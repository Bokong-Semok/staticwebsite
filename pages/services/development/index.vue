<template>
    <div class="main-container">
        <TheHeader2 />
        <OffCanvasMobileMenu />
        <SearchPopup />
        <BreadcrumbOne activePageName="Services - Software Development" title="We develop our own tech and serve you" backgroundUrl= "/images/bg/breadcrumb-bg.jpg" />

        <CallToActionOne2 />
        <TheFooter2 />
    </div>
</template>
<script>
    export default {
        head() {
            return {
                title: 'Services - Software Development'
            }
        },
    };
</script>