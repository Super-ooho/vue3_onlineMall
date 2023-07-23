<template>
    <div class="container">
        <HomeCategory></HomeCategory>
        <HomeSlider></HomeSlider>
    </div>
    <HomeNew></HomeNew>
    <HomeHot></HomeHot>
    <HomeProduct></HomeProduct>


</template>

<script setup>
    import HomeCategory from './components/HomeCategory.vue'
    import HomeHot from './components/HomeHot.vue'
    import HomeSlider from './components/HomeSlider.vue'
    import HomeNew from './components/HomeNew.vue'
    import HomeProduct from './components/HomeProduct.vue'

</script>

<style lang="scss" scoped>

</style>