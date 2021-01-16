<template>
    <!-- <section id="home">
        <div class="row">
            <div class="owl-carousel owl-theme home-slider">
                <div class="item item-first">
                    <div class="caption">
                        <div class="container">
                            <div class="row mx-auto">
                                <div class="col-md-6 col-sm-12 mx-auto">
                                    <div class="input-group md-form form-sm form-2 pl-0">
                                        <input class="form-control my-0 py-1 amber-border" type="text" placeholder="Enter Email" aria-label="Search">
                                        <div class="input-group-append">
                                            <span class="input-group-text amber lighten-3" id="basic-text1">Get Started</span>
                                        </div>
                                    </div>
                                    <div class="btn-flex">
                                        <a href="#"><img class="app-store-btn" src="../assets/images/app-store-icon.png" alt="App Store Icon"></a>
                                        <a href="#"><img class="google-play-btn" src="../assets/images/google-play-icon.png" alt="Google Play Icon"></a>
                                    </div>
                                </div>
                                <div class="col-md-6 banner-right text-center">
                                    <img class="img-fluid play-img" src="../assets/landing/img/youtube.svg" alt="">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="item item-second">
                    <div class="caption">
                        <div class="container">
                            <div class="row mx-auto">
                                <div class="col-md-6 col-sm-12 mx-auto">
                                    <div class="input-group md-form form-sm form-2 pl-0">
                                        <input class="form-control my-0 py-1 amber-border" type="text" placeholder="Enter Email" aria-label="Search">
                                        <div class="input-group-append">
                                            <span class="input-group-text amber lighten-3" id="basic-text1">Get Started</span>
                                        </div>
                                    </div>
                                    <div class="btn-flex">
                                        <a href="#"><img class="app-store-btn" src="../assets/images/app-store-icon.png" alt="App Store Icon"></a>
                                        <a href="#"><img class="google-play-btn" src="../assets/images/google-play-icon.png" alt="Google Play Icon"></a>
                                    </div>
                                </div>
                                <div class="col-md-6 banner-right text-center">
                                    <img class="img-fluid play-img" src="../assets/landing/img/youtube.svg" alt="">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="item item-third">
                    <div class="caption">
                        <div class="container">
                            <div class="row mx-auto">
                                <div class="col-md-6 col-sm-12 mx-auto">
                                    <div class="input-group md-form form-sm form-2 pl-0">
                                        <input class="form-control my-0 py-1 amber-border" type="text" placeholder="Enter Email" aria-label="Search">
                                        <div class="input-group-append">
                                            <span class="input-group-text amber lighten-3" id="basic-text1">Get Started</span>
                                        </div>
                                    </div>
                                    <div class="btn-flex">
                                        <a href="#"><img class="app-store-btn" src="../assets/images/app-store-icon.png" alt="App Store Icon"></a>
                                        <a href="#"><img class="google-play-btn" src="../assets/images/google-play-icon.png" alt="Google Play Icon"></a>
                                    </div>
                                </div>
                                <div class="col-md-6 banner-right text-center">
                                    <img class="img-fluid play-img" src="../assets/landing/img/youtube.svg" alt="">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <VueInjectJs src="/lib/owl-carousel/custom.js" />
    </section> -->
    <!-- End banner section -->
    <section id="home" class="parallax-section">
        <div class="overlay"></div>
        <div class="container">
            <div class="row">
                <div class="col-md-6 col-sm-12">
                    <div class="home-text">
                        <div class="input-group md-form form-sm form-2 pl-0">
                            <input class="form-control my-0 py-1 amber-border" type="text" placeholder="Enter Email" aria-label="Search">
                            <div class="input-group-append">
                                <span class="input-group-text amber lighten-3" id="basic-text1">Get Started</span>
                            </div>
                        </div>
                        <div class="btn-flex">
                            <a href="#"><img class="app-store-btn" src="../assets/images/app-store-icon.png" alt="App Store Icon"></a>
                            <a href="#"><img class="google-play-btn" src="../assets/images/google-play-icon.png" alt="Google Play Icon"></a>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 banner-right text-center">
                    <img class="img-fluid play-img" src="../assets/landing/img/youtube.svg" alt="">
                </div>
            </div>
        </div>
        <!-- Video -->
        <video controls autoplay loop muted>
            <source src="../assets/videos/video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <img class="home-to-cinema" src="../assets/images/Group 141.svg">
    </section>
