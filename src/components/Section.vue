<template>
    <section :id="nameSection">
        <div :class="['main-div', extraClass]">
            <component :is="currentSection" />
        </div>
    </section>
</template>

<script>
import Hero from "./Hero.vue";
import Features from "./Features.vue";
import Avatars from "./Avatars.vue";
import Cta from "./Cta.vue";

export default {
    name: "Section",
    props: {
        nameSection: String,
        extraClass: String,
    },
    data() {
        return {
            currentSection: " ",
        };
    },
    components: {
        Hero,
        Features,
        Avatars,
        Cta,
    },

    methods: {
        changeSection() {
            this.currentSection = this.nameSection;
        },
    },

    beforeMount() {
        this.changeSection();
    },
};
</script>

<style></style>
