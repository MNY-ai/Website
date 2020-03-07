<template>
    <section class="hero-branding bg-cover" :style="bgImg" id="home">
        <div class="container-fluid container-fluid--cp-150">
            <div class="hero-branding">
                <div class="hero-content">
                    <h2 class="h1 hero-content-title">The easy way.</h2>
                    <h6 class="hero-content-subtitle mt-20">Make more money while working fewer hours — from anywhere. Built by CPAs for CPAs, MNY is the easy way to CPA.</h6>
                    <div class="slider-button mt-30">
                        <router-link :to="{ path: 'overview' }" class="ht-btn ht-btn-md">Learn More</router-link>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        data (){
            return {
                bgImg: {
                    backgroundImage: `url(${require('../assets/img/hero/branding/branding3.jpg')})`
                },
            }
        }
    }
</script>

<style lang="scss" scoped>
    @import '../assets/scss/variabls.scss';
    @import '../assets/scss/elements/hero-branding.scss'
</style>
