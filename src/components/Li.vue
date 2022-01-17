<template>
    <a :href="menuObject.link">{{menuObject.text}}</a>
</template>

<script>
export default {
    name: 'Li',
    props: {
        menuObject: Object
    }
}
</script>

<style scoped lang="scss">
a {
    padding: 5px;
    margin: 10px;
}
</style>