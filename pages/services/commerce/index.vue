<template>
    <div class="main-container">
        <TheHeader2 />
        <OffCanvasMobileMenu />
        <SearchPopup />
        <BreadcrumbOne activePageName="Services - Commerce" title="We develop our own shops" backgroundUrl= "/images/bg/breadcrumb-bg.jpg" />

        <CallToActionOne2 />
        <TheFooter2 />
    </div>
</template>
<script>
    export default {
        head() {
            return {
                title: 'Services - Commerce'
            }
        },
    };
</script>