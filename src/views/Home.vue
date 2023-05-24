<script setup>
import Instagram from "../assets/icons/instagram.vue"
import Facebook from "../assets/icons/facebook.vue"
import Twitter from "../assets/icons/twitter.vue"
import Redo from "../assets/redo.vue"
import Logo from "../assets/logo.vue"
</script>

<template>
    <section class="w-screen h-screen flex flex-col justify-center items-center ">
        <h1 className="lg:text-3xl font-bold underline">
            Confederación Argentina de Judo
        </h1>

        <Logo class="w-60 h-60 mt-16" />

        <h3 class="lg:text-xl mt-24">
            Sitio web bajo mantenimiento...
        </h3>

        <Redo class="w-8 h-8 animate-spin-slow mt-4"/>

        <h3 class="lg:text-xl underline mt-24">
            Redes
        </h3>
        
        <div class="flex space-x-10 mt-4">
            <a href="https://www.instagram.com/" target="_blank" class="w-8 h-8">
                <Instagram class="fill-black hover:fill-red-500 transition-all duration-200"/>
            </a>
            <a href="https://www.facebook.com/" target="_blank" class="w-8 h-8">
                <Facebook class="fill-black hover:fill-red-500 transition-all duration-200"/>
            </a>
            <a href="https://twitter.com/ARG_Judo" target="_blank" class="w-8 h-8">
                <Twitter class="fill-black hover:fill-red-500 transition-all duration-200"/>
            </a>
        </div>
    </section>
</template>

<style scoped></style>
