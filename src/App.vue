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
</template>

<style lag="scss" scoped  >
.gradientBackground{
    background: rgb(1,1,47);
    background: -moz-linear-gradient(0deg, rgba(1,1,47,1) 0%, rgba(11,25,83,1) 60%);
    background: -webkit-linear-gradient(0deg, rgba(1,1,47,1) 0%, rgba(11,25,83,1) 60%);
    background: linear-gradient(0deg, rgba(1,1,47,1) 0%, rgba(11,25,83,1) 60%);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#01012f",endColorstr="#0b1953",GradientType=1);

}
</style>
