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
    
</style>