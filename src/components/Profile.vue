<script lang="ts" setup>
import { ref } from 'vue';

const isShowVideo = ref(false)
</script>
<template>
    <div class="relative w-full h-full flex items-center justify-center z-10 py-40">
        <div class="container flex justify-between">
            <div class="w-1/2 flex flex-col justify-between">
                <div class="space-y-4">
                    <h1 class="text-8xl font-bold">名前の例</h1>
                    <h1 class="text-8xl font-bold text-right">Example Name</h1>
                    <div>
                        <span class="block text-4xl">analyst.</span>
                        <span class="block text-4xl">writer.</span>
                    </div>
                </div>
                <div class="space-y-10">
                    <p class="text-2xl">
                        表ぽろーげ式酩演よ全仕ワケロス開民ケナモ下車サテ聞壊表オ意界ヱナネ治長ぐたそね堂北け載刊めよ語政んつに公余掲どさふら提中ば車今イエケテ願祭イごい。等オ理画収ヘモヱ部9公ワレナ訪禁入ルーなの学20明うっづき書吉アフミ放展層ンえぶ力年ヱメ異宅シ気発ぼりわ同宅相京寮ぞにちす。長めわづを学周ヱ米76典っくへ力債がゃク治子臨りじさ断経格めげ女込市ラワユ毛務ぐルう。
                    </p>
                    <div
                        class="w-[125px] h-[125px] bg-transparent border-2 border-black rounded-full flex justify-center items-center cursor-pointer hover:opacity-50">
                        <img src="@/assets/icons/navigation.svg" width="60" height="60" class="w-[70px] h-[70px]" />
                    </div>
                </div>
            </div>
            <div class="w-1/2 flex justify-end">
                <template v-if="isShowVideo">
                    <iframe width="700" height="1100"
                        src="https://www.youtube.com/embed/KRntP-q_R9s?autoplay=1&disablekb=1&fs=1&modestbranding=1&rel=0&playsinline=1&start=16"
                        title="YouTube video player" frameborder="0"
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                        referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                </template>
                <template v-else>
                    <div class="relative">
                        <div class="absolute w-full h-full left-0 top-0 bg-black opacity-40 z-0"></div>
                        <div class="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 w-[90px] h-[90px] rounded-full bg-transparent backdrop-blur-sm flex justify-center items-center cursor-pointer"
                            @click="isShowVideo = true">
                            <img src="@/assets/icons/play-icon.svg" class="w-[40px] h-[40px]" />
                        </div>
                        <img src="@/assets/images/founder.webp" alt="profile" width="450" height="750"
                            class="min-w-[700px] max-w-[700px] min-h-[1100px] max-h-[1100px] object-cover" />
                    </div>
                </template>
            </div>
        </div>
    </div>
</template>