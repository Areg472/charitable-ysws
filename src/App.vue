<script setup lang="ts">
import Button from "./components/Button.vue";
import Faq from "./components/Faq.vue";

// import Navbar from "./components/Navbar.vue";
</script>

<template>
    <!-- <div class="flex flex-row mt-4 items-center justify-center">
        <Navbar />
    </div> -->
    <div class="flex flex-col mt-12 items-center justify-center text-black">
        <h1 class="text-4xl font-bold">Charitable YSWS!</h1>
        <p class="text-2xl mt-4">Make Projects</p>
        <p class="text-2xl mt-4">Ship Projects</p>
        <p class="text-2xl mt-4 text-center px-4">
            Donate to Charities, Non-Profits, or Projects!
        </p>
        <Button href="https://forms.fillout.com/t/8x9AqPpK4nus" class="mt-4">
            RSVP Now!
        </Button>
        <Faq />
    </div>
</template>
