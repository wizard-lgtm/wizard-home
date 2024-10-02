<template>
  <html :class="{ dark: darkMode }">
    <div class="min-h-[100vh] dark:bg-[#222831] text-[#ECDFCC] box-border">
      <Navbar />
      <NuxtPage />
    </div>
  </html>
</template>
<script setup>
const dark = true;
const darkMode = ref(dark);
</script>
