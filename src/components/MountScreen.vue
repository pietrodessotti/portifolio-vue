<template>
    <!-- responsável por montar a tela -->
    <div>
        <Header />
        <AboutMe />
        <SoftSkills />
        <HardSkills />
        <Projects />
        <Footer />
    </div>
</template>
<script>
import Header from "./Header/Header.vue";
import AboutMe from "./AboutMe/AboutMe.vue";
import Footer from "./Footer/Footer.vue";
import SoftSkills from "./SoftSkills/SoftSkills.vue";
import HardSkills from "./HardSkills/HardSkills.vue";
import Projects from "./Projects/Projects.vue";

export default {
    name: "MountScreen",
    components: {
        Header,
        AboutMe,
        Footer,
        SoftSkills,
        HardSkills,
        Projects,
    },
};
</script>
