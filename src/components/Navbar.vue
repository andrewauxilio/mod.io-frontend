<template>
<nav id="header" class="animate__animated animate__fadeIn w-full z-30 top-0 text-white py-1 lg:py-6">
    <div class="w-full container mx-auto flex flex-wrap items-center justify-between mt-0 px-2 py-2 lg:py-6">
        <div class="pl-4 flex items-center">
            <a class="text-white no-underline hover:no-underline font-bold text-2xl lg:text-4xl" href="#">
                <img src="https://static.mod.io/v1/images/default/logo.svg" alt="mod.io" width="200">
            </a>
        </div>

        <div class="block lg:hidden pr-4">
            <button @click="toggleNav" id="nav-toggle" class="flex items-center px-3 py-2 border rounded text-gray-500 border-gray-400 hover:text-white hover:border-blue-500 appearance-none focus:outline-none">
                <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                    <title>Menu</title>
                    <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
                </svg>
            </button>
        </div>

        <div v-bind:class="{hidden: !isActive}" class="animate__animated animate__fadeIn w-full flex-grow lg:flex lg:items-center lg:w-auto lg:block mt-2 lg:mt-0 text-white p-4 lg:p-0 z-20" id="nav-content">
            <ul class="list-reset lg:flex justify-end flex-1 items-center">
                <li v-for="link in links" :key="link" class="mr-3">
                    <router-link class="inline-block py-2 px-2 text-white no-underline" :to="link.url">{{ link.name }}</router-link>
                </li>
            </ul>
        </div>
    </div>
</nav>
</template>

<script>
export default {
    props: {
        links: Array
    },

    data() {
        return {
            isActive: false
        }
    },

    methods: {
        toggleNav() {
            this.isActive = !this.isActive;
        }
    }
}
</script>
