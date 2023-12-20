<template>
    <div class="main-container">
        <TheHeader2 />
        <OffCanvasMobileMenu />
        <SearchPopup />
        <HeroSliderOne />
        <AboutOne />
        <FeatureOne :style="{backgroundColor: '#f8faff'}" />
        <SuccessStory />
        <PortfolioGallery />
        <BlogSectionOne />
        <Newsletter />
        <CallToActionOne2 />
        <TheFooter2 />
    </div>
</template>

<script>
    export default {
        head() {
            return {
                title: 'Bokong Semok'
            }
        },
    };
</script>


