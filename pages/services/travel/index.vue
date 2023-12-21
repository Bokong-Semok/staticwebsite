<template>
    <div class="main-container">
        <TheHeader2 />
        <OffCanvasMobileMenu />
        <SearchPopup />
        <BreadcrumbOne activePageName="Services - Travel" title="We prepare travel package for you and your team" backgroundUrl= "/images/bg/breadcrumb-bg-1.jpg" />

        <CallToActionOne2 />
        <TheFooter2 />
    </div>
</template>

<script>
    export default {
        head() {
            return {
                title: 'Services - Travel'
            }
        },
    };
</script>