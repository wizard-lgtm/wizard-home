<template>
  <div
    class="min-h-[100vh] text-center flex flex-col justfiy-center items-center"
  >
    <div
      class="bg-[url('/assets/peakpx.jpg')] bg-cover w-[75%] h-[80vh] rounded-lg overflow-hidden shadow-custom"
    >
      <div
        class="w-full h-full backdrop-blur-md pt-12 flex flex-col flex-nowrap"
      >
        <h1
          class="text-4xl font-bold backdrop-blur-lg bg-slate-800 bg-opacity-30 inline-block p-4 rounded-full"
        >
          Who I Am?
        </h1>
        <br />
        <div
          class="backdrop-blur-lg bg-slate-800 bg-opacity-20 p-12 inline-block rounded flex gap-4 justify-center"
        >
          <h3 class="flex items-center text-xl font-semibold">A person</h3>
          <ul class="">
            <li>who is calm</li>
            <li>who is loves coding</li>
            <li>who is loves <span class="underline">people</span></li>
          </ul>
        </div>
        <div
          class="backdrop-blur-lg p-12 inline-block rounded flex flex-col gap-4 justify-center"
        >
          <h3>Sooo...</h3>
          <h4>Just a normal one,</h4>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup></script>

<style>
.shadow-custom {
  /* https://smoothshadows.com/#djEsMSw1LDAuMTQsMTM3LC0xMSw4LCNlOGU5ZWQsIzI1MjYyNywjZmZmZmZmLDI%3D */
  box-shadow: 0px -0px 5px rgba(232, 233, 237, 0.03),
    1px -2px 22px rgba(232, 233, 237, 0.06),
    3px -4px 49px rgba(232, 233, 237, 0.08),
    5px -7px 88px rgba(232, 233, 237, 0.11),
    8px -11px 137px rgba(232, 233, 237, 0.14);
}
</style>
