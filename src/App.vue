<script>
    import HeaderComp from './components/HeaderComp.vue';
    import FooterComp from './components/FooterComp.vue';
    import MainComp from './components/MainComp.vue';

    export default {
        components: {
            HeaderComp,
            MainComp,
            FooterComp
        },
        data () {
            return {

            }
        }
    }
</script>

<template>
    <HeaderComp />
    <MainComp />
    <FooterComp />
</template>

<style lang="scss" scoped>
@use './style/main.scss';
</style>
