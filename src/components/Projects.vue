<template>
    <section class="container section200">
        <div class="project-intro">
            <div class="project-text">
                <div class="separator">
                    <div class="first-sep"></div>
                    <div class="second-sep"></div>
                </div>
                <h2 class="projects-title">Our recent <span class="green-text">web designs</span> &amp; some examples of past <span class="green-text">projects</span></h2>
                <div class="separator">
                    <div class="first-sep"></div>
                    <div class="second-sep"></div>
                </div>
            </div>
            <p>Far far away, beyond the word mountains, far from the world of Vokalia and Consonantia, there live the blind texts. Separated they live in the bookmarksgrove right at the coast of the Semantics, a large language ocean. separeted they live in bookmarksgrove. Far far away, beyond the word mountains, far from the world of Vokalia and Consonantia, there live the blind texts. Separated they live in the bookmarksgrove right at the coast of the Semantics, a large language ocean. separeted they live in bookmarksgrove</p>
        </div>
        
        <div class="projects">
            <div class="single-project">
                <img src="../assets/img/ina-soulis-227104-unsplash-1024x1024.jpg" alt="">
                <div class="overlay">
                    <h4>A famous ferris wheel</h4>
                    <span>Marketing</span>
                </div>
            </div>

            <div class="single-project">
                <img src="../assets/img/sunisa-misa-531163-unsplash-1024x1024.jpg" alt="">
                <div class="overlay">
                    <h4>A famous ferris wheel</h4>
                    <span>Marketing</span>
                </div>
            </div>

            <div class="single-project">
                <img src="../assets/img/355H-1024x1024.jpg" alt="">
                <div class="overlay">
                    <h4>A famous ferris wheel</h4>
                    <span>Marketing</span>
                </div>
            </div>

            <div class="single-project">
                <img src="../assets/img/photo-1448932252197-d19750584e56-1024x1024.jpg" alt="">
                <div class="overlay">
                    <h4>A famous ferris wheel</h4>
                    <span>Marketing</span>
                </div>
            </div>

            <div class="single-project">
                <img src="../assets/img/business-competition-PB366D8-1024x1024.jpg" alt="">
                <div class="overlay">
                    <h4>A famous ferris wheel</h4>
                    <span>Marketing</span>
                </div>
            </div>

            <div class="single-project">
                <img src="../assets/img/cozy-sofa-in-living-room-PQR5AB9-1024x1024.jpg" alt="">
                <div class="overlay">
                    <h4>A famous ferris wheel</h4>
                    <span>Marketing</span>
                </div>
            </div>

            <div class="single-project">
                <img src="../assets/img/aa9a4539-PQGJ7HU-1024x1024.jpg" alt="">
                <div class="overlay">
                    <h4>A famous ferris wheel</h4>
                    <span>Marketing</span>
                </div>
            </div>

            <div class="single-project">
                <img src="../assets/img/cody-davis-253928-unsplash-1024x1024.jpg" alt="">
                <div class="overlay">
                    <h4>A famous ferris wheel</h4>
                    <span>Marketing</span>
                </div>
            </div>
        </div>
        <button class="btn-primary centered">READ MORE</button>     
    </section>
</template>

<script>
export default {
    name: 'Projects',
}
</script>

<style scoped lang="scss">
.project-intro {
    display: flex;
    justify-content: space-between;
    width: 100%;
    margin-bottom: 50px;
    p {
        align-self: flex-end;
        width: 60%

    }
    .project-text {
        width: 30%;
    }
}
.projects {
    display: flex;
    flex-wrap: wrap;
    .single-project {
        position: relative;
        margin: 0 3px;
        margin-bottom: 3px;
        width: calc((100% / 4) - 6px);
        .overlay {
            visibility: hidden;
            width: 100%;
            height: 100%;
            position: absolute;
            top: 0;
            left: 0;
            background-image: linear-gradient(45deg, rgb(152, 225, 97, 0.9), rgb(5, 217, 164, 0.9));
            z-index: 1;
            color: white;
            font-size: 25px;
            display: flex;
            flex-direction: column;
            justify-content: flex-end;
            align-items: center;
            padding: 50px 0;
        }
    }
    .single-project:hover .overlay {
        visibility: visible;
    }
}
.centered {
    position: absolute;
    transform: translate(-50%);
    left: 50%;
    margin: 60px 0;
}
</style>