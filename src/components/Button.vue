<script setup lang="ts">
defineProps({
    href: String,
    class: String,
    target: {
        type: String,
        default: "_blank",
    },
});
</script>

<template>
    <a :href="href" :target="target">
        <button
            :class="$props.class"
            class="bg-gray-200 cursor-pointer border-black border-2 text-black rounded-xl w-40 h-10"
        >
            <slot />
        </button>
    </a>
</template>
