<script lang="ts" setup>
const props = defineProps<{
    title: string
    description: string
    backgroundClass: string
}>()
</script>

<template>
    <div :class="`relative w-full h-[1000px] flex justify-center py-20 ${props.backgroundClass}`">
        <div class="container flex gap-40">
            <div class="w-2/6">
                <div class="w-[100px] h-[100px] flex justify-center items-center rounded-xl bg-gray-100 mb-8">ここのアイコン
                </div>
                <h3 class="text-7xl font-bold text-white mb-16">{{ props.title }}</h3>
                <p class="text-xl text-white">
                    {{ props.description }}
                </p>
            </div>
            <div class="w-4/6 flex gap-8">
                <slot></slot>
            </div>
        </div>
    </div>
</template>