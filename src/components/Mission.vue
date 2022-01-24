<template>
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
</template>

<script>
export default {
    name: 'Mission',
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

.standard-section {
    .text {
        width: 35%;
        .separator {
            margin: 50px 0;
        }
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