<script lang="ts" setup>
</script>
<template>
    <div
        class="relative w-full h-screen bg-[url(@/assets/images/hero-image.webp)] bg-cover bg-no-repeat bg-center text-white px-10 py-5">
        <div class="absolute w-full h-full left-0 top-0 bg-black opacity-40 z-0"></div>
        <nav class="relative w-full flex justify-between z-10">
            <div class="text-2xl font-bold">DANGDI</div>
            <ul class="flex items-center gap-10">
                <li>最初のメニュー</li>
                <li>セカンドメニュー</li>
                <li>3番目のメニュー</li>
                <li>
                    <button class="bg-white text-black rounded-full px-4 py-2">アクションボタン</button>
                </li>
            </ul>
        </nav>
        <div class="relative w-full h-full flex items-center justify-center z-10">
            <div class="container flex justify-between items-center">
                <div class="space-y-6">
                    <div class="h-[100px] flex justify-center items-center bg-gray-100 rounded-lg">
                        <p class="text-black">受賞画像はこちら</p>
                    </div>
                    <h1 class="text-7xl font-bold">長いタイトルはこちら</h1>
                    <p class="text-xl">これは説明例です後で変更できます</p>
                    <div class="flex items-center">
                        <img src="@/assets/images/profile.webp" width="50" height="50"
                            class="w-[50px] h-[50px] rounded-full border-2 border-white" />
                        <img src="@/assets/images/profile.webp" width="50" height="50"
                            class="w-[50px] h-[50px] rounded-full -ml-2 border-2 border-white" />
                        <img src="@/assets/images/profile.webp" width="50" height="50"
                            class="w-[50px] h-[50px] rounded-full -ml-2 border-2 border-white" />
                        <img src="@/assets/images/profile.webp" width="50" height="50"
                            class="w-[50px] h-[50px] rounded-full -ml-2 border-2 border-white" />
                        <img src="@/assets/images/profile.webp" width="50" height="50"
                            class="w-[50px] h-[50px] rounded-full -ml-2 border-2 border-white" />
                        <img src="@/assets/images/profile.webp" width="50" height="50"
                            class="w-[50px] h-[50px] rounded-full -ml-2 border-2 border-white" />
                        <img src="@/assets/images/profile.webp" width="50" height="50"
                            class="w-[50px] h-[50px] rounded-full -ml-2 border-2 border-white" />
                        <img src="@/assets/images/profile.webp" width="50" height="50"
                            class="w-[50px] h-[50px] rounded-full -ml-2 border-2 border-white" />
                    </div>
                </div>
                <div class="w-[500px] bg-white h-full space-y-4 p-4">
                    <input placeholder="ここで検索してください" class="w-full h-[50px] bg-white border border-gray-500 p-4" />
                    <button class="w-full bg-black text-white px-6 py-3 rounded-full">ボタンアクション</button>
                    <p class="text-black text-center">簡単な説明</p>
                </div>
            </div>
        </div>
    </div>
</template>