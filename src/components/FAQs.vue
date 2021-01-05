<template>
    <!-- Start faq section -->
    <section class="home-faq-section faq-section">
        <div class="container">
            <div class="section-title">
                <h2 class="text-center">Frequently Asked Question</h2>
            </div>
            <div class="row justify-content-between">
                <div class="col-lg-7">
                    <dl class="accordion">
                        <dt>
                            <a class="acc-link" href="#">What is Buff TV?</a>
                        </dt>
                        <dd class="answer">
                            Far curiosity incommode now led smallness allowance. Favour bed assure son things yet. She
                            consisted consulted elsewhere happiness disposing household any old the. Widow downs you
                            new shade drift hopes small. So otherwise commanded sweetness we improving.
                        </dd>
                        <dt>
                            <a class="acc-link" href="#">What is Buff TV?</a>
                        </dt>
                        <dd class="answer">
                            Far curiosity incommode now led smallness allowance. Favour bed assure son things yet. She
                            consisted consulted elsewhere happiness disposing household any old the. Widow downs you
                            new shade drift hopes small. So otherwise commanded sweetness we improving.
                        </dd>
                        <dt>
                            <a class="acc-link" href="#">What is Buff TV?</a>
                        </dt>
                        <dd class="answer">
                            Far curiosity incommode now led smallness allowance. Favour bed assure son things yet. She
                            consisted consulted elsewhere happiness disposing household any old the. Widow downs you
                            new shade drift hopes small. So otherwise commanded sweetness we improving.
                        </dd>
                        <dt>
                            <a class="acc-link" href="#">What is Buff TV?</a>
                        </dt>
                        <dd class="answer">
                            Far curiosity incommode now led smallness allowance. Favour bed assure son things yet. She
                            consisted consulted elsewhere happiness disposing household any old the. Widow downs you
                            new shade drift hopes small. So otherwise commanded sweetness we improving.
                        </dd>
                        <dt>
                            <a class="acc-link" href="#">What is Buff TV?</a>
                        </dt>
                        <dd class="answer">
                            Far curiosity incommode now led smallness allowance. Favour bed assure son things yet. She
                            consisted consulted elsewhere happiness disposing household any old the. Widow downs you
                            new shade drift hopes small. So otherwise commanded sweetness we improving.
                        </dd>
                    </dl>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    mounted() {
        const acclink = document.getElementsByClassName("acc-link");
        const answers = document.getElementsByClassName("answer");
        console.log("Acc: ", acclink);
        acclink.forEach((linkValue) => {
            if (linkValue.classList.contains("active")) {
            	console.log("contains");
                linkValue.classList.remove("active");
            } else {
            	console.log("bollocks");
            }
        });
        answers.forEach((answer) => {
        	answer.style.display = "none";
        });
    }
}
</script>
<style scoped>
.col-lg-7 {
    margin: 0 auto !important;
}

.home-faq-section {
    background-color: #45093f;
}

h2 {
    color: #fff;
}

dt>a {
    font-size: 22px;
    font-weight: 100;
}
</style>