<template>
    <div class="main-container">
        <TheHeader2 />
        <OffCanvasMobileMenu />
        <SearchPopup />
        <BreadcrumbOne activePageName="Technology" title="Our Technology expert to build" backgroundUrl= "/images/bg/breadcrumb-bg.jpg" />

        <CallToActionOne2 />
        <TheFooter2 />
    </div>
</template>
<script>
    export default {
        head() {
            return {
                title: 'Technology'
            }
        },
    };
</script>