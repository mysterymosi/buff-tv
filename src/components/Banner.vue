<template>
    <!-- <section id="home">
        <div class="row">
            <div class="owl-carousel owl-theme home-slider">
                <div class="item item-first">
                    <div class="caption">
                        <div class="container">
                            <div class="col-md-6 col-sm-12">
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
                    </div>
                </div>
                <div class="item item-second">
                    <div class="caption">
                        <div class="container">
                            <div class="col-md-6 col-sm-12">
                                <h1>Start your journey with our practical courses</h1>
                                <h3>Our online courses are built in partnership with technology leaders and are designed to meet industry demands.</h3>
                                <a href="#courses" class="section-btn btn btn-default smoothScroll">Take a course</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="item item-third">
                    <div class="caption">
                        <div class="container">
                            <div class="col-md-6 col-sm-12">
                                <h1>Efficient Learning Methods</h1>
                                <h3>Nam eget sapien vel nibh euismod vulputate in vel nibh. Quisque eu ex eu urna venenatis sollicitudin ut at libero. Visit <a rel="nofollow" href="https://www.facebook.com/templatemo">templatemo</a> page.</h3>
                                <a href="#contact" class="section-btn btn btn-default smoothScroll">Let's chat</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <VueInjectJs src="/lib/owl-carousel/custom.js" />
    </section> -->
    <!-- Start banner section -->
    <section class="banner-section relative section-gap-full" id="banner-section">
        <div class="overlay overlay-bg"></div>
        <div class="container">
            <div class="row">
                <div class="col-md-6 banner-left">
                    <div class="input-group md-form form-sm form-2 pl-0">
                        <input class="form-control my-0 py-1 amber-border" type="text" placeholder="Enter Email" aria-label="Search">
                        <div class="input-group-append">
                            <span class="input-group-text amber lighten-3" id="basic-text1">Get Started</span>
                        </div>
                    </div>
                    <div class="btn-flex">
                        <a href="about-us.html"><img class="img-fluid" src="../assets/landing/img/play.svg" alt=""></a>
                        <a href="about-us.html"><img class="img-fluid" src="../assets/landing/img/apple.svg" alt=""></a>
                    </div>
                </div>
                <div class="col-md-6 banner-right text-center">
                    <img class="img-fluid" src="../assets/landing/img/youtube.svg" alt="">
                </div>
            </div>
        </div>
        <div class="wave">
            <svg class="nectar-shape-divider" fill="" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 300" preserveAspectRatio="none">
                <path d="M 1000 299 l 2 -279 c -155 -36 -310 135 -415 164 c -102.64 28.35 -149 -32 -232 -31 c -80 1 -142 53 -229 80 c -65.54 20.34 -101 15 -126 11.61 v 54.39 z"></path>
                <path d="M 1000 286 l 2 -252 c -157 -43 -302 144 -405 178 c -101.11 33.38 -159 -47 -242 -46 c -80 1 -145.09 54.07 -229 87 c -65.21 25.59 -104.07 16.72 -126 10.61 v 22.39 z"></path>
                <path d="M 1000 300 l 1 -230.29 c -217 -12.71 -300.47 129.15 -404 156.29 c -103 27 -174 -30 -257 -29 c -80 1 -130.09 37.07 -214 70 c -61.23 24 -108 15.61 -126 10.61 v 22.39 z"></path>
            </svg>
        </div>
    </section>
    <!-- End banner section -->
</template>
<script>
// import VueInjectJs from "vue-inject-js"
export default {
    components: {
        // VueInjectJs
    }
}
</script>

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
</style>
<!-- <style scoped>
@import "../assets/lib/owl-carousel/owl.carousel.css";
@import "../assets/lib/owl-carousel/owl.theme.default.min.css";

@media (max-width: 1024px) {
    .row {
        margin-right: 0 !important;
    }
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
    background: rgba(0, 0, 0, 0.6);
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
    background-image: url(../assets/images/sexed.svg);
    background-position: center;
}

.home-slider .item-second {
    background-image: url(../assets/images/sexed.svg);
}

.home-slider .item-third {
    background-image: url(../assets/images/sexed.svg);
}

.input-group.md-form.form-sm.form-2 input {
    border: 1px solid #bdbdbd;
    border-top-left-radius: 2rem;
    border-bottom-left-radius: 2rem;
    height: 50px;
}

.input-group-append span {
    border-top-right-radius: 2rem;
    border-bottom-right-radius: 2rem;
}

img {
    width: 136px !important;
}

.btn-flex {
    display: flex;
    justify-content: space-around;
    margin-top: 50px;
}
</style> -->