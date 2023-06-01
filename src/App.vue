<script >
import pageHeader from './components/pageHeader.vue'
import jumbotron from './components/jumbotron.vue'
import pageMain from './components/pageMain.vue'
import pageFooter from './components/pageFooter.vue'
export default {
    components: {
        pageHeader,
        jumbotron,
        pageMain,
        pageFooter
    }
}
</script>

<template>
    <div class="gradientBackground">
        <pageHeader/>
        <jumbotron/>
    </div>
    <pageMain/>
    <pageFooter/>
</template>

<style lag="scss" scoped  >

</style>
