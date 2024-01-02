<template>
    <div class="main-container">
        <TheHeader2 />
        <OffCanvasMobileMenu />
        <SearchPopup />
        <BreadcrumbOne activePageName="Services - Software Development" title="Our tech in real world" backgroundUrl= "/images/bg/breadcrumb-bg-1.jpg" />
        <SoftwareService />


        <CallToActionOne2 />
        <TheFooter2 />
    </div>
</template>
<script>
import SoftwareService from '~/components/SoftwareService.vue';

    export default {
    head() {
        return {
            title: 'Services - Software Development'
        };
    },
    components: { SoftwareService }
};
</script>