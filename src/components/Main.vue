<template>
    <main>
        <!-- section 1 -->
        <section class="container features">
            <div class="text">
                <h2>We are here to make you <span class="green-text">Website</span> look more <span class="green-text">Elegant</span> and stylish!</h2>
                <div class="separator">
                    <div class="first-sep"></div>
                    <div class="second-sep"></div>
                </div>
                <button class="btn-primary">VIEW ALL</button>
            </div>

            <div class="cards">
                <Card v-for="(card, index) in cardArray" :key="index" :cardObj="card" />
            </div>
        </section>
        <!-- section 2 -->

        <!-- section 3 -->

        <!-- section 4 -->

        <!-- section 5 -->

        <!-- section 6 -->

        <!-- section 7 -->

        <!-- section 8 -->
    </main>
</template>

<script>
import Card from './Card.vue';

export default {
    name: 'Main',
    components: {
        Card,
    },
    data: function() {
        return {
            cardArray: [
                {
                    icon: 'fas fa-tachometer-alt',
                    title: 'Speed Optimization',
                    paragraph: 'Far far away, behind the word mountains far from the countries Vokalia Separated...'
                },
                {
                    icon: 'fas fa-cloud',
                    title: 'Cloud Solutions',
                    paragraph: 'Far far away, behind the word mountains far from the countries Vokalia Separated...'
                },
                {
                    icon: 'fas fa-tablet-alt',
                    title: 'Website Design',
                    paragraph: 'Far far away, behind the word mountains far from the countries Vokalia Separated...'
                },
                {
                    icon: 'fas fa-stopwatch',
                    title: 'Online Marketing',
                    paragraph: 'Far far away, behind the word mountains far from the countries Vokalia Separated...'
                }
            ]
        }
    }
}
</script>

<style scoped lang="scss">
// section 1
.features {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 250px 0;
    .text {
        width: 40%;
        h2 {
            font-size: 50px;
        }
        .separator {
            margin: 50px 0;
        }
    }
    .cards {
        display: flex;
        flex-wrap: wrap;
        width: 60%;
    }
}
// section 3
// section 4
// section 5
// section 6
// section 7
// section 8
</style>