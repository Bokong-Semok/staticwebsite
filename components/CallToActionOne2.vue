<template>
    <div class="section-padding-t90-b100 overflow-hidden">
        <div class="container shape-animate">
            <!-- Section Title Start -->
            <SectionTitle title="Teams" sub-title="Our team are passionate on tech" add-class-name="mb-30" />
            <!-- Section Title End -->

            <div class="row row-cols-lg-3 row-cols-md-2 row-cols-sm-2 row-cols-1 mtn-30">
                <div class="col mt-30" data-aos="fade-up">
                    <div class="contact-info">
                        <div class="icon">
                            <img class="svgInject" src="/images/svg/linea/linea-basic-map.svg" alt="Icon">
                        </div>
                        <div class="info">
                            <h4 class="title">Our Locations</h4>
                            <span class="info-text"> 2 Frederick Street, Kings Cross <br/>London, UNITED KINGDOM </span>
                        </div>
                    </div>
                </div>

                <!-- <div class="col mt-30" data-aos="fade-up">
                    <div class="contact-info">
                        <div class="icon">
                            <img class="svgInject" src="/images/svg/linea/linea-basic-message-txt.svg" alt="Icon">
                        </div>
                        <div class="info">
                            <h4 class="title">Give Us A Call</h4>
                            <span class="info-text"> +86 15267084773 <br></span>
                        </div>
                    </div>
                </div> -->

                <div class="col mt-30" data-aos="fade-up">
                    <div class="contact-info">
                        <div class="icon">
                            <img class="svgInject" src="/images/svg/linea/linea-basic-mail-open-text.svg" alt="Icon">
                        </div>
                        <div class="info">
                            <h4 class="title">Sales and Marketing</h4>
                            <span class="info-text">
                                You can fill  <a style="color: blue;" href="https://form.jotform.com/240012309096043" target="_blank">CONTACT FORM </a>&nbsp;&nbsp;
                                <br>
                                <!-- <a href="mailto:demo@example.com">demo@example.com</a> -->
                            </span>
                        </div>
                    </div>
                </div>
            </div>

            <shape-with-animation add-class-name="shape-1" data-depth="4" img-src="/images/shape-animation/video-shape-1.png" />

        </div>
    </div>
</template>

<script>

    export default {
        components: {
            SectionTitle: () => import("@/components/SectionTitle"),
            ShapeWithAnimation: () => import("@/components/ShapeWithAnimation"),
        },
    };
</script>
