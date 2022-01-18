<template>
    <main>
        <!-- section 1 -->
        <section class="standard-section container flex-centered">
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
        <section class="standard-section bg-grey flex-centered">
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
        <section class="container standard-section">
            <div class="project-intro">
                <div class="project-text">
                    <div class="separator">
                        <div class="first-sep"></div>
                        <div class="second-sep"></div>
                    </div>
                    <h2 class="projects-title">Our recent <span class="green-text">web designs</span> &amp; some examples of past <span class="green-text">projects</span></h2>
                    <div class="separator">
                        <div class="first-sep"></div>
                        <div class="second-sep"></div>
                    </div>
                </div>
                <p>Far far away, beyond the word mountains, far from the world of Vokalia and Consonantia, there live the blind texts. Separated they live in the bookmarksgrove right at the coast of the Semantics, a large language ocean. separeted they live in bookmarksgrove. Far far away, beyond the word mountains, far from the world of Vokalia and Consonantia, there live the blind texts. Separated they live in the bookmarksgrove right at the coast of the Semantics, a large language ocean. separeted they live in bookmarksgrove</p>
            </div>
            
            <div class="projects">
                <div class="single-project">
                    <img src="../assets/img/ina-soulis-227104-unsplash-1024x1024.jpg" alt="">
                    <div class="overlay">
                        <h4>A famous ferris wheel</h4>
                        <span>Marketing</span>
                    </div>
                </div>

                <div class="single-project">
                    <img src="../assets/img/sunisa-misa-531163-unsplash-1024x1024.jpg" alt="">
                    <div class="overlay">
                        <h4>A famous ferris wheel</h4>
                        <span>Marketing</span>
                    </div>
                </div>

                <div class="single-project">
                    <img src="../assets/img/355H-1024x1024.jpg" alt="">
                    <div class="overlay">
                        <h4>A famous ferris wheel</h4>
                        <span>Marketing</span>
                    </div>
                </div>

                <div class="single-project">
                    <img src="../assets/img/photo-1448932252197-d19750584e56-1024x1024.jpg" alt="">
                    <div class="overlay">
                        <h4>A famous ferris wheel</h4>
                        <span>Marketing</span>
                    </div>
                </div>

                <div class="single-project">
                    <img src="../assets/img/business-competition-PB366D8-1024x1024.jpg" alt="">
                    <div class="overlay">
                        <h4>A famous ferris wheel</h4>
                        <span>Marketing</span>
                    </div>
                </div>

                <div class="single-project">
                    <img src="../assets/img/cozy-sofa-in-living-room-PQR5AB9-1024x1024.jpg" alt="">
                    <div class="overlay">
                        <h4>A famous ferris wheel</h4>
                        <span>Marketing</span>
                    </div>
                </div>

                <div class="single-project">
                    <img src="../assets/img/aa9a4539-PQGJ7HU-1024x1024.jpg" alt="">
                    <div class="overlay">
                        <h4>A famous ferris wheel</h4>
                        <span>Marketing</span>
                    </div>
                </div>

                <div class="single-project">
                    <img src="../assets/img/cody-davis-253928-unsplash-1024x1024.jpg" alt="">
                    <div class="overlay">
                        <h4>A famous ferris wheel</h4>
                        <span>Marketing</span>
                    </div>
                </div>
            </div>        
        </section>
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

.bg-grey {
    background-color: #F5F5F5;
}
.standard-section {
    padding: 200px 0;
    .text {
        width: 35%;
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
.flex-centered {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.project-intro {
    display: flex;
    justify-content: space-between;
    width: 100%;
    margin-bottom: 50px;
    p {
        align-self: flex-end;
        width: 60%

    }
    .project-text {
        width: 30%;
    }
}
.projects {
    display: flex;
    flex-wrap: wrap;
    .single-project {
        position: relative;
        margin: 0 3px;
        margin-bottom: 3px;
        width: calc((100% / 4) - 6px);
        .overlay {
            visibility: hidden;
            width: 100%;
            height: 100%;
            position: absolute;
            top: 0;
            left: 0;
            background-image: linear-gradient(45deg, rgb(152, 225, 97, 0.9), rgb(5, 217, 164, 0.9));
            z-index: 1;
            color: white;
            font-size: 25px;
            display: flex;
            flex-direction: column;
            justify-content: flex-end;
            align-items: center;
            padding: 50px 0;
        }
    }
    .single-project:hover .overlay {
        visibility: visible;
    }
}
</style>