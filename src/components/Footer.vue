<template>
    <footer class="bg-veryDarkBlue">
        <div
            class="container flex justify-between items-center flex-col-reverse mx-auto md:flex-row"
        >
            <div class="flex flex-col container mx-auto p-4">
                <div class="p-2 flex justify-center md:justify-start">
                    <img src="../img/logo-white.svg" alt="" />
                </div>
            </div>
            <!-- List Container -->
            <div
                class="flex space-x-20 container justify-center mx-auto px-4 py-8 md:justify-start"
            >
                <div class="flex flex-col space-y-3 text-white">
                    <a href="#" class="hover:text-brightRed">Home</a>
                    <a href="#" class="hover:text-brightRed">Pricing</a>
                    <a href="#" class="hover:text-brightRed">Products</a>
                    <a href="#" class="hover:text-brightRed">About</a>
                </div>
                <div class="flex flex-col space-y-3 text-white">
                    <a href="#" class="hover:text-brightRed">Careers</a>
                    <a href="#" class="hover:text-brightRed">Community</a>
                    <a href="#" class="hover:text-brightRed">Privacy Policy</a>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "Footer",
};
</script>
