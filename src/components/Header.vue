<template>
    <header>
        <!-- contact header part -->
        <div class="contact-header">
            <div class="container">
                <div class="phone">
                    <i class="fas fa-phone"></i>
                    <span>(001) 88451234</span>
                    <span>8845455438</span>
                </div>
                <div class="social">
                    <i class="fab fa-facebook-f"></i>
                    <i class="fab fa-twitter"></i>
                    <i class="fab fa-pinterest"></i>
                </div>
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
    background-color: $brand_darkgrey;
    color: white;
}
</style>
