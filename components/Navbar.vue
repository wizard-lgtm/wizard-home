<template>
    <div class="sm:px-12 p-4 navbar opacity-0 -translate-y-[50px]">
        <div
            class="flex bg-slate-400 py-4 bg-opacity-5 justfiy-center text-center backdrop-blur-lg justify-between px-12 rounded-md"
        >
            <div class="cursor-pointer font-bold text-xl flex items-center">
                :3
            </div>
            <div class="flex justify-end gap-8 items-center">
                <div class="cursor-pointer hidden sm:block">Source</div>
                <div class="cursor-pointer hidden sm:block">Posts</div>
                <div
                    class="cursor-pointer bg-[#ECDFCC] text-[#222831] py-2 px-3 rounded-lg transition-all duration-300 ease-in-out hover:bg-opacity-70 md:block"
                >
                    Contact Me
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import gsap from "gsap";

onMounted(() => {
    const navbar = document.querySelector(".navbar");
    gsap.to(navbar, {
        opacity: 1,
        translateY: 0,
        delay: 2.5,
        duration: 1,
        ease: "power1",
    });
});
</script>

<style></style>
