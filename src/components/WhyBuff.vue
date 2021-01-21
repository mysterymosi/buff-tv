<template>
    <!-- Start screenshot section -->
    <section class="about-section section-gap-full">
        <div class="container">
            <div class="section-title">
                <h2 class="text-center">Why Buff Tv?</h2>
            </div>
            <div class="row align-items-center justify-content-between">
                <div class="col-lg-6 col-md-12 about-left">
                    <!-- <div class="overlay"></div> -->
                    <img class="img-fluid tv-img" src="../assets/images/tv-1.png" alt="">
                    <video height="900" autoplay loop muted>
                        <source src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/video-tv-0819.m4v" type="video/mp4">
                        Your browser does not support the video tag.
                    </video>
                </div>
                <div class="col-lg-5 col-md-7 about-right">
                    <ul>
                        <li class="d-flex m-bottom">
                            <div class="icon">
                                <span class="ti-layout-media-center-alt"></span>
                            </div>
                            <div class="details">
                                <h4>Pack and Deliver, anything, anywhere From the convenience of your home or office</h4>
                            </div>
                        </li>
                        <li class="d-flex m-bottom">
                            <div class="icon">
                                <span class="ti-crown"></span>
                            </div>
                            <div class="details">
                                <h4>Pack and Deliver, anything, anywhere From the convenience of your home or office</h4>
                            </div>
                        </li>
                        <li class="d-flex m-bottom">
                            <div class="icon">
                                <span class="ti-headphone-alt"></span>
                            </div>
                            <div class="details">
                                <h4>Pack and Deliver, anything, anywhere From the convenience of your home or office</h4>
                            </div>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    <!-- End about section -->
</template>
<style scoped>
.m-bottom {
    margin-bottom: 99px !important;
}

.about-section {
    background-color: #fafafa;
    /*margin-top: 18px;*/
    padding-top: 240px;
}

.about-left {
    background-size: cover;
    background-position: center;
}

.about-left .overlay{
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 100;
    background-color: rgba(0, 0, 0, 0.75);
}

.about-left .tv-img {
    z-index: 100;
} 

.about-left video {
    position: absolute;
    top: 43%;
    left: 50%;
    min-width: 10%;
    min-height: 10%;
    width: 93.1%;
    height: 102%;
    /*z-index: -3;*/
    transform: translateX(-50%) translateY(-50%);
    background-size: cover;
    transition: 1s opacity;
}

@media (max-width: 768px) {
    .about-left video {
        width: 94.4%;
    }
}

@media (max-width: 480px) {
    .about-left video {
        width: 92.3%;
    }
}

@media (max-width: 414px) {
    .about-left video {
        width: 91.1%;
    }
}

@media (max-width: 375px) {
    .about-left video {
        width: 90.8%;
    }
}

@media (max-width: 320px) {
    .about-left video {
        width: 89.2%;
    }
}
</style>