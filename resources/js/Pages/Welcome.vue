<template>
    <Navbar />
    <Header />

    <div class="bg-gray-100 h-screen"></div>
</template>

<script>
    import Navbar from '../Components/Navbar'
    import Header from '../Components/Header'

    export default {
        components: {
            Navbar,
            Header
        },
        props: {}
    }
</script>

<style scoped>

</style>
