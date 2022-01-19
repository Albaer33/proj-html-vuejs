<template>
    <main>
        <!-- section 1 -->
        <section class="standard-section container flex-centered section200">
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
        <section class="standard-section bg-grey flex-centered section200">
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
        <section class="container section200">
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
            <button class="btn-primary centered">READ MORE</button>     
        </section>
        <!-- section 4 -->
        <section class="bg-grey section200">
            <div class="container">
                <div class="back-img-box">
                    <img src="../assets/img/person-with-long-curly-hair-PZ99QM2-2x.jpg" alt="">
                    <div class="overlay">
                        <div class="f70 w100">
                            280
                            <div class="f25">PROJECTS</div>
                        </div>

                        <div class="f40 w50">
                            +3500
                            <div class="f25">USER'S COMMENT</div>
                        </div>

                        <div class="f40 w50">
                            100%
                            <div class="f25">HAPPY CLIENTS</div>
                        </div>

                        <!-- info traslate a destra -->
                        <div class="info">
                            <h2>We <span class="green-text">Love</span> what we do</h2>
                            <div class="separator">
                                <div class="first-sep"></div>
                                <div class="second-sep"></div>
                            </div>
                            <p>Far far away, beyond the word mountains, far from the world of Vokalia and Consonantia, there live the blind texts. Separated they live in the bookmarksgrove right at the coast of the Semantics, a large language ocean. separeted they live in bookmarksgrove. Far far away, beyond the word mountains, far from the world of Vokalia and Consonantia, there live the blind texts.</p>              
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- section 5 -->
        <section class="bg-grey section200">
            <div class="container flex-centered">
                <div class="support">
                    <h2>With <span class="green-text">live chat 24/7</span> support</h2>
                    <div class="separator">
                        <div class="first-sep"></div>
                        <div class="second-sep"></div>
                    </div>
                    <p>Far far away, beyond the word mountains, far from the world of Vokalia and Consonantia, there live the blind texts. Separated they live in the bookmarksgrove right at the coast of the Semantics, a large language ocean. separeted they live in bookmarksgrove. Far far away, beyond the word mountains, far from the world of Vokalia and Consonantia, there live the blind texts.</p>
                </div>

                <div class="promotions">
                    <div class="single-promotion">
                        <div class="small-band"></div>
                        <h4>DESIGNING</h4>
                        <span>All designs</span>
                        <div class="wide-band">
                            <div>$ <span>13</span>/design</div>
                        </div>
                        <ul>
                            <li><i class="fas fa-check"></i> Creative design enabled</li>
                            <li><i class="fas fa-check"></i> Vibrant color usage</li>
                            <li><i class="fas fa-check"></i> Eye catching design</li>
                            <li><i class="fas fa-check"></i> Extreme typography</li>
                            <li><i class="fas fa-check"></i> Exeptional design</li>
                        </ul>
                    </div>

                    <div class="single-promotion">
                        <div class="small-band notblack"></div>
                        <h4>DEVELOPMENT</h4>
                        <span>WordPress project</span>
                        <div class="wide-band notblack">
                            <div>$ <span>15</span>/project</div>
                        </div>
                        <ul>
                            <li><i class="fas fa-check"></i> Creative design enabled</li>
                            <li><i class="fas fa-check"></i> Vibrant color usage</li>
                            <li><i class="fas fa-check"></i> Eye catching design</li>
                            <li><i class="fas fa-check"></i> Extreme typography</li>
                            <li><i class="fas fa-check"></i> Exeptional design</li>
                        </ul>
                    </div>

                    <div class="single-promotion">
                        <div class="small-band"></div>
                        <h4>SEO</h4>
                        <span>Web Product</span>
                        <div class="wide-band">
                            <div>$ <span>10</span>/product</div>
                        </div>
                        <ul>
                            <li><i class="fas fa-check"></i> Creative design enabled</li>
                            <li><i class="fas fa-check"></i> Vibrant color usage</li>
                            <li><i class="fas fa-check"></i> Eye catching design</li>
                            <li><i class="fas fa-check"></i> Extreme typography</li>
                            <li><i class="fas fa-check"></i> Exeptional design</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
        <!-- section 6 -->
        <section class="client-opinion section200">
            <div class="overlay"></div>
            <div class="text">
                <i class="fas fa-quote-left green-text"></i>
                <div class="quote">When it comes to berbequing, there are two main schools of thought for the techniques that you can use. Freshly scrambled eggs with applewood smoked bacon are amazing!</div>
                <div class="img-box">
                    <img src="../assets/img/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" alt="">
                </div>
                <span class="green-text name">LISSA DURBIN</span>
                <span>Client</span>
            </div>
        </section>
        <!-- section 7 -->
        <section class="section200">
            <div class="container news">
                <h2>latest news &amp; our <span class="green-text">Blog</span></h2>
                <div class="separator">
                    <div class="first-sep"></div>
                    <div class="second-sep"></div>
                </div>
                <div class="rotate sx">17 years of experience helping people for best solutions</div>
                <div class="threads">

                    <div class="single-thread">
                        <img src="../assets/img/serious-businesswoman-with-documents-talking-on-P9Q6LX6-1024.jpg" alt="">
                        <div class="title">
                            <span>May 24, 2018 - by Alex</span>
                            <h4>Marketing Ideas</h4>
                        </div>
                    </div>

                    <div class="single-thread">
                        <img src="../assets/img/Businessman-at-the-desk-in-his-office-resting--1024x768.jpg" alt="">
                        <div class="title">
                            <span>May 24, 2018 - by Alex</span>
                            <h4>Rest during working hours</h4>
                        </div>
                    </div>

                    <div class="single-thread">
                        <img src="../assets/img/simple-home-office-with-tree-PBXRXYB-large-1024x768.jpg" alt="">
                        <div class="title">
                            <span>May 24, 2018 - by Alex</span>
                            <h4>Develop your starup idea</h4>
                        </div>
                    </div>

                </div>
                <button class="btn-primary">VIEW ALL POST</button>
            </div>
        </section>
        <!-- section 8 -->
        <section class="section200">
            <div class="container initialize">
                <div class="w2 black">
                    <span class="grey-text">Are you ready?</span>
                    <h3>Start a new Project</h3>
                    <div class="form">
                        <input type="text" placeholder="Enter your email address">
                        <button class="custom-btn">Submit</button>
                    </div>
                </div>
                <div class="w2 colored">
                    <span class="grey-text">What are you waiting for?</span>
                    <h3>Let's talk about work</h3>
                    <button>START NOW</button>
                </div>

                <div class="w6">
                    <img src="../assets/img/client-1-2x.png" alt="">
                </div>

                <div class="w6">
                    <img src="../assets/img/client-3-2x.png" alt="">
                </div>

                <div class="w6">
                    <img src="../assets/img/client-4-2x.png" alt="">
                </div>

                <div class="w6">
                    <img src="../assets/img/client-5-2x.png" alt="">
                </div>

                <div class="w6">
                    <img src="../assets/img/client-7-2x.png" alt="">
                </div>

                <div class="w6">
                    <img src="../assets/img/client-9-2x.png" alt="">
                </div>
            </div>
        </section>
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
@import '../style/variables.scss';
.standard-section {
    .centered {
        position: absolute;
        transform: translate(-50%);
        left: 50%;
        margin: 60px 0;
    }
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
.back-img-box {
    width: 55%;
    position: relative;
    border-radius: 10px;
    z-index: 0;
    .overlay {
        width: 100%;
        height: 100%;
        position: absolute;
        top: 0;
        left: 0;
        background-image: linear-gradient(45deg, rgb(152, 225, 97, 0.7), rgb(5, 217, 164, 0.7));
        z-index: 1;
        color: white;
        font-weight: bold;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
        .f70 {
            font-size: 100px;
        }
        .f40 {
            font-size: 40px;
        }
        .f25 {
            font-size: 25px;
        }
        .w100 {
            padding-top: 50px;
            width: 100%;
            text-align: center;
        }
        .w50 {
            width: 30%;
            text-align: center;
        }
    }
    .info {
        background-color: white;
        box-shadow: #DEDEDE 0px 0px 30px 5px;
        width: 100%;
        height: 100%;
        position: absolute;
        top: 20%;
        left: 85%;
        z-index: 2;
        color: black;
        display: flex;
        flex-direction: column;
        justify-content: center;
        padding-left: 70px;
    }
}
.support {
    width: 35%;
}
.promotions {
    width: 65%;
    display: flex;
    justify-content: center;
    align-items: center;
    .single-promotion {
        width: calc((100% / 3) - 40px);
        margin: 0 20px;
        padding-bottom: 20px;
        text-align: center;
        border-radius: 20px;
        overflow: hidden;
        box-shadow: #c7c7c7 0px 0px 30px 5px;
        li {
            padding: 20px 0;
        }
        h4 {
            font-size: 26px;
        }
        span {
            color: $brand_grey;
        }
        .small-band {
            height: 20px;
            margin-bottom: 20px;
            background-image: linear-gradient(90deg, #3D3D3D, #333333, black);;
        }
        .wide-band {
            height: 100px;
            line-height: 100px;
            margin: 20px 0;
            background-image: linear-gradient(90deg, #3D3D3D, #333333, black);
            color: white;
            span {
                color: inherit;
                font-size: 40px;
            }
        }
        .notblack {
            background-image: linear-gradient(270deg, #05d9a4, #98e161);;
        }
    }
}
.client-opinion {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: white;
    background-image: url('../assets/img/four-businesspeople-in-a-boardroom-with-paperwork-PC4V8H4.jpg');
    position: relative;
    .text {
        text-align: center;
        position: relative;
        z-index: 3;
        i {
        font-size: 60px;
        }
        .quote {
            font-size: 30px;
            padding: 100px 300px;
            font-style: italic;
        }
        .img-box {
            display: inline-block;
            width: 180px;
            height: 180px;
            border-radius: 300px;
            overflow: hidden;
            border: 3px solid white;
        }
        .name {
            display: block;
            padding: 10px 0;
            font-size: 22px;
        }
    }
    .overlay {
        width: 100%;
        height: 100%;
        position: absolute;
        top: 0;
        left: 0;
        background-color: rgb(51, 51, 51, 0.93);
    }
}
.news {
    text-align: center;
    position: relative;
    .sx {
        position: absolute;
        left: -230px;
        bottom: 380px;
    }
    .threads {
        display: flex;
        .single-thread {
            position: relative;
            width: calc((100% / 3) - 20px);
            margin: 0 10px;
            box-shadow: #DEDEDE 0px 0px 30px 5px;
            .title {
                position: absolute;
                width: 70%;
                height: 100px;
                background-color: white;
                border-radius: 10px;
                transform: translate(-50%, -50%);
                bottom: -100px;
                left: 50%;
                box-shadow: #DEDEDE 0px 20px 30px 5px;
                span {
                    color: $brand_grey;
                }
                h4 {
                    font-size: 24px;
                }
            }
        }
    }
    button {
        background-image: linear-gradient(90deg, #3D3D3D, #333333, black);
        margin-top: 150px;
    }
}
.initialize {
    display: flex;
    flex-wrap: wrap;
    text-align: center;
    .black {
        background-image: linear-gradient(90deg, #3D3D3D, #333333, black);
    }
    .colored {
        background-image: linear-gradient(60deg, #05d9a4, #98e161);
    }
    .w2 {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-around;
        width: calc((100% / 2) - 20px);
        margin: 0 10px;
        padding: 80px 0;
        border-radius: 20px;
        h3 {
            font-size: 40px;
            margin-bottom: 80px;
            color: white;
        }
        button {
            background-image: linear-gradient(90deg, #3D3D3D, #333333, black);
        }
        .form {
            background-color: #4d4d4d;
            border-radius: 40px;
            width: 420px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            .custom-btn {
                background-color: #4d4d4d;
                background-image: none;
                color: $brand_grey;
                font-size: 20px;
                font-weight: bold;
            }
            input {
                padding: 20px 100px 20px 20px;
                border: none;
                background-color: #4d4d4d;
                border-radius: 30px;
            }
        }
    }
    .w6 {
        
        align-self: center;
        width: calc((100% / 6) - 180px);
        margin: 100px 90px;
    }
}
</style>