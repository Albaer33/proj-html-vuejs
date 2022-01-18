<template>
    <header>
        <!-- contact header part -->
        <div class="contact-header">
            <div class="container">
                <ul class="list">
                    <li><i class="fas fa-phone"></i></li>
                    <li>(001) 88451234</li>
                    <li>8845455438</li>
                </ul>
                <ul class="list">
                    <li><i class="fab fa-facebook-f"></i></li>
                    <li><i class="fab fa-twitter"></i></li>
                    <li><i class="fab fa-pinterest"></i></li>
                </ul>
            </div>
        </div>

        <!-- main header part -->
        <div class="main-header">
            <div class="container">
                <div class="logo">
                    <img src="../assets/img/cropped-Group-39-2x.png" alt="brand logo">
                </div>
                <div class="menu">
                    <Li v-for="(element, index) in headerMenu" :key="index" :menuObject='element' />
                </div>
                <div class="option">
                    <button>PURCHASE</button>
                    <i class="fas fa-search"></i>
                </div>
            </div>
        </div>

        <!-- header-jumbotron part -->
        <div class="header-jumbotron">
            <div class="container">
                <div class="jumbotron-text">

                    <h4>
                    <span>1 7</span>
                    <span>Y E A R S</span>
                    <span>O F</span>
                    <span>E X P E R I E N C E</span>
                    </h4>

                    <h1>Focus on Your <br><span>Business</span></h1>

                    <div class="separator first-sep"></div>
                    <div class="separator second-sep"></div>

                    <p>Far far away, beyond the word mountains, far from the world of Vokalia and Consonantia, there live the blind texts. Separated they live in the bookmarksgrove right at the coast of the Semantics, a large language ocean. separeted they live in bookmarksgrove</p>
                    <button>READ MORE</button>
                    <div class="social">FACEBOOK - YOUTUBE - INSTAGRAM - TWITTER</div>
                    <div class="slider">
                        <div class="number">1</div>
                        <div class="number active">2</div>
                        <div class="number">3</div>
                    </div>
                </div>
            </div>
            <div class="bg-image"></div>
        </div>
    </header>
</template>

<script>
import Li from './Li.vue';

export default {
    name: "Header",
    components: {
        Li,
    },
    data: function () {
        return {
            headerMenu: [
                {
                    text: 'HOME',
                    link: '#'
                },
                {
                    text: 'ABOUT',
                    link: '#'
                },
                {
                    text: 'SERVICES',
                    link: '#'
                },
                {
                    text: 'SHOWCASE',
                    link: '#'
                },
                {
                    text: 'BLOG',
                    link: '#'
                },
                {
                    text: 'CONTACT',
                    link: '#'
                },
            ]
        }
    }
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

// contact header part
.contact-header {
    height: 40px;
    line-height: 40px;
    background-color: #333333;
    color: white;
    .container {
        display: flex;
        justify-content: space-between;
        .list {
            display: flex;
            li {
                margin: 0 8px;
            }
        }
    }
}

// main header part
.main-header {
    width: 100%;
    height: 100px;
    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 100%;
        .menu {
            display: flex;
            justify-content: center;
        }
        .option {
            button {
                background-image: linear-gradient(90deg, #98e161, #05d9a4);
            }
            button:hover {
                background-image: linear-gradient(90deg, #3D3D3D, #333333, black);
            }
            i {
                color: $brand_green;
                margin-left: 10px;
            }
        }
    }
}

// header-jumbotron part
.header-jumbotron {
    background-color: #F5F5F5;
    padding-top: 150px;
    background-image: url("../assets/img/Group-35-2x.png");
    background-repeat: no-repeat;
    background-position: 180% 50%;
    .container {
        .jumbotron-text {
            position: relative;
            width: 40%;
            h4 span {
                color: $brand_green;
                margin-right: 15px;
            }
            h1 {
                font-size: 65px;
                margin: 30px 0;
                span{
                    color: $brand_green;
                }
            }
            .separator {
                display: inline-block;
                margin: 5px;
                border-radius: 3px;
                background-image: linear-gradient(90deg, #98e161, #05d9a4);
            }
            .first-sep {
                height: 5px;
                width: 10px;
            }
            .second-sep {
                height: 5px;
                width: 50px;
            }
            p {
                color: #AAAAAA;
                padding-top: 40px;
            }
            button {
                background-image: linear-gradient(90deg, #3D3D3D, #333333, black);
                margin: 60px 0;
            }
            .social {
                font-weight: bold;
                padding: 60px 0;
            }
            .slider {
                background-image: linear-gradient(90deg, #424242, #2c2c2c);
                border-radius: 50px;
                padding: 5px;
                display: flex;
                justify-content: space-between;
                align-items: center;
                position: absolute;
                z-index: 2;
                bottom: 45px;
                right: -20px;
                text-align: center;
                .number {
                    padding: 10px 20px;
                    color: white;
                }
                .active {
                    background-image: linear-gradient(90deg, #98e161, #05d9a4);
                    border-radius: 40px;
                }
            }
        }
    }
}
</style>
