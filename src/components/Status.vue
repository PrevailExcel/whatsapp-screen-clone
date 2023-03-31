<script setup>
import { onMounted } from 'vue';

</script>
<template>
    <div class="row text-start">
        <div class="d-flex justify-content-between mt-3">
            <img src="/avatar.jpg" height="45" width="45" class="rounded-circle me-3">
            <span class="flex-grow-1 gchat pt-2">
                <h6 class="fw-bold">My Status</h6>
                <p class="text-muted">Today, 9:16 AM</p>
            </span>
            <i class="fa fa-ellipsis-h px-3 pt-2"> </i>
        </div>
        <p class="mt-4 text-muted">Recent updates</p>
        <template v-for="i in 12">
            <div class="d-flex justify-content-between mt-3">
                <img src="/stat.png" height="45" width="45" class="rounded-circle me-3 status two">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">Happiness RM</h6>
                    <p class="text-muted">2 minutes ago</p>
                </span>
            </div>
            <div class="d-flex justify-content-between mt-3">
                <img src="/stat-2.jpg" height="45" width="45" class="rounded-circle me-3 status seen">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">My heart 😀😂👌❤️😍</h6>
                    <p class="text-muted">4 hours ago</p>
                </span>
            </div>
            <div class="d-flex justify-content-between mt-3">
                <img src="/stat-3.jpg" height="45" width="45" class="rounded-circle me-3 status two">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">Asap Tv</h6>
                    <p class="text-muted">4 hours ago</p>
                </span>
            </div>
            <div class="d-flex justify-content-between mt-3">
                <img src="/fire.png" height="45" width="45" class="rounded-circle me-3 status two seen">
                <span class="flex-grow-1 gchat pt-2">
                    <h6 class="fw-bold">Asap Tv</h6>
                    <p class="text-muted">4 hours ago</p>
                </span>
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