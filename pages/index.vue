<script setup lang="ts">
import WhoAmI from "~/components/WhoAmI.vue";
</script>

<template>
  <div class="min-h-[100vh]">
    <div class="min-h-[100vh] flex justify-center items-center flex-col gap-3">
      <img
        src="https://avatars.githubusercontent.com/u/173285554?v=4"
        alt="wizard"
        class="rounded-full shadow-xl w-[170px]"
      />
      <h1 class="text-4xl font-bold underline text-center">wizard-lgtm</h1>
      <ul
        class="flex gap-3 translate-y-3 transition-all duration-300 ease-in-out"
      >
        <li class="underline cursor-pointer">Ziglang</li>
        <li class="underline cursor-pointer">Kernel dev</li>
      </ul>
    </div>
    <WhoAmI />
    <Footer />
  </div>
</template>
