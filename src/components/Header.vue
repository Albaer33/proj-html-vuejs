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

        <!-- main header part -->
        <div class="main-header">
            <div class="container">
                <div class="logo">
                    <img src="../assets/img/cropped-Group-39-2x.png" alt="brand logo">
                </div>
                <ul class="menu">
                    <li><a href="#">HOME</a></li>
                    <li><a href="#">ABOUT</a></li>
                </ul>
                <div class="option">
                    <button>PURCHASE</button>
                    <i class="fas fa-search"></i>
                </div>
            </div>
        </div>

        <div class="banner-header"></div>
    </header>
</template>

<script>
export default {
    name: "Header",
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

// contact header part
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
                margin: 0 8px;
            }
        }
    }
}

// main header part
.main-header {
    width: 100%;
    height: 100px;
    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 100%;
        .menu {
            display: flex;
            justify-content: center;
            li {
                margin: 5px;
                a {
                    padding: 10px;
                }
            }
        }
        .option {
            button {
                background-image: linear-gradient(30deg, #98e161, #05d9a4);
                border: none;
                border-radius: 50px;
                color: white;
                padding: 15px 30px;
                cursor: pointer;
            }
            i {
                color: $brand_green;
                margin-left: 10px;
            }
        }
    }
}
</style>
