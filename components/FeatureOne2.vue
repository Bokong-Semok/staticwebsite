<template>
    <div class="section-padding-t90-b100">
        <div class="container">
            <!-- Section Title Start -->
            <SectionTitle title="We create unique for experiences for the services" sub-title="Starting the to customize hospitality for you and your team" add-class-name="mb-60" />
            <!-- Section Title End -->

            <div class="row row-cols-lg-3 row-cols-md-2 row-cols-sm-2 row-cols-1 mtn-30">
                <div class="col mt-30" data-aos="fade-up" v-for="(feature, index) in serviceData.slice(0, 3)" :key="index">
                    <div class="icon-box text-center" :class="addClassName">
                        <div class="icon">
                            <img :src="feature.iconSrc" :alt="feature.title">
                        </div>
                        <div class="content">
                            <h3 class="title">{{ feature.title }}</h3>
                            <div class="desc">
                                <p>{{ feature.text }}</p>
                            </div>
                            <NuxtLink :to="`/services/${feature.slug}`" class="link">View Details</NuxtLink>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import serviceData from '~/data/service2.json'
    export default {
        props: ["addClassName"],

        components: {
            SectionTitle: () => import("@/components/SectionTitle"),
        },

        data() {
            return {
                serviceData
            }
        },
    };
</script>