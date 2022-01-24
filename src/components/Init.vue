<template>
    <section class="section200 bg-grey">
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
</template>

<script>
export default {
    name: 'Init',
    props: {
        menuObject: Object
    }
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';
.initialize {
    display: flex;
    flex-wrap: wrap;
    text-align: center;
    justify-content: space-between;
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
        width: calc(100% / 6);
        padding: 0 50px;
        margin-top: 100px;
    }
}
</style>