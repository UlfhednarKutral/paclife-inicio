<template>
    <div class="w-full">
            <div class="absolute mx-auto w-full text-center mt-14 md:mt-24 bansFont md:text-3xl 3xl:text-6xl 3xl:mt-40 4xl:mt-80 4xl:text-8xl" v-html="$t('inicio.bienv')">
            </div>
            <img class="w-3/4 lg:w-4/12 mx-auto z-0 3xl:w-1/2" :src="require('../../assets/paclifeMapa.svg')"/>
            <TextoCirculos
            />

        </div>

</template>

<script>
import TextoCirculos from './svg/TextoCirculos.vue'
export default {

    name: "Mapa",
    components: { 
        TextoCirculos
    }
}
</script>
<style scoped>
    @font-face {
        font-family: Bahns;
        src: url('../../assets/fonts/Bahns.ttf');
    }
    .bansFont{
        font-family: Bahns;
    }
</style>