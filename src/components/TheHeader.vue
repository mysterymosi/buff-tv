<template>
    <!-- Start header section -->
    <header class="header-area" id="header-area">
        <div id="dope-nav-container" class="dope-nav-container breakpoint-off">
            <div class="container">
                <div class="row">
                    <!-- dope Menu -->
                    <nav class="dope-navbar justify-content-between" id="dopeNav">
                        <!-- Logo -->
                        <a class="nav-brand" href="index.html">
                            <!-- <img src="../assets/landing/img/logo.png" alt=""> -->
                            <strong>Buff</strong>
                        </a>
                        <!-- Navbar Toggler -->
                        <div class="dope-navbar-toggler">
                            <span class="navbarToggler">
                                <span></span>
                                <span></span>
                                <span></span>
                            </span>
                        </div>
                        <!-- Menu -->
                        <div class="dope-menu">
                            <!-- close btn -->
                            <div class="dopecloseIcon">
                                <div class="cross-wrap">
                                    <span class="top"></span>
                                    <span class="bottom"></span>
                                </div>
                            </div>
                            <!-- Nav Start -->
                            <div class="dopenav">
                                <ul id="nav">
                                    <li>
                                        <router-link to="/">Home</router-link>
                                    </li>
                                    <li>
                                        <a href="#about-section">About</a>
                                    </li>
                                    <li>
                                        <a href="#feature-section">Contact Us</a>
                                    </li>
                                    <li>
                                        <a href="#price-section">Price</a>
                                    </li>
                                    <li>
                                        <router-link to="/login">Login</router-link>
                                    </li>
                                    <li>
                                        <router-link to="/register">Signup</router-link>
                                    </li>
                                </ul>
                            </div>
                            <!-- Nav End -->
                        </div>
                    </nav>
                </div>
            </div>
        </div>
    </header>
    <!-- Start header section -->
</template>
<script>
export default {
    data() {
        return {
            breakpoint: 991
        }
    },

    mounted() {
        this.breakpointCheck();
    },

    methods: {
        breakpointCheck() {
            const navContainer = document.querySelector('.dope-nav-container');
            let windoWidth = window.innerWidth;
            console.log("navc: ", navContainer);
            if (windoWidth <= this.breakpoint) {
                navContainer.classList.remove('breakpoint-off');
                navContainer.classList.add('breakpoint-on');
            } else {
                navContainer.classList.remove('breakpoint-on');
                navContainer.classList.add('breakpoint-off');
            }
        }
    }
}
</script>
<style scoped>
.nav-brand {
    color: #721fa5 !important;
}
</style>