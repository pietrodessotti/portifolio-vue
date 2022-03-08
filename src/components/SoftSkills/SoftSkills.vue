<template>
    <section id="softSkills">
        <p>Soft Skills</p>

        <div class="cards">
            <div class="movieRow">
                <div class="movieRow--left" onClick="{handleLeftArrow}">
                    <img :src="navigation_before" alt="" />
                </div>
                <div class="movieRow--right" onClick="{handleRightArrow}">
                    <img :src="navigation_next" alt="" />
                </div>
            </div>
            <div class="card">
                <div class="star">
                    <img :src="cardStar" alt="" />
                </div>
                <h2>Proativo</h2>
                <p>
                    Ser proativo não só me ajuda a alcançar mais rápido mais
                    objetivos como me mostra que eu posso ir sempre além do que
                    eu mesmo esperaria de mim.
                </p>
            </div>
            <div class="card">
                <div class="star">
                    <img :src="cardStar" alt="" />
                </div>
                <h2>Organizado</h2>
                <p>
                    A organização é peça chave e fundamental para um bom
                    desempenho na vida pessoal e no trabalho, por isso me
                    esforço para estar sempre aperfeiçoando essa habilidade, ser
                    organizado te faz ganhar tempo.
                </p>
            </div>
            <div class="card">
                <div class="star">
                    <img :src="cardStar" alt="" />
                </div>
                <h2>Gerenciar tempo</h2>
                <p>
                    Dentre as soft skills que evolui no ano de 2021 essa com
                    certeza me deu maior destaque, ao aprender a gerenciar meu
                    tempo eu percebi que posso fazer muito mais durante meu dia.
                </p>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "SoftSkills",
    data() {
        return {
            cardStar: "/images/star_outline_black_24dp.svg",
            navigation_next: "/images/navigation-next.svg",
            navigation_before: "/images/navigation-before.svg",
        };
    },
};
</script>
<style scoped>
@import "styles.scss";
</style>
