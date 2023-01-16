<template>
    <nav class="container mx-auto my-4 p-4">
        <div class="flex items-center justify-between flex-row">
            <!-- Logo -->
            <div class="p-2">
                <img src="../img/logo.svg" alt="" />
            </div>
            <!-- Navbar Items -->
            <div class="hidden flex-row space-x-6 md:flex">
                <a href="" class="hover:text-darkGrayishBlue">Pricing</a>
                <a href="" class="hover:text-darkGrayishBlue">Product</a>
                <a href="" class="hover:text-darkGrayishBlue">About Us</a>
                <a href="" class="hover:text-darkGrayishBlue">Careers</a>
                <a href="" class="hover:text-darkGrayishBlue">Community</a>
            </div>
            <!-- Button -->
            <Button btnName="Get Started" />
        </div>
    </nav>
</template>

<script>
import Button from "./Button.vue";
export default {
    name: "Header",
    components: {
        Button,
    },
};
</script>

<style></style>
