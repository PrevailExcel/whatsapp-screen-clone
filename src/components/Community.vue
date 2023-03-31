<script setup>
import { onMounted } from 'vue';

</script>
<template>
    <div class="row text-start mb-3">
        <div class="d-flex justify-content-between mt-3 lighter-bg">
            <span class="rounded me-3 bg-dark p-2 position-relative"><i class="px-2 py-1 fa fa-users"> </i>
                <span class="position-absolute bottom-0 end-0 add-com"><i class="rounded-circle bg-success p-1 fa fa-plus"></i></span>
</span>
            <span class="flex-grow-1 gchat pt-2">
                <h6 class="fw-bold">New community</h6>
            </span>
        </div>
            <span class="mt-3 py-1 bg-dark"></span>  

        <template v-for="i in 3">
            <div class="row my-3">
                <div class="d-flex justify-content-between mt-3">
                    <span class="rounded me-3 bg-dark p-2"><i class="px-2 py-1 fa fa-users"> </i></span>
                    <span class="flex-grow-1 gchat pt-2">
                        <h6 class="fw-bold">Software Engineers Global</h6>
                    </span>
                </div>
                <hr class="my-2">
                <template v-for="j in 2">
                    <div class="d-flex justify-content-between mt-3">
                        <img src="/stat-3.jpg" height="45" width="45" class="rounded-circle me-3">
                        <span class="flex-grow-1 gchat pt-2">
                            <h6 class="fw-bold">Software Engineers {{ j }}</h6>
                        </span>
                        <small class="small-date m-auto ms-auto text-muted">4:40 PM </small>
                    </div>
                </template>
            </div>
            <span class="py-1 bg-dark"></span>
            <div class="row my-3">
                <div class="d-flex justify-content-between mt-3">
                    <span class="rounded me-3 bg-dark p-2"><i class="px-2 py-1 fa fa-users"> </i></span>
                    <span class="flex-grow-1 gchat pt-2">
                        <h6 class="fw-bold">Poets in Nigeria</h6>
                    </span>
                </div>
                <hr class="my-2">
                <template v-for="j in 2">
                    <div class="d-flex justify-content-between mt-3">
                        <img src="/stat-2.jpg" height="45" width="45" class="rounded-circle me-3">
                        <span class="flex-grow-1 gchat pt-2">
                            <h6 class="fw-bold">PIN Group {{ j }}</h6>
                        </span>
                        <small class="small-date m-auto ms-auto text-muted">4:40 PM </small>
                    </div>
                </template>
            </div>

            <span class="py-1 bg-dark"></span>        </template>
    </div>
</template>