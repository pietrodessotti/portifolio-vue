<template>
    <section id="projects">
        <p>Meus Projetos</p>

        <div class="cardsProject">
            <div class="cardProject">
                <div class="starProject">
                    <img :src="cardStar" alt="" />
                </div>
                <h2>Clone netflix</h2>
                <a
                    href="https://ecstatic-panini-b088bb.netlify.app/"
                    target="_blank"
                    ><img :src="project_netflix" alt="" />
                </a>
            </div>
            <div class="cardProject">
                <div class="starProject">
                    <img :src="cardStar" alt="" />
                </div>
                <h2>Página de Captura</h2>
                <a
                    href="https://elated-pasteur-66e249.netlify.app/"
                    target="_blank"
                    ><img :src="project_workshop" alt="" />
                </a>
            </div>
            <div class="cardProject">
                <div class="starProject">
                    <img :src="cardStar" alt="" />
                </div>
                <h2>Churrascômetro</h2>
                <a
                    href="https://gallant-kalam-1522a2.netlify.app/"
                    target="_blank"
                    ><img :src="project_churrascometro" alt="" />
                </a>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Projects",
    data() {
        return {
            cardStar: "/images/star_outline_black_24dp.svg",
            project_churrascometro: "/images/project_churrascometro.png",
            project_workshop: "/images/project_workshop.png",
            project_netflix: "/images/project_netflix.jpg",
        };
    },
};
</script>

<style scoped>
@import "styles.scss";
</style>
