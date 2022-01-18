<template>
    <div class="card">
        <i :class="cardObj.icon"></i>
        <h3>{{cardObj.title}}</h3>
        <p>{{cardObj.paragraph}}</p>
    </div>
</template>

<script>
export default {
    name: 'Card',
    props: {
        cardObj: Object
    }
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

.card {
    width: calc((100% / 2) - 40px);
    margin: 40px 20px;
    border-radius: 20px;
    padding: 60px;
    box-shadow: #DEDEDE 0px 0px 30px 5px;
    i {
        font-size: 50px;
        color: $brand_green;
        margin-bottom: 30px;
    }
    h3 {
        font-size: 30px;
        margin-bottom: 20px;
    }
    p {
        color: #AAAAAA;
    }
}
.card:hover {
    background-image: linear-gradient(60deg, #05d9a4, #98e161);
    i, h3, p {
        color: white;
    }
}
</style>