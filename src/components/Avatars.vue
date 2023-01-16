<template>
    <div class="md:w-1/3 py-10" v-for="user in users">
        <Avatar :url="user.url" :name="user.name" :desc="user.desc" />
    </div>
</template>

<script>
import Avatar from "./Avatar.vue";

export default {
    name: "Avatars",
    components: {
        Avatar,
    },
    data() {
        return {
            users: {
                user1: {
                    url: "./src/img/avatar-anisha.png",
                    name: "Anisha Li",
                    desc: `“Manage has supercharged our team’s workflow. The ability to maintain visibility on larger milestones at all times keeps everyone motivated.”`,
                },
                user2: {
                    url: "./src/img/avatar-ali.png",
                    name: "Ali Bravo",
                    desc: `“We have been able to cancel so many other subscriptions since using Manage. There is no more cross-channel confusion and everyone is much more focused.”`,
                },
                user3: {
                    url: "./src/img/avatar-richard.png",
                    name: "Richard Watts",
                    desc: `“Manage has supercharged our team’s workflow. The ability to maintain visibility on larger milestones at all times keeps everyone motivated.”`,
                },
            },
        };
    },
};
</script>
