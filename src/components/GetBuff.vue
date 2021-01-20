<template>
    <!-- Start explore section -->
    <section class="explore-section section-gap-full relative">
        <div class="overlay overlay-bg"></div>
        <div class="container">
            <div class="row">
                <div class="col-lg-6 text-center mx-auto">
                    <button class="btn btn-primary btn-lg"><h1>Get Buff Today</h1></button>
                    <!-- <h1>Other Features</h1> -->
                    <h3>for as low as 3500/month</h3>
                </div>
                <!-- <div class="col-lg-6 explore-right"></div> -->
            </div>
        </div>
    </section>
    <!-- End explore section -->
</template>

<style scoped>
/*.col-lg-6 {
	margin: 0 auto !important;
}
*/
.btn-primary {
	background: linear-gradient(90deg, #721fa5 0%, #7e166e 100%);
	border: none;
	margin-bottom: 10px;
	border-radius: 86.5px;
	/*width: 410px;*/
}

@media (max-width: 500px) {
    .btn-primary h1 {
        font-size: 2rem !important;
    }
}

.explore-section h1 {
	padding: 0;
	margin: 0;
}

.explore-section h3 {
	color: black;
}
</style>