</template>
<script>
// import VueInjectJs from "vue-inject-js"
export default {
    components: {
        // VueInjectJs
    }
}
</script>
<!-- 
<style scoped>
.input-group.md-form.form-sm.form-2 input {
    border: 1px solid #bdbdbd;
    border-top-left-radius: 2rem;
    border-bottom-left-radius: 2rem;
    height: 50px;
    background: rgba(255, 255, 255, 0.3);
    border-color: transparent;
}

.input-group-append span {
    border-top-right-radius: 2rem;
    border-bottom-right-radius: 2rem;
    background: linear-gradient(90deg, #721fa5 0%, #7e166e 100%);
    color: #fff;
    border-color: transparent;
}

::placeholder {
    color: #ffffff;
    opacity: 50%;
}

.btn-flex {
    display: flex;
    justify-content: space-around;
    margin-top: 50px;
}

.container {
    margin-top: 15%;
}
</style> -->
<style scoped>
.home-to-cinema {
    position: absolute;
    width: 534px !important;
    left: 940px;
    top: 644px;
}

@media (max-width: 1440px) {
    .home-to-cinema {
        position: absolute;
        width: 534px !important;
        left: 800px;
        top: 744px;
    }
}

@media (max-width: 1280px) {
    .home-to-cinema {
        position: absolute;
        width: 534px !important;
        left: 700px;
        top: 644px;
    }
}

@media (max-width: 1024px) {
    .home-to-cinema {
        position: absolute;
        width: 534px !important;
        left: 450px;
        top: 1200px;
    }
}

@media (max-width: 768px) {
    .home-to-cinema {
        position: absolute;
        width: 534px !important;
        left: 200px;
        top: 870px;
    }
}

@media (max-width: 500px) {
    .home-to-cinema {
        position: absolute;
        width: 304px !important;
        left: 100px;
        top: 730px;
    }
}

@media (max-width: 384px) {
    .home-to-cinema {
        position: absolute;
        width: 304px !important;
        left: 70px;
        top: 720px;
    }
}

@media (max-width: 375px) {
    .home-to-cinema {
        position: absolute;
        width: 304px !important;
        left: 70px;
        top: 720px;
    }
}

@media (max-width: 360px) {
    .home-to-cinema {
        position: absolute;
        width: 304px !important;
        left: 50px;
        top: 560px;
    }
}

#home {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    height: 100vh;
    position: relative;
    padding-top: 6em;
}

#home h1 {
    color: #ffffff;
    font-size: 6em;
    line-height: 1.2em;
}

#home p {
    color: rgba(250, 250, 250, 0.7);
}

#home .overlay {
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.75);
}

#home video {
    position: fixed;
    top: 50%;
    left: 50%;
    min-width: 100%;
    min-height: 100%;
    width: auto;
    height: auto;
    z-index: -100;
    transform: translateX(-50%) translateY(-50%);
    background-size: cover;
    transition: 1s opacity;
}

.parallax-section {
    background-attachment: fixed !important;
    background-size: cover !important;
}

.section-btn {
    margin: 32px 0 0 0;
    padding: 0;
}

.section-btn a,
.section-btn button {
    line-height: 45px;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
    color: #ffffff;
    font-weight: normal;
}

.section-btn a span,
.section-btn button span {
    position: relative;
    display: inline-block;
    font-size: 18px;
    font-weight: normal;
    letter-spacing: 0.5px;
    padding: 0 25px;
    background: #4dc47d;
    border-radius: 1px;
    -webkit-transition: -webkit-transform 0.3s;
    -moz-transition: -moz-transform 0.3s;
    transition: transform 0.3s;
    -webkit-transform-origin: 50% 0;
    -moz-transform-origin: 50% 0;
    transform-origin: 50% 0;
    -webkit-transform-style: preserve-3d;
    -moz-transform-style: preserve-3d;
    transform-style: preserve-3d;
}


