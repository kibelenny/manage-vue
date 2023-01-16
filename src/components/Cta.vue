<template>
    <h1
        class="font-bold text-4xl text-center text-white md:max-w-xl md:text-left"
    >
        Simplify how your team works today
    </h1>
    <div>
        <Button btnName="Get Started" :btnClasses="btnClasses" />
    </div>
</template>

<script>
import Button from "./Button.vue";
export default {
    name: "Cta",
    components: {
        Button,
    },
    data() {
        return {
            btnClasses: "border-2 border-white",
        };
    },
};
</script>
