<template>
    <div class="main-container">
        <TheHeader2 />
        <OffCanvasMobileMenu />
        <SearchPopup />
        <BreadcrumbOne activePageName="Services - Commerce" title="Cross border e-commerce with the power of technology" backgroundUrl= "/images/bg/breadcrumb-bg-1.jpg" />
        <CommerceService />


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