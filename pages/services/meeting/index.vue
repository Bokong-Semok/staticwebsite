<template>
    <div class="main-container">
        <TheHeader2 />
        <OffCanvasMobileMenu />
        <SearchPopup />
        <BreadcrumbOne activePageName="Services - Meeting" title="We prepare meeting package for you and your team" backgroundUrl= "/images/bg/breadcrumb-bg-1.jpg" />

        <CallToActionOne2 />
        <TheFooter2 />
    </div>
</template>
<script>
    export default {
        head() {
            return {
                title: 'Services - Meeting'
            }
        },
    };
</script>