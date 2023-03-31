<script setup>
import Head from './Head.vue';
import Chat from './Chat.vue';
import Status from './Status.vue';
import Calls from './Calls.vue';
import Community from './Community.vue';
import { onMounted } from 'vue';

onMounted(() => {
    var myCarousel = document.getElementById('screens')

    myCarousel.addEventListener('slide.bs.carousel', function (e) {        
        document.querySelectorAll('a[data-bs-target]').forEach(e => {
                e.classList.remove('active')
            });
        if (e.relatedTarget.classList.contains("forCommunity")) {
            document.querySelector('a.forCommunity').classList.add('active')
        }
        if (e.relatedTarget.classList.contains("forChat")) {
            document.querySelector('a.forChat').classList.add('active')
        }
        if (e.relatedTarget.classList.contains("forStatus")) {
            document.querySelector('a.forStatus').classList.add('active')
        }
        if (e.relatedTarget.classList.contains("forCalls")) {
            document.querySelector('a.forCalls').classList.add('active')
        }
    })
})
</script>
<template>
    <Head />
    <main class="container px-3">
        <div class="row">
            <div class="mx-auto mt-2 center text-center">
                <div id="screens" class="carousel slide" data-bs-ride="carousel" data-bs-interval="false">
                    <div class="carousel-inner">
                        <div class="carousel-item forCommunity">
                            <Community />
                        </div>
                        <div class="carousel-item forChat active">
                            <Chat />
                        </div>
                        <div class="carousel-item forStatus">
                            <Status />
                        </div>
                        <div class="carousel-item forCalls">
                            <Calls />
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>