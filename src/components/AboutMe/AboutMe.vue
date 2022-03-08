<template>
    <section id="about">
        <div class="aboutSection">
            <div class="info">
                <p>Pietro Dessotti</p>
                <h1>Desenvolvedor Front-end</h1>
                <p>
                    Sou Bacharel em Ciência da Computação e Desenvolvedor
                    Front-end a 8 meses. Trabalho em projetos robustos com
                    códigos padronizados fazendo Code-review, Conventional
                    commits, JSDoc, Eslint, Prettier e Husky. Sempre atuando com
                    boas práticas de programação e também utilizando
                    metodologias ágeis como Scrum e Kanban.
                </p>
                <p>
                    Possuo experiência em React, Redux-saga, Next.js,
                    Typescript, versionamento de código e bibliotecas como
                    Styled Components e Chart.js, em meu tempo livre estou
                    estudando Vue.js.
                </p>
            </div>
            <div class="imagePerfil">
                <img :src="imagePerfil" alt="" />
            </div>
        </div>

        <!-- <div class="aboutWave">
            <img :src="waveSection" alt="" />
        </div> -->
    </section>
</template>

<script>
export default {
    name: "AboutMe",
    data() {
        return {
            imagePerfil: "/images/undraw_programming.svg",
            waveSection: "/images/wave.svg",
        };
    },
};
</script>

<style scoped>
@import "styles.scss";
</style>