.input-group.md-form.form-sm.form-2 input {
    border: 1px solid #bdbdbd;
    border-top-left-radius: 2rem;
    border-bottom-left-radius: 2rem;
    height: 50px;
    background: rgba(255, 255, 255, 0.3);
    border-color: transparent;
}

.input-group-append span {
    border-top-right-radius: 2rem;
    border-bottom-right-radius: 2rem;
    background: linear-gradient(90deg, #721fa5 0%, #7e166e 100%);
    color: #fff;
    border-color: transparent;
}

.input-group {}

::placeholder {
    color: #ffffff;
    opacity: 50%;
}

img {
    width: 136px !important;
}

.play-img {
    margin: 0 auto;
    text-align: center;
    width: 70px !important;
}

.btn-flex {
    display: flex;
    justify-content: space-around;
    margin-top: 50px;
}

@media (max-width: 992px) {
    #home h1 {
        font-size: 4em;
        line-height: normal;
    }
}

@media (max-width: 980px) {
    #home {
        padding-top: 0em;
    }
}

@media (max-width: 770px) {
    #home h1 {
        font-size: 3.5em;
    }
}

@media (max-width: 580px) {
    #home {
        height: 100vh;
    }

    .play-img {
        margin: 40px auto;
    }
}



/*@import "../assets/lib/owl-carousel/owl.carousel.css";
@import "../assets/lib/owl-carousel/owl.theme.default.min.css";

@media (max-width: 1024px) {
    .row {
        margin-right: 0 !important;
    }
}

.play-img {
    margin: 0 auto;
    text-align: center;
}

.mx-auto {
    padding-right: 0 !important;
}

#home {
    padding: 0;
}

#home h1 {
    color: #ffffff;
}

#home h3 {
    color: #f9f9f9;
    font-size: 16px;
    font-weight: 300;
    margin: 0;
    padding: 5px 0 40px 0;
}

@media (min-width: 768px) {
    .home-slider .col-md-6 {
        padding-left: 0;
    }
}

.home-slider .caption {
    display: flex;
    justify-content: center;
    flex-direction: column;
    text-align: left;
    background-color: rgba(20, 20, 20, 0.2);
    height: 100%;
    color: #fff;
    cursor: e-resize;
}

.home-slider .item {
    background-repeat: no-repeat;
    background-attachment: local;
    background-size: cover;
    height: 650px;
}

.home-slider .item:before {
    content: "";
    background: linear-gradient(to right, rgba(0,0,0,1), rgba(0,0,0,0));
    position: absolute;
    bottom: 0;
    top: 0;
    left: 0;
    right: 0;
}

.caption h3 a {
    color: #FFF;
}

.caption h3 a:hover {
    color: #FF3;
}

.home-slider .item-first {
    background-image: url(../assets/landing/img/banner-5.jpg);
    background-position: center;
}

.home-slider .item-second {
    background-image: url(../assets/landing/img/banner-4.jpg);
}

.home-slider .item-third {
    background-image: url(../assets/landing/img/banner-6.jpg);
}

.input-group.md-form.form-sm.form-2 input {
    border: 1px solid #bdbdbd;
    border-top-left-radius: 2rem;
    border-bottom-left-radius: 2rem;
    height: 50px;
    background: rgba(255, 255, 255, 0.3);
    border-color: transparent;
}

.input-group-append span {
    border-top-right-radius: 2rem;
    border-bottom-right-radius: 2rem;
    background: linear-gradient(90deg, #721fa5 0%, #7e166e 100%);
    color: #fff;
    border-color: transparent;
}

.input-group {
}

::placeholder {
    color: #ffffff;
    opacity: 50%;
}

img {
    width: 136px !important;
}

.btn-flex {
    display: flex;
    justify-content: space-around;
    margin-top: 50px;
}

*/
</style>