<template>
<div class="gradient leading-relaxed tracking-wide flex flex-col" style="background-image: url('https://static.mod.io/v1/images/home/bg-tiles.jpg'); background-size: contain, cover;">
    <!--Nav-->
    <nav id="header" class="w-full z-30 top-0 text-white py-1 lg:py-6">
        <div class="w-full container mx-auto flex flex-wrap items-center justify-between mt-0 px-2 py-2 lg:py-6">
            <div class="pl-4 flex items-center">
                <a class="text-white no-underline hover:no-underline font-bold text-2xl lg:text-4xl" href="#">
                    <img src="https://static.mod.io/v1/images/default/logo.svg" alt="mod.io" width="200">
                </a>
            </div>

            <div class="block lg:hidden pr-4">
                <button id="nav-toggle" class="flex items-center px-3 py-2 border rounded text-gray-500 border-gray-400 hover:text-white hover:border-blue-500 appearance-none focus:outline-none">
                    <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                        <title>Menu</title>
                        <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
                    </svg>
                </button>
            </div>

            <div class="w-full flex-grow lg:flex lg:items-center lg:w-auto hidden lg:block mt-2 lg:mt-0 text-white p-4 lg:p-0 z-20" id="nav-content">
                <ul class="list-reset lg:flex justify-end flex-1 items-center">
                    <li class="mr-3">
                        <a class="inline-block py-2 px-4 text-white font-bold no-underline" href="#">Home</a>
                    </li>
                    <li class="mr-3">
                        <a class="inline-block text-white no-underline hover:text-white hover:text-underline py-2 px-4" href="#">About</a>
                    </li>
                    <li class="mr-3">
                        <a class="inline-block text-white no-underline hover:text-white hover:text-underline py-2 px-4" href="#">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container mx-auto h-screen">
        <div class="text-center px-3 lg:px-0">
            <h1 class="my-4 text-2xl md:text-3xl text-white lg:text-5xl font-black leading-tight">
                Mod support for every platform
            </h1>
            <p class="leading-normal text-white text-base md:text-xl lg:text-2xl mb-8">
                Enable cross-platform UGC and thriving creator communities in your games.
            </p>
            <button class="mx-auto lg:mx-1 hover:underline text-white font-extrabold rounded my-2 md:my-6 mx-1 py-4 px-8 shadow-lg w-48">
                Request a Demo
            </button>
        </div>

        <div class="flex items-center w-full mx-auto content-end">
            <img src="https://binary.modcdn.io/misc/hero-art.svg">
        </div>
    </div>

    <section class="bg-white border-b py-8 text-center">
        <div class="container mx-auto flex flex-wrap pt-4 pb-12">
            <h2 class="w-full my-2 text-5xl font-black leading-tight text-center text-white">
                How to launch your creator community
            </h2>

            <div class="w-full md:w-1/3 p-6 flex flex-col flex-grow flex-shrink">
                <div class="flex-1 bg-white rounded-t rounded-b-none overflow-hidden shadow">
                    <a href="#" class="flex flex-wrap no-underline hover:no-underline">
                        <div class="mt-6 w-full font-bold text-xl text-black px-6">
                            <img class="mx-auto" src="https://static.mod.io/v1/images/home/launch-support.svg">
                            Build your game
                        </div>
                        <p class="text-gray-600 text-base px-6 mb-5">
                            Plan your UGC strategy, setup your game to support UGC &amp; you are ready to go.
                        </p>
                    </a>
                </div>
                <div class="flex-none mt-auto bg-white rounded-b rounded-t-none overflow-hidden shadow p-6">
                    <div class="flex items-center justify-center">
                        <button class="mx-auto lg:mx-0 hover:underline gradient2 text-white font-extrabold rounded my-6 py-4 px-8 shadow-lg">
                            Action
                        </button>
                    </div>
                </div>
            </div>

            <div class="w-full md:w-1/3 p-6 flex flex-col flex-grow flex-shrink">
                <div class="flex-1 bg-white rounded-t rounded-b-none overflow-hidden shadow">
                    <a href="#" class="flex flex-wrap no-underline hover:no-underline">
                        <div class="mt-6 w-full font-bold text-xl text-black px-6">
                            <img class="mx-auto" src="https://static.mod.io/v1/images/home/launch-integrate.svg">
                            Integrate mod.io
                        </div>
                        <p class="text-gray-600 text-base px-6 mb-5">
                            Use our SDKs &amp; plugins so your players can browse &amp; install UGC in-game.
                        </p>
                    </a>
                </div>
                <div class="flex-none mt-auto bg-white rounded-b rounded-t-none overflow-hidden shadow p-6">
                    <div class="flex items-center justify-center">
                        <button class="mx-auto lg:mx-0 hover:underline gradient2 text-white font-extrabold rounded my-6 py-4 px-8 shadow-lg">
                            Action
                        </button>
                    </div>
                </div>
            </div>

            <div class="w-full md:w-1/3 p-6 flex flex-col flex-grow flex-shrink">
                <div class="flex-1 bg-white rounded-t rounded-b-none overflow-hidden shadow">
                    <a href="#" class="flex flex-wrap no-underline hover:no-underline">
                        <div class="mt-6 w-full font-bold text-xl text-black px-6">
                            <img class="mx-auto" src="https://static.mod.io/v1/images/home/launch-grow.svg">
                            Launch community
                        </div>
                        <p class=" text-gray-600 text-base px-6 mb-5">
                            Host, moderate, monetize, brand &amp; grow your creator community with mod.io.
                        </p>
                    </a>
                </div>
                <div class="flex-none mt-auto bg-white rounded-b rounded-t-none overflow-hidden shadow p-6">
                    <div class="flex items-center justify-center">
                        <button class="mx-auto lg:mx-0 hover:underline gradient2 text-white font-extrabold rounded my-6 py-4 px-8 shadow-lg">
                            Action
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!--Footer-->
    <footer class="gradient text-center">
        <div class="container mx-auto mt-8 px-8">
            <div class="w-full flex flex-col md:flex-row py-6">
                <div class="flex-1">
                    <p class="uppercase font-extrabold modio-colour md:mb-6">Explore</p>
                    <ul class="list-reset mb-6">
                        <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                            <a href="#" class="font-light no-underline hover:underline text-white">Games</a>
                        </li>
                        <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                            <a href="#" class="font-light no-underline hover:underline text-white">Mods</a>
                        </li>
                        <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                            <a href="#" class="font-light no-underline hover:underline text-white">Blog</a>
                        </li>
                    </ul>
                </div>
                <div class="flex-1">
                    <p class="uppercase font-extrabold modio-colour md:mb-6">Develop</p>
                    <ul class="list-reset mb-6">
                        <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                            <a href="#" class="font-light no-underline hover:underline text-white">Documentation</a>
                        </li>
                        <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                            <a href="#" class="font-light no-underline hover:underline text-white">Test Environment</a>
                        </li>
                        <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                            <a href="#" class="font-light no-underline hover:underline text-white">SDK & Tools</a>
                        </li>
                    </ul>
                </div>
                <div class="flex-1">
                    <p class="uppercase font-extrabold modio-colour md:mb-6">Social</p>
                    <ul class="list-reset mb-6">
                        <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                            <a href="#" class="font-light no-underline hover:underline text-white">Twitter</a>
                        </li>
                        <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                            <a href="#" class="font-light no-underline hover:underline text-white">Facebook</a>
                        </li>
                        <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                            <a href="#" class="font-light no-underline hover:underline text-white">Discord</a>
                        </li>
                    </ul>
                </div>
                <div class="flex-1">
                    <p class="uppercase font-extrabold modio-colour md:mb-6">
                        Company
                    </p>
                    <ul class="list-reset mb-6">
                        <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                            <a href="#" class="font-light no-underline hover:underline text-white">About Us</a>
                        </li>
                        <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                            <a href="#" class="font-light no-underline hover:underline text-white">Careers</a>
                        </li>
                        <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                            <a href="#" class="font-light no-underline hover:underline text-white">Contact</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</div>
</template>
