<template>
    <div class="section-padding-t90 section-padding-bottom overflow-hidden">
        <div class="container">
            <!-- Section Title Start -->
            <div class="section-title text-center" data-aos="fade-up">
                <h2 class="title fz-32">Revolutionizing Global Commerce: Cross-Border E-Commerce Empowered by Blockchain and
                    AI </h2>
                <p class="desc">Welcome to the future of cross-border e-commerce, where cutting-edge technologies such as
                    Blockchain and Artificial Intelligence converge to redefine the way businesses connect and thrive on a
                    global scale. In an era where borders are no longer barriers, our platform seamlessly integrates the
                    power of Blockchain and AI to unlock unprecedented opportunities for businesses and consumers alike.
                </p>
            </div>

            <section class="service-details section-padding pb-125">
                <div class="container">
                    <div class="row">
                        <div class="col-sm-6">
                            <div class="service-details-content mt-30">
                                <h4>Unlocking Global Opportunities with Blockchain</h4>
                                <p style="text-align: justify;">Experience a paradigm shift in the world of cross-border
                                    transactions with the
                                    transparency and security offered by Blockchain technology. Our platform leverages the
                                    decentralized nature of Blockchain to ensure trust, traceability, and integrity
                                    throughout the entire supply chain. Say goodbye to traditional bottlenecks and hello to
                                    a borderless marketplace where businesses can flourish without the constraints of
                                    geographical limitations. </p>
                            </div>
                        </div>

                        <div class="col-sm-6">
                            <div class="service-details-content mt-30">
                                <h4>Smart Solutions with Artificial Intelligence</h4>
                                <p style="text-align: justify;">Harness the power of Artificial Intelligence to elevate your
                                    cross-border e-commerce
                                    experience. Our AI-driven solutions bring unparalleled efficiency to every aspect of
                                    your business – from personalized customer experiences to predictive analytics that
                                    optimize inventory management and supply chain logistics. Embrace the future of
                                    commerce, where AI adapts to market trends, anticipates consumer behavior, and empowers
                                    you to make data-driven decisions with confidence.</p>
                            </div>
                        </div>

                    </div>
                </div>
            </section>


            <!-- Section Title End -->

            <section class="service-details section-padding pb-125">
                <div class="container">
                    <div class="row">
                        <div class="service-details-thumb">
                            <img src="/images/commerce/Cross-Border-Commerce-App-Hero-01.jpg"
                                alt="Hospitality Service Android APP" style="height:100%;" />
                        </div>
                        <h3 class="mt-4 mb-3">Our Service</h3>
                        <p>Join us on the forefront of the cross-border e-commerce revolution, where Blockchain and AI
                            converge to create a borderless marketplace that empowers businesses to thrive in the global
                            economy. Explore new horizons, connect with customers worldwide, and embrace the future of
                            commerce with confidence and innovation</p>
                        <div class="row">
                            <div class="col-sm-6">
                                <div class="service-details-content mt-30">
                                    <h4>Cross Border e-commerce</h4>
                                    <p>We provide cross border e-commerce with complete comprehensive supply chain </p>
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <div class="service-details-content mt-30">
                                    <h4>Fiat and Crypto Payment</h4>
                                    <p>Customer, logistic and seller can pay on various fiat and crypto with lower cost of payment. </p>
                                </div>
                            </div>

                            <div class="col-sm-6">
                                <div class="service-details-content mt-30">
                                    <h4>Advertisement with privacy</h4>
                                    <p>We use strict privacy policy with advertisement with minimum collections of data for our system.  </p>
                                </div>
                            </div>

                            <div class="col-sm-6">
                                <div class="service-details-content mt-30">
                                    <h4>High volume transaction</h4>
                                    <p>We support high volume transactions for cross border commerce</p>
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
import serviceData from '~/data/commerce-service.json';

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