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
        <section class="mission bg-grey">
            <div class="banner">
                <div class="back-img">
                    <img class="lower" src="../assets/img/busy-architect-PYVKWM4-1024x872.jpg" alt="">
                    <div class="overlay"></div>
                </div>
                <img class="upper" src="../assets/img/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" alt="">
            </div>
            <div class="container text">
                <h2>Learn more about our <span class="green-text">mission</span></h2>
                <div class="separator">
                    <div class="first-sep"></div>
                    <div class="second-sep"></div>
                </div>
                <button class="btn-primary">READ MORE</button>
            </div>
        </section>
        <!-- section 3 -->

        <!-- section 4 -->

        <!-- section 5 -->

        <!-- section 6 -->

        <!-- section 7 -->
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
// common
.bg-grey {
    background-color: #F5F5F5;
}
section {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 200px 0;
    .text {
        width: 35%;
        h2 {
            font-size: 55px;
        }
        .separator {
            margin: 50px 0;
        }
    }
    .cards {
        display: flex;
        flex-wrap: wrap;
        width: 65%;
    }
    .banner {
        position: relative;
        width: 50%;
        background-repeat: no-repeat;
        background-size: 80%;
        background-position: 0% 80%;
        .upper {
            position: absolute;
            width: 80%;
            top: 0;
            left: 20%;
            z-index: 3;
            border-radius: 20px;
            box-shadow: #dedede 20px 20px 15px 10px;
        }
        .back-img {
            position: relative;
            top: -100px;
            left: -25px;
            width: 80%;
            border-radius: 20px;
            overflow: hidden;
        }
        .overlay {
            width: 100%;
            height: 100%;
            position: absolute;
            top: 0;
            left: 0;
            background-image: linear-gradient(45deg, rgb(152, 225, 97, 0.7), rgb(5, 217, 164, 0.7));
            z-index: 1;
        }
    }
}
</style>