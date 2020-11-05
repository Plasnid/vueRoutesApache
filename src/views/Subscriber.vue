<template>
    <header>
        <h1>Welcome Subscriber {{$route.params.salut}} {{$route.params.firstName}} {{$route.params.lastName}}</h1>
        <p @click="sendMeHome">Go Back To Home</p>
    </header>
</template>

<script>
export default {
    methods: {
        sendMeHome() {
            console.log("Now I'll click my heels together");
            console.log(this.$route.params.firstName);
            this.$router.push({path:'/'});
        }
    },
}
</script>

<style>

</style>