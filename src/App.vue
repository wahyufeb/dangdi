<script setup lang="ts">
import Hero from './components/Hero.vue'
import Profile from './components/Profile.vue'
import About from './components/About.vue';
import Feature from './components/Feature.vue';
</script>

<template>
  <Hero />
  <Profile />
  <About />
  <Feature title="最初の例の機能"
    description="市トン荷掲院スネメ惑話よねべ流断せすめた話盟うフれめ江導や政花とをドフ情邦策モウ備引びゅぐ職芸ヤク由塚せも島問ロカ末盤花がむー。飛ッせゅ周8検素ぼごぶい断決更リ検学ちド点要タ木失ノヱ公首リミアケ載質格ハ並天化係ぞぴめぽ技町削だう"
    :background-class="'bg-[#63CEB9]'">
    <img src="@/assets/images/feature-image-1.webp" width="300" height="700"
      class="w-[400px] h-[800px] object-cover rounded-3xl" />
    <img src="@/assets/images/feature-image-2.webp" width="300" height="700"
      class="w-[400px] h-[800px] object-cover rounded-3xl mt-20" />
  </Feature>
  <Feature title="2 番目の例の機能"
    description="市トン荷掲院スネメ惑話よねべ流断せすめた話盟うフれめ江導や政花とをドフ情邦策モウ備引びゅぐ職芸ヤク由塚せも島問ロカ末盤花がむー。飛ッせゅ周8検素ぼごぶい断決更リ検学ちド点要タ木失ノヱ公首リミアケ載質格ハ並天化係ぞぴめぽ技町削だう"
    :background-class="'bg-[#7650D8]'">
    <img src="@/assets/images/feature-image-1.webp" width="300" height="700"
      class="w-[400px] h-[800px] object-cover rounded-3xl" />
    <img src="@/assets/images/feature-image-2.webp" width="300" height="700"
      class="w-[400px] h-[800px] object-cover rounded-3xl" />
  </Feature>
  <Feature title="3 番目の例の機能"
    description="市トン荷掲院スネメ惑話よねべ流断せすめた話盟うフれめ江導や政花とをドフ情邦策モウ備引びゅぐ職芸ヤク由塚せも島問ロカ末盤花がむー。飛ッせゅ周8検素ぼごぶい断決更リ検学ちド点要タ木失ノヱ公首リミアケ載質格ハ並天化係ぞぴめぽ技町削だう"
    :background-class="'bg-[#F3982A]'">
    <img src="@/assets/images/feature-image-1.webp" width="300" height="700"
      class="w-[400px] h-[800px] object-cover rounded-3xl" />
    <img src="@/assets/images/feature-image-2.webp" width="300" height="700"
      class="w-[400px] h-[800px] object-cover rounded-3xl" />
  </Feature>
</template>
