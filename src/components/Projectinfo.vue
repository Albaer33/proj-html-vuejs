<template>
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
</template>

<script>
export default {
    name: 'Projectinfo',
}
</script>

<style scoped lang="scss">
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
</style>