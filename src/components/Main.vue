<template>
    <main>
        <!-- section 1 -->
        <Offer/>
        <!-- section 2 -->
        <Mission/>
        <!-- section 3 -->
        <Projects/>
        <!-- section 4 -->
        <Projectinfo/>
        <!-- section 5 -->
        <Subscription/>
        <!-- section 6 -->
        <Customerquote/>
        <!-- section 7 -->
        <News/>
        <!-- section 8 -->
        <Init/>
    </main>
</template>

<script>
import Offer from './Offer.vue';
import Mission from './Mission.vue';
import Projects from './Projects.vue';
import Projectinfo from './Projectinfo.vue';
import Subscription from './Subscription.vue';
import Customerquote from './Customerquote.vue';
import News from './News.vue';
import Init from './Init.vue';


export default {
    name: 'Main',
    components: {
        Offer,
        Mission,
        Projects,
        Projectinfo,
        Subscription,
        Customerquote,
        News,
        Init,
    }
}
</script>

<style scoped lang="scss">
</style>