<template>
    <div class="space-y-10 text-center md:text-left md:w-1/2">
        <h1 class="text-4xl font-bold max-w-md">
            Bring everyone together to build better products
        </h1>
        <p class="text-darkGrayishBlue max-w-sm mx-auto md:mx-0">
            Manage makes it simple for software teams to plan day-to-day tasks
            while keeping the larger team goals in view.
        </p>
        <Button btnName="Get Started" />
    </div>
    <!-- Item 2 -->
    <div class="md:w-1/2">
        <img src="../img/illustration-intro.svg" alt="" />
    </div>
</template>

<script>
import Button from "./Button.vue";

export default {
    name: "Hero",
    components: {
        Button,
    },
};
</script>

<style></style>
