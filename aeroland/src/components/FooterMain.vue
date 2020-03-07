<template>
    <div class="footer-area-wrapper" :class="FooterStyle">
        <div class="footer-area section-space--ptb_90">
            <div class="container">
                <div class="row footer-widget-wrapper">
                    <div class="col-lg-4 col-md-6 footer-widget">
                        <div class="footer-widget__logo mb-30">
                            <router-link to="/">
                                <img src="../assets/img/logo/logo-dark.png" class="img-fluid logo-dark" alt="">
                                <img src="../assets/img/logo/white-logo.png" class="img-fluid logo-light" alt="MNY">
                            </router-link>
                        </div>
                        <ul class="footer-widget__list">
                            <li>800 Howe Ave Suite 160<br> Sacramento, CA 95825</li>
                            <li><a href="#" class="hover-style-link">contact@mny.ai</a></li>
                            <li><a href="#" class="hover-style-link">844-MAKE-MNY</a></li>
                            <li><a href="#" class="hover-style-link hover-style-link--green">www.MNY.ai</a></li>
                        </ul>
                    </div>
                    <div class="col-lg-2 col-md-6 footer-widget">
                    </div>
                    <div class="col-lg-2 col-md-6 footer-widget">
                    </div>
                    <div class="col-lg-3 col-md-6 offset-lg-1 footer-widget">
                        <div class="twitter-feed-slider">
                            <div class="swiper-container twitter-feed-slider__container">
                                <div class="swiper-wrapper twitter-feed-slider__wrapper">
                                    <div class="swiper-slide twitter-feed-slider__single">
                                        <div class="tweet">
                                            <div class="tweet__text">
                                                "We're looking for a few good people: work in the 21st century." Featuring Mary Klein, C.P.A.
                                                <a href="https://t.co/" target="_blank">https://t.co/kdjhf0304</a>
                                            </div>
                                            <div class="tweet__info">
                                                <h6 class="tweet__heading">MNY, Inc.</h6>
                                                <span class="tweet__date">May 22, 2020</span>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer-copyright-area border-top section-space--ptb_30">
            <div class="container">
                <div class="row align-items-center">
                    <div class="col-md-6 text-center text-md-left">
                        <span class="copyright-text">© 2020 MNY, Inc. All Rights Reserved.</span>
                    </div>
                    <div class="col-md-6 text-center text-md-right">
                        <ul class="list ht-social-networks solid-rounded-icon">
                            <li class="item">
                                <a href="#" target="_blank" class="social-link"> <i class="fab fa-facebook social-link-icon"></i> </a>
                            </li>
                            <li class="item">
                                <a href="#" target="_blank" class="social-link"> <i class="fab fa-twitter social-link-icon"></i> </a>
                            </li>
                            <li class="item">
                                <a href="#" target="_blank" class="social-link"> <i class="fab fa-instagram social-link-icon"></i> </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterMain',
        props: ["FooterStyle"]
    }
</script>
