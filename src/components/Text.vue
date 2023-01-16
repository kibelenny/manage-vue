<template>
    <div class="container mx-auto">
        <h2 class="text-center font-bold text-3xl my-32">{{ text }}</h2>
    </div>
</template>

<script>
export default {
    name: Text,
    props: {
        text: String,
    },
};
</script>
