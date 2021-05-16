<template>
<div class="gradient leading-relaxed tracking-wide flex flex-col" style="background-image: url('https://static.mod.io/v1/images/home/bg-tiles.jpg'); background-size: contain, cover;">
    <!--Nav-->
    <navbar :links="links"/>

    <!--View-->
    <router-view />

    <!--Footer-->
    <Footer />
</div>
</template>

<script>
import Navbar from './components/Navbar'
import Footer from './components/Footer'

export default {
    components: {
        Navbar,
        Footer
    },

    data() {
        return {
          links: [
            { name: 'Home', url: '/'},
            { name: 'About', url: '/about'},
            { name: 'Contact', url: '/contact'},
          ]
        }
    }
}
</script>
