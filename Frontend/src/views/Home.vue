<template>
    <main>
        <Nav />
        <HomePage />
        <HomeLayout>
        </HomeLayout>
    </main>
</template>

<script>
import HomeLayout from '@/components/HomeLayout/HomeLayout.vue';
import Nav from '@/components/Nav.vue';
import HomePage from '@/components/Home/HomePage.vue';
    export default {
        components: {
            HomeLayout,
            Nav,
            HomePage
        }
    }
</script>

<style lang="scss" scoped>

</style>