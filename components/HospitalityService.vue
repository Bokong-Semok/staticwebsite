<template>
    <div class="section-padding-t90 section-padding-bottom overflow-hidden">
        <div class="container">
            <!-- Section Title Start -->
            <div class="section-title text-center" data-aos="fade-up">
                <h2 class="title fz-32">Elevate Your Hospitality Experience with Cutting-Edge Blockchain and AI Solutions
                </h2>
                <p class="desc">Our innovation meets hospitality excellence. We redefine the guest experience by seamlessly
                    integrating blockchain and artificial intelligence into every aspect of our services. Our commitment is
                    to bring a new era of efficiency, transparency, and personalized service to the hospitality industry.
                </p>
            </div>
            <!-- Section Title End -->

            <section class="service-details section-padding pb-125">
                <div class="container">
                    <div class="row">
                        <div class="service-details-thumb">
                            <img src="/images/hospitality/hospitality-service-android-app-hero-01.jpg"
                                alt="Hospitality Service Android APP" style="height:75%;"/>
                        </div>
                        <h3 class="mt-4 mb-3">Our Service</h3>
                        <p>Welcome to a new era of hospitality where cutting-edge technology meets unparalleled service. Our
                            innovative approach integrates the power of Blockchain and Artificial Intelligence to redefine
                            the guest experience, ensuring a seamless and secure journey from reservation to check-out.</p>
                        <div class="row">
                            <div class="col-sm-6">
                                <div class="service-details-content mt-30">
                                    <h4>Social and Business Meeting</h4>
                                    <p>Use our recommendation for social meeting for you, your team or your business opportinities with our unique </p>
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <div class="service-details-content mt-30">
                                    <h4>Personalize Travel</h4>
                                    <p>Our technology enrich your travel experience, meet new people, enjoy culture.</p>
                                </div>
                            </div>

                            <div class="col-sm-6">
                                <div class="service-details-content mt-30">
                                    <h4>Fine Dining</h4>
                                    <p>Indulge in a culinary delight at our fine dining restaurant, offering a diverse menu of gourmet dishes prepared by our skilled chefs </p>
                                </div>
                            </div>

                            <div class="col-sm-6">
                                <div class="service-details-content mt-30">
                                    <h4>Escape session</h4>
                                    <p>Tired of daily activity, just escape to a place for you and your family</p>
                                </div>
                            </div>

                           

                        </div>

                    </div>
                </div>
            </section>



            <div>
                <h3 class="mt-4 mb-3">Why use our service</h3>
                <!-- About Wrapper Start -->
                <div class="row row-cols-lg-3 row-cols-md-2 row-cols-sm-2 row-cols-1 icon-box-shape-animation mtn-30">


                    <div class="col mt-30" data-aos="fade-up" v-for="(service, index) in serviceData" :key="index">
                        <ServiceItem2 :service="service" addClassName="box-border" />
                    </div>

                    <ShapeWithAnimation addClassName="shape-1" data-depth="1"
                        imgSrc="/images/shape-animation/video-shape-1.png" />
                </div>
                <!-- About Wrapper End -->
            </div>


        </div>
    </div>
</template>
<script>
import serviceData from '~/data/hospitality-service.json';

export default {
    components: {
        ServiceItem2: () => import('@/components/ServiceItem2'),
        ShapeWithAnimation: () => import('@/components/ShapeWithAnimation'),
    },

    data() {
        return {
            serviceData
        }
    },
};

</script>