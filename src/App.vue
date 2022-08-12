<script setup lang="ts">
  // This starter template is using Vue 3 <script setup> SFCs
  // Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
  import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="flex flex-col fixed t-0 l-0 h-full w-full justify-evenly">
    <div class="flex justify-evenly">
      <a href="https://www.electronjs.org/">
        <img style="height: 140px" src="@/assets/electron.png" />
      </a>
      <a href="https://vitejs.dev/">
        <img style="height: 140px" src="@/assets/vite.svg" />
      </a>
    </div>
    <div class="flex justify-evenly">
      <a href="https://vuejs.org/">
        <img style="height: 140px" src="@/assets/vue.png" />
      </a>
      <a href="https://tailwindcss.com/">
        <img style="height: 120px" src="@/assets/tailwind.svg" />
      </a>
    </div>
  </div>
</template>

<style scoped lang="scss">
  $w: 10px;
</style>
