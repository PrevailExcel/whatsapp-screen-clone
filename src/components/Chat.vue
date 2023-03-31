<script setup>
import { onMounted } from 'vue';

</script>
<template>
    <div class="row text-start">
        <div class="d-flex justify-content-between mt-3">
            <i class="fa fa-archive mx-3 me-4"> </i>
            <span class="flex-grow-1 gchat">
                <h6 class="fw-bold">Archived</h6>
            </span>
            <small class="small-date mt-auto mb-auto green">10</small>
        </div>
        <template v-for="i in 12">
            <div class="d-flex justify-content-between mt-3">
                <img src="/user.jpg" height="45" width="45" class="rounded-circle me-3">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">Prevail Ejimadu</h6>
                    <p class="text-muted">thank you</p>
                </span>
                <small class="small-date mt-auto mb-auto text-muted">yesterday</small>
            </div>
            <div class="d-flex justify-content-between mt-3">
                <img src="/avatar.jpg" height="45" width="45" class="rounded-circle me-3 status">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">Chimeremeze Ejimadu</h6>
                    <p class="text-muted">agba developer!</p>
                </span>
                <small class="small-date mt-auto mb-auto text-muted">4:40 PM</small>
            </div>
            <div class="d-flex justify-content-between mt-3">
                <img src="/user-2.jpg" height="45" width="45" class="rounded-circle me-3">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">My heart 😀😂👌❤️😍 </h6>
                    <p class="text-muted">good evening API Daddy, how are yo...</p>
                </span>
                <small class="small-date m-auto ms-auto text-muted green">4:40 PM
                    <p><span class="badge tab-badge-color rounded-circle mt-1 px-1 py-1">12</span></p>
                </small>
            </div>
            <div class="d-flex justify-content-between mt-3">
                <img src="/zen.png" height="45" width="45" class="rounded-circle me-3">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">ZenPens Writers' Community</h6>
                    <p class="text-muted">~Somtoochukwu: <i class="fa fa-image"> </i> Happy bir...</p>
                </span>
                <small class="small-date m-auto ms-auto text-muted green">12:30 AM
                    <p><b class="fs-6 green">@ </b> <span
                            class="badge tab-badge-color rounded-circle mt-1 px-1 py-1">97</span></p>
                </small>
            </div>
            <div class="d-flex justify-content-between mt-3">
                <img src="/user-3.jpg" height="45" width="45" class="rounded-circle me-3 status">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">Dr Ebele Project Supervisor </h6>
                    <p class="text-muted">If you don't submit your project tomo...</p>
                </span>
                <small class="small-date mt-auto mb-auto text-muted">4:40 PM</small>
            </div>
            <div class="d-flex justify-content-between mt-3">
                <img src="/soft.jpg" height="45" width="45" class="rounded-circle me-3">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">SoftAmplify tech <img src="/lap.png" height="15" width="15"> </h6>
                    <p class="text-muted">~Engr Tim: Twitter space tonight...</p>
                </span>
                <small class="small-date m-auto ms-auto text-muted green">4:40 PM
                    <p><span class="badge tab-badge-color rounded-circle mt-1 px-1 py-1">97</span></p>
                </small>
            </div>
        </template>

        <div class="fab-container">
            <div class="fab shadow">
                <div class="fab-content">
                    <i class="fa fa-comment"></i>
                </div>
            </div>
        </div>
    </div>
</template>