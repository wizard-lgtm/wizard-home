<template>
    <div
        ref="scrollContainer"
        class="min-h-[100vh] flex justify-center items-center flex-col gap-3"
    >
        <img
            src="https://avatars.githubusercontent.com/u/173285554?v=4"
            alt="wizard"
            class="rounded-full landing shadow-xl w-[170px] image"
        />
        <h1 class="text-4xl font-bold underline opacity-0 text-center image">
            wizard-lgtm
        </h1>
        <ul class="flex gap-3 translate-y-3 opacity-0 image">
            <li class="underline cursor-pointer">Ziglang</li>
            <li class="underline cursor-pointer">Kernel dev</li>
        </ul>
    </div>
</template>

<script setup>
import gsap from "gsap";

gsap.registerPlugin("ScrollTrigger");
const scrollContainer = ref(); // Init container

function addScrollTrigger() {
    const tl = gsap.timeline();
    tl.fromTo(
        ".image",
        {
            opacity: 0,
            translateY: 50,
            ease: "power1.out",
            duration: 1,
        },
        {
            opacity: 1,
            translateY: 0,
            ease: "power1.out",
            duration: 1,
            delay: 0.4,
            stagger: 0.7,
        },
    );
}

onMounted(() => {
    addScrollTrigger();
});
</script>
