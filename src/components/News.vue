<template>
    <section class="section200 bg-grey">
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
</template>

<script>
export default {
    name: 'News',
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';
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
</style>