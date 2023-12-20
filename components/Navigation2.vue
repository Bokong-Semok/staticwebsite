<template>
    <nav class="site-main-menu">
        <ul>
            <li>
                <NuxtLink to="/">Home</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/about">About Us</NuxtLink>
            </li>
            <li class="has-children">
                <NuxtLink to="/services">Service</NuxtLink>
                <ul class="sub-menu">
                    <li>
                        <NuxtLink to="/services/travel">Travel</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/services/meeting">Meeting</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/services/development">Software</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/services/commerce">Commerce</NuxtLink>
                    </li>
                   
                </ul>
            </li>
            <!-- <li class="has-children">
                <NuxtLink to="/project">Products</NuxtLink>
                <ul class="sub-menu">
                    <li>
                        <NuxtLink to="/project">Project</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/project/project-details">Project Details</NuxtLink>
                    </li>
                </ul>
            </li> -->
            <!-- <li class="has-children">
                <NuxtLink to="/blog">Blog</NuxtLink>
                <ul class="sub-menu">
                    <li>
                        <NuxtLink to="/blog">Blog Grid</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/blog/blog-classic">Blog Classic</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/blog/blog-details">Blog Details</NuxtLink>
                    </li>
                </ul>
            </li> -->
            <li>
                <NuxtLink to="/contact-us">Contact Us</NuxtLink>
            </li>
        </ul>
    </nav>
</template>