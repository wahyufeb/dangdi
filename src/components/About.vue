<script lang="ts" setup>
import { ref } from 'vue';

const isShowVideo = ref(false)
</script>
<template>
    <div class="relative w-full h-full flex items-center justify-center z-10 py-40">
        <div class="container flex flex-col gap-10">
            <div class="space-y-4">
                <h1 class="text-8xl font-bold">について</h1>
                <h1 class="text-8xl font-bold ml-40">ABOUT</h1>
            </div>
            <template v-if="isShowVideo">
                <iframe height="850"
                    src="https://www.youtube.com/embed/AY5qcIq5u2g?autoplay=1&disablekb=1&fs=1&modestbranding=1&rel=0&playsinline=1"
                    title="YouTube video player" frameborder="0"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                    referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </template>
            <div v-else class="relative">
                <div class="absolute w-full h-full left-0 top-0 bg-black opacity-40 z-0"></div>
                <div class="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 w-[90px] h-[90px] rounded-full bg-transparent backdrop-blur-sm flex justify-center items-center cursor-pointer"
                    @click="isShowVideo = true">
                    <img src="@/assets/icons/play-icon.svg" class="w-[40px] h-[40px]" />
                </div>
                <img src="https://img.youtube.com/vi/AY5qcIq5u2g/maxresdefault.jpg"
                    class="w-full h-[850px] object-cover" />
            </div>
        </div>
    </div>
</template>