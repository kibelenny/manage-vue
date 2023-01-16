<template>
    <div
        id="card"
        class="flex flex-col items-center rounded-3xl bg-gray-50 duration-500 hover:bg-gray-100 hover:shadow-lg"
    >
        <!-- Img -->
        <div class="flex flex-col space-y-4 items-center">
            <img :src="url" alt="" class="-mt-11 w-28 md:-mt-14" />

            <div class="p-5 space-y-4 flex flex-col">
                <!-- Name -->
                <h3 class="font-bold text-center">{{ name }}</h3>
                <!-- Testimonial -->
                <p class="text-darkGrayishBlue text-sm text-center">
                    {{ desc }}
                </p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Avatar",
    props: {
        url: String,
        name: String,
        desc: String,
    },
};
</script>
