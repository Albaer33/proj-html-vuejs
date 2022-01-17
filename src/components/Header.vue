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

    </header>
</template>

<script>
export default {
    name: "Header",
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

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
                margin: 0 5px;
            }
        }
    }
}
</style>
