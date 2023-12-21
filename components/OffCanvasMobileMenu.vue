<template>
    <div class="popup-mobile-menu popup-mobile-visiable" id="offcanvas-menu">
        <div class="mobile-menu-overlay" @click="mobiletoggleClass('removeClass', 'show-mobile-menu')"></div>
        <div class="inner custom-scrollbar">
            <div class="mobile-header">
                <div class="logo">
                    <NuxtLink to="/">
                        <img :src="'/images/logo/logo2.png'" alt="Bokong Semok logo">
                    </NuxtLink>
                </div>
                <button class="mobile-close-btn" @click="mobiletoggleClass('removeClass', 'show-mobile-menu')"></button>
            </div>
            <div class="menu-content">
                <MobileNavigation2 />
            </div>
        </div>
    </div>
</template>

<script>
import MobileNavigation2 from './MobileNavigation2.vue';

    export default {
        components: {
    MobileNavigation: () => import('@/components/MobileNavigation'),
    MobileNavigation2
},
        
        methods: {
            // offcanvas menu close
            mobiletoggleClass(addRemoveClass, className) {
                const el = document.querySelector('#offcanvas-menu');
                if (addRemoveClass === 'addClass') {
                    el.classList.add(className);
                } else {
                    el.classList.remove(className);
                }
            }
        }
    };
</script>