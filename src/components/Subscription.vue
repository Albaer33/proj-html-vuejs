<template>
    <section class="bg-grey section200">
        <div class="container flex-centered">
            <div class="support">
                <h2>With <span class="green-text">live chat 24/7</span> support</h2>
                <div class="separator">
                    <div class="first-sep"></div>
                    <div class="second-sep"></div>
                </div>
                <p>Far far away, beyond the word mountains, far from the world of Vokalia and Consonantia, there live the blind texts. Separated they live in the bookmarksgrove right at the coast of the Semantics, a large language ocean. separeted they live in bookmarksgrove. Far far away, beyond the word mountains, far from the world of Vokalia and Consonantia, there live the blind texts.</p>
            </div>

            <div class="promotions">
                <div class="single-promotion">
                    <div class="small-band"></div>
                    <h4>DESIGNING</h4>
                    <span>All designs</span>
                    <div class="wide-band">
                        <div>$ <span>13</span>/design</div>
                    </div>
                    <ul>
                        <li><i class="fas fa-check"></i> Creative design enabled</li>
                        <li><i class="fas fa-check"></i> Vibrant color usage</li>
                        <li><i class="fas fa-check"></i> Eye catching design</li>
                        <li><i class="fas fa-check"></i> Extreme typography</li>
                        <li><i class="fas fa-check"></i> Exeptional design</li>
                    </ul>
                </div>

                <div class="single-promotion">
                    <div class="small-band notblack"></div>
                    <h4>DEVELOPMENT</h4>
                    <span>WordPress project</span>
                    <div class="wide-band notblack">
                        <div>$ <span>15</span>/project</div>
                    </div>
                    <ul>
                        <li><i class="fas fa-check"></i> Creative design enabled</li>
                        <li><i class="fas fa-check"></i> Vibrant color usage</li>
                        <li><i class="fas fa-check"></i> Eye catching design</li>
                        <li><i class="fas fa-check"></i> Extreme typography</li>
                        <li><i class="fas fa-check"></i> Exeptional design</li>
                    </ul>
                </div>

                <div class="single-promotion">
                    <div class="small-band"></div>
                    <h4>SEO</h4>
                    <span>Web Product</span>
                    <div class="wide-band">
                        <div>$ <span>10</span>/product</div>
                    </div>
                    <ul>
                        <li><i class="fas fa-check"></i> Creative design enabled</li>
                        <li><i class="fas fa-check"></i> Vibrant color usage</li>
                        <li><i class="fas fa-check"></i> Eye catching design</li>
                        <li><i class="fas fa-check"></i> Extreme typography</li>
                        <li><i class="fas fa-check"></i> Exeptional design</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Subscription',
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

.support {
    width: 35%;
}
.promotions {
    width: 65%;
    display: flex;
    justify-content: center;
    align-items: center;
    .single-promotion {
        width: calc((100% / 3) - 40px);
        margin: 0 20px;
        padding-bottom: 20px;
        text-align: center;
        border-radius: 20px;
        overflow: hidden;
        box-shadow: #c7c7c7 0px 0px 30px 5px;
        li {
            padding: 20px 0;
        }
        h4 {
            font-size: 26px;
        }
        span {
            color: $brand_grey;
        }
        .small-band {
            height: 20px;
            margin-bottom: 20px;
            background-image: linear-gradient(90deg, #3D3D3D, #333333, black);;
        }
        .wide-band {
            height: 100px;
            line-height: 100px;
            margin: 20px 0;
            background-image: linear-gradient(90deg, #3D3D3D, #333333, black);
            color: white;
            span {
                color: inherit;
                font-size: 40px;
            }
        }
        .notblack {
            background-image: linear-gradient(270deg, #05d9a4, #98e161);;
        }
    }
}
</style>