<script setup>
</script>
<template>
    <div class="top-head">
        <span class="fw-bold">WhatsApp</span>

        <div class="justify-content-center">
            <i class="fa fa-camera px-3"> </i>
            <i class="fa fa-search px-3"> </i>
            <i class="fa fa-ellipsis-v px-3"> </i>
        </div>
    </div>

    <div class="position-sticky" style="top: 0rem; z-index: 2000 !important;">
        <div class="head-nav">
            <a class="flex-fill ps-2 fa fa-users forCommunity" data-bs-target="#screens" data-bs-slide-to="0"></a>
            <a class="flex-fill ps-2 text-center active forChat" data-bs-target="#screens" data-bs-slide-to="1"> Chats <span
                    class="badge tab-badge-color active-tab rounded-circle p-1">23</span></a>
            <a class="flex-fill ps-2 text-center forStatus" data-bs-target="#screens" data-bs-slide-to="2">Status </a>
            <a class="flex-fill ps-2 text-center forCalls" data-bs-target="#screens" data-bs-slide-to="3">Calls</a>
        </div>
    </div>
</template>