<template>
    <div>
        <h2>Welcome to the Zerkblatt Post</h2>
        <p>This is your guide to all things on planet Zerkblatt</p>
        <p @click="$router.push({path:'/'})">Back home</p>
        <p @click="$router.push({path:'/subscribers/mr/bork/borkington'})">Mr. Borkington</p>
    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>