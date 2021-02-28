<template>
    <NavigationBar />
    <AboutMe />
    <SkillFramework />
    <RecentFramework />
    <Footer />
</template>

<script>
import AboutMe from './components/AboutMe.vue'
import SkillFramework from './components/SkillFramework.vue'
import RecentFramework from './components/RecentWork.vue'
import Footer from './components/Footer.vue'
import NavigationBar from './components/NavigationBar.vue'


export default {
    components: {
        AboutMe,
        SkillFramework,
        RecentFramework,
        Footer,
        NavigationBar
    }
}
</script>