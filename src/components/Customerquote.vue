<template>
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
</template>

<script>
export default {
    name: 'Customerquote',
}
</script>

<style scoped lang="scss">
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
</style>