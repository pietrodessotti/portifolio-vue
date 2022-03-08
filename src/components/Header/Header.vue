<template>
    <div class="headerComponent">
        <div>
            <h1 class="logoHeader">P</h1>

            <div class="loader">
                <div class="circle"></div>
            </div>
        </div>

        <!-- <svg width="100" height="100">
            <circle
                cx="50"
                cy="50"
                r="30"
                stroke="#41B883"
                stroke-width="3"
                fill="transparent"
            />
        </svg> -->
        <div class="titleHeader">
            <h2>{{ title }}</h2>
            <p>{{ caption }}</p>
        </div>

        <!-- <div class="theme">
            <img :src="theme_light" :alt="teste" />
        </div> -->

        <div class="menuHeader">
            <ul>
                <li class="list active">
                    <a href="#">
                        <span class="icon">
                            <img :src="menu.about" alt="" />
                        </span>
                        <span class="text">Sobre mim</span>
                    </a>
                </li>
                <li class="list">
                    <a href="#softSkills">
                        <span class="icon">
                            <img :src="menu.softSkills" alt="" />
                        </span>
                        <span class="text">Soft skills</span></a
                    >
                </li>
                <li class="list">
                    <a href="#hardSkills">
                        <span class="icon">
                            <img :src="menu.hardSkills" alt="" />
                        </span>
                        <span class="text">Hard skills</span></a
                    >
                </li>
                <li class="list">
                    <a href="#projects">
                        <span class="icon">
                            <img :src="menu.projects" alt="" />
                        </span>
                        <span class="text">Projetos</span></a
                    >
                </li>
                <li class="list">
                    <a href="#hardSkills">
                        <span class="icon">
                            <img :src="menu.contact" alt="" />
                        </span>
                        <span class="text">Contato</span></a
                    >
                </li>
                <div class="indicator"></div>
            </ul>
        </div>
    </div>
</template>

<script>
const list = document.querySelectorAll(".list");

export default {
    name: "Header",
    data() {
        return {
            logo: "/images/logo.jpg",
            title: "Pietro Dessotti",
            caption: "Software Engineer",
            imageGif: "../../assets/logo.png",
            // theme_light: "/images/lightbulb_black_24dp.svg",
            theme_light: "/images/tungsten_black_24dp.svg",

            menu: {
                title: "Menu",
                hamburguer: "Criar",
                about: "/images/home-outline.svg",
                softSkills: "/images/sparkles-outline.svg",
                hardSkills: "/images/barbell-outline.svg",
                projects: "/images/ribbon-outline.svg",
                contact: "/images/person-add-outline.svg",
            },
        };
    },
    methods: {
        activeLink() {
            list.forEach((item) => item.classList.remove("active"));
            this.classList.add("active");
        },
    },
};
</script>

<style scoped>
@import "styles.scss";
</style>
