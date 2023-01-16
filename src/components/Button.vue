<template>
    <button
        :class="[
            `bg-brightRed p-4 mx-1 text-white rounded-full duration-300 hover:bg-brightRedLight`,
            btnClasses,
        ]"
    >
        {{ btnName }}
    </button>
</template>

<script>
export default {
    name: "Button",
    props: {
        btnName: String,
        btnClasses: String,
    },
};
</script>
