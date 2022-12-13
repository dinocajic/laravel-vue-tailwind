<template>
    <h1 class="p-4">Welcome Page from Vue</h1>
    <div class="p-4">
        <a href="/">Home</a> | <a href="/about">About</a>
    </div>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style scoped>
    h1, div {
        background-color: cornflowerblue;
        color: white;
    }
</style>
