<template>
    <Header />
    <Section nameSection="Hero" :extraClass="heroClasses" />
    <Section nameSection="Features" />
    <Text :text="avatarText" />
    <Section nameSection="Avatars" />
    <div class="text-center">
        <Button btnName="Get Started" />
    </div>
    <Section nameSection="Cta" :extraClass="ctaClasses" />
    <Footer />
</template>
<script>
import Header from "./components/Header.vue";
import Section from "./components/Section.vue";
import Button from "./components/Button.vue";
import Text from "./components/Text.vue";
import Footer from "./components/Footer.vue";

export default {
    name: "App",
    components: {
        Header,
        Section,
        Text,
        Button,
        Footer,
    },
    data() {
        return {
            avatarText: "What's Different About Manage?",
            heroClasses:
                "md:flex-row flex-col-reverse items-center justify-center",
            ctaClasses: "py-8 px-6 items-center justify-between",
        };
    },
};
</script>

<style></style>
