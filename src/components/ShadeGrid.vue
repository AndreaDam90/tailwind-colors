<template>
    <div class="grid w-96">
        <ColorSquare
            v-for="(gradient, index) in gradients"
            :key="index"
            :class="`bg-${tailwindClass}-${gradient}`"
            :to-be-copied="shades[index]"
            >{{ shades[index] }}</ColorSquare
        >
    </div>
</template>

<script setup>
import { ref } from "vue";
import ColorSquare from "./ColorSquare.vue";

defineProps(["tailwindClass", "shades"]);

const gradients = ref(["50", "100", "200", "300", "400", "500", "600", "700", "800", "900", "950"]);
</script>
