<script setup>
import { onMounted } from 'vue';

</script>
<template>
    <div class="row text-start">
        <div class="d-flex justify-content-between mt-3">
            <img src="/avatar.jpg" height="45" width="45" class="rounded-circle me-3">
            <span class="flex-grow-1 gchat pt-2">
                <h6 class="fw-bold">Create call link</h6>
                <p class="text-muted">Share a link for your whatsapp call</p>
            </span>
        </div>
        <p class="mt-4 text-muted">Recent</p>
        <template v-for="i in 12">            
            <div class="d-flex justify-content-between mt-3">
                <img src="/user-2.jpg" height="45" width="45" class="rounded-circle me-3">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">My heart 😀😂👌❤️😍</h6>
                    <p class="text-muted"><i class="fa fa-long-arrow-down picked-call"> </i> Today, 6:25 PM</p>
                </span>
            <i class="fa fa-video-camera green px-3 pt-3"> </i>
            </div>
            <div class="d-flex justify-content-between mt-3">
                <img src="/stat.png" height="45" width="45" class="rounded-circle me-3">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">Chinese HR</h6>
                    <p class="text-muted"><i class="fa fa-long-arrow-down missed-call"> </i> Today, 6:25 PM</p>
                </span>
            <i class="fa fa-phone green px-3 pt-3"> </i>
            </div>

            <div class="d-flex justify-content-between mt-3">
                <img src="/stat.png" height="45" width="45" class="rounded-circle me-3">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">Chinese HR</h6>
                    <p class="text-muted"><i class="fa fa-long-arrow-down picked-call"> </i> Today, 6:25 PM</p>
                </span>
            <i class="fa fa-video-camera green px-3 pt-3"> </i>
            </div>
            <div class="d-flex justify-content-between mt-3">
                <img src="/zen.png" height="45" width="45" class="rounded-circle me-3">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">ZenPen Writers' Community</h6>
                    <p class="text-muted"><i class="fa fa-long-arrow-down picked-call"> </i> March 22, 6:25 PM</p>
                </span>
            <i class="fa fa-phone green px-3 pt-3"> </i>
            </div>
            
            <div class="d-flex justify-content-between mt-3">
                <img src="/user-2.jpg" height="45" width="45" class="rounded-circle me-3">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">My heart 😀😂👌❤️😍</h6>
                    <p class="text-muted">Today, 6:25 PM</p>
                </span>
            <i class="fa fa-video-camera green px-3 pt-3"> </i>
            </div>

             

        </template>
        
        <div class="fab-container write">
            <div class="fab write shadow">
                <div class="fab-content">
                    <i class="fa fa-pencil"></i>
                </div>
            </div>
        </div>
        <div class="fab-container">
            <div class="fab shadow">
                <div class="fab-content">
                    <i class="fa fa-camera"></i>
                </div>
            </div>
        </div>
    </div>
</template>