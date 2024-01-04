<template>
    <div class="section-padding-t90 section-padding-bottom-200 overflow-hidden">
        <div class="container">
            <!-- Section Title Start -->
            <div class="section-title text-center" data-aos="fade-up">
                <h2 class="title">We develop and market commerce and hospitality with technology</h2>
                <p class="sub-title">Travel and Meeting with AI recommendation, back with blockchain technology</p>
            </div>
            
            <!-- Section Title End -->

            <!-- About Wrapper Start -->
            <div class="row">
                <!-- About Image Area Start -->
                <div class="col-xl-7 col-lg-6" data-aos="fade-up">
                    <div class="about-image-area">
                        <div class="about-image js-tilt">
                            <img src="/images/about/about-1.jpg" alt="images">
                        </div>
                        <div class="about-image js-tilt">
                            <img src="/images/about/about-2.jpg" alt="images">
                        </div>

                        <!-- Animation Shape Start -->
                        <ShapeWithAnimation addClassName="shape-1" dataDepth="1" imgSrc="/images/shape-animation/about-shape-1.png" />
                        <!-- Animation Shape End -->
                    </div>
                </div>
                <!-- About Image Area Start -->

                <!-- About Start -->
                <div class="col-xl-5 col-lg-6" data-aos="fade-up">
                    <div class="about-content-area about-one">
                        <!-- Section Title Two Start -->
                        <div class="section-title-two">
                            <span class="sub-title">Hospitality</span>
                            <h3 class="title">Bring hospitality with Blockchain and AI technology.</h3>
                        </div>

                        <div class="section-title-two">
                            <span class="sub-title">Cross-border e-commerce</span>
                            <h3 class="title">E-commerce with crypto + fiat payments.</h3>
                        </div>
                        <!-- Section Title Two End -->

                        <p>Hospitality and cross border commerce powered by blockchain and AI technology</p>
                        <NuxtLink to="/technology" class="btn btn-primary btn-hover-secondary mt-4">Tell me</NuxtLink>
                    </div>
                </div>
                <!-- About Start -->
            </div>
            <!-- About Wrapper End -->
        </div>
    </div>
</template>

<script>
    export default {
        components: {
            ShapeWithAnimation: () => import('@/components/ShapeWithAnimation'),
        },
    };
</script>