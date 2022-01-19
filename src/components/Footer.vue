<template>
    <footer>
        <div class="upper-footer container">

            <div class="element">
                <img class="logo" src="../assets/img/cropped-Group-39-2x.png" alt="">
                <p>While the lovely valley teems with the vapor around me, and the meridian sun strikes the upper surface of the impenatrable foliage of my trees. While the lovely valley teems with the vapor around me</p>
            </div>

            <div class="element">
                <h3>Quick links</h3>
                <div class="separator">
                    <div class="first-sep"></div>
                    <div class="second-sep"></div>
                </div>
                <div class="menulink">
                    <ul>
                        <li v-for="(item, index) in footerMenu" :key="index"><a :href="item.link">{{item.text}}</a></li>
                    </ul>
                </div>
            </div>

            <div class="element">
                <h3>Contact</h3>
                <div class="separator">
                    <div class="first-sep"></div>
                    <div class="second-sep"></div>
                </div>
                <div class="contact">
                    <ul>
                        <li v-for="(item, index) in contact" :key="index">{{item}}</li>
                    </ul>
                </div>
            </div>

            <div class="element">
                <h3>Location on map</h3>
                <div class="separator">
                    <div class="first-sep"></div>
                    <div class="second-sep"></div>
                </div>
                <img src="../assets/img/map.png" alt="">
            </div>

        </div>

        <div class="lower-footer">
            <div class="flex container">
                <span><i class="fas fa-copyright"></i>2020 PHLOX BUSINESS THEME.</span>
                <ul class="list">
                    <li><i class="fab fa-facebook-f"></i></li>
                    <li><i class="fab fa-twitter"></i></li>
                    <li><i class="fab fa-pinterest"></i></li>
                    <li><i class="fas fa-arrow-up"></i></li>
                    <li><i class="far fa-comment"></i></li>
                </ul>
            </div>
        </div>
    </footer>
</template>

<script>

export default {
    name: 'Footer',
      data: function() {
    return {
        footerMenu: [
            {
                text: 'Careers',
                link: '#'
            },
            {
                text: 'News',
                link: '#'
            },
            {
                text: 'Terms of use',
                link: '#'
            },
            {
                text: 'Privacy project',
                link: '#'
            },
            {
                text: 'About',
                link: '#'
            },
            {
                text: 'Contact',
                link: '#'
            },
        ],
        contact: [
            'Patricia C. Amedee 4401 Waldeck Street Grapevine Nashville, TX 76051',
            'info@yourdomain.com',
            '+99 (0) 101 0000 888',
        ]
    }
  }
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';
.upper-footer {
    display: flex;
    padding: 100px 0;
    .element {
        width: calc((100% / 4) - 50px);
        margin: 0 25px;
        .logo {
            width: 60%;
        }
        .separator {
            margin: 10px 0;
        }
        li {
            color: $brand_grey;
            padding: 3px 0;
            a {
                color: inherit;
            }
        }
    }
}
.lower-footer {
    height: 120px;
    background-image: linear-gradient(90deg, #3D3D3D, #333333, black);
    .flex {
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: space-between;
        color: $brand_grey;
        .list {
            display: flex;
            align-items: center;
            li {
                margin: 0 8px;
            }
            .fa-arrow-up {
                font-size: 20px;
                color: black;
                padding: 10px;
                background-color: white;
                border-radius: 30px;
            }
            .fa-comment {
                font-size: 20px;
                color: white;
                padding: 20px;
                border-radius: 30px;
                background-color: $brand_blue;
            }
        }
    }
}
</style>
