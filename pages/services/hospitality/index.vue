<template>
    <div class="main-container">
        <TheHeader2 />
        <OffCanvasMobileMenu />
        <SearchPopup />
        <BreadcrumbOne activePageName="Services - Hospitality" title="Our hospitality meet high tech" backgroundUrl= "/images/bg/breadcrumb-bg-1.jpg" />

        <CallToActionOne2 />
        <TheFooter2 />
    </div>
</template>
<script>
    export default {
        head() {
            return {
                title: 'Services - Hospitality'
            }
        },
    };
</script>