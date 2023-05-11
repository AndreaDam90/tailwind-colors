<template>
    <!-- Schermata Mobile -->
    <div
        v-if="width <= 1024 && orientation === 'portrait-primary'"
        class="flex h-screen w-screen flex-col items-center justify-center gap-5 bg-slate-900 p-5 text-white">
        <h1 class="text-center text-5xl">Tailwind Colors</h1>
        <h2 class="text-2xl italic">by Andrea Damiani</h2>
        <Icon icon="material-symbols:mobile-off-rounded" class="text-9xl" />
        <h2 class="text-center text-3xl">Quest'app è utilizzabile solo su uno schermo grande.</h2>
    </div>

    <!-- Schermata Desktop -->
    <main v-else class="flex h-screen">
        <ShadeGrid v-for="(color, index) in colors" :key="index" :tailwind-class="color.color" :shades="color.shades" />
    </main>
</template>

<script setup>
import { useWindowSize, useScreenOrientation } from "@vueuse/core";
import { Icon } from "@iconify/vue";

import ShadeGrid from "./components/ShadeGrid.vue";

import colors from "./data/colors.json";

const { width } = useWindowSize();
const { orientation } = useScreenOrientation();
</script>
