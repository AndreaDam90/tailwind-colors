<template>
    <button class="group relative" @click="copy(toBeCopied)" :disabled="copied">
        <div
            class="absolute bottom-0 top-0 flex w-full items-center justify-center bg-neutral-200/20 font-semibold opacity-0 transition-opacity duration-100 ease-in group-hover:opacity-100">
            <Icon v-if="copied" :icon="doneRounded" class="text-4xl" />
            <slot v-else></slot>
        </div>
    </button>
</template>

<script setup>
import { useClipboard } from "@vueuse/core";

import { Icon } from "@iconify/vue";
import doneRounded from "@iconify-icons/material-symbols/done-rounded";

defineProps(["toBeCopied"]);

const { copy, copied } = useClipboard();
</script>
