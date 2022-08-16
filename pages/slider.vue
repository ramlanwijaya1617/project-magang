<template>
    <div class="container mx-auto relative">
        <div class="flex items-center justify-between absolute inset-0 w-full">
            <button @click="showPrev" role="button" aria-label="slide forward" class=" z-30  ml-20 bg-[#32B9B9]"
                id="next">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="white"
                    stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7" />
                </svg>
            </button>

            <button @click="showNext" role="button" aria-label="slide forward" class=" z-30  mr-20 bg-[#32B9B9]"
                id="next">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="white"
                    stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7" />
                </svg>
            </button>
        </div>
        <div class="flex items-center justify-center w-full h-full py-10">
            <div class="slider">
                <div class="slide-ana">
                    <VueSlickCarousel v-bind="settings" ref="carousel">
                        <div class="px-3">
                            <div class="flex flex-nowrap-0 relative w-full sm:w-auto">
                                <img src="../assets/image/slider1.svg" alt="black chair and white table"
                                    class="object-cover object-center w-full rounded-2xl" />
                                <div class="absolute w-full h-full p-6">
                                    <p class="text-base leading-4 lg:leading-5 text-white hover:text-[#67f5f5]">
                                        Pengawasan Mutu
                                        Hasil Pertanian / Agriteknologi Pertanian</p>
                                </div>
                            </div>
                        </div>
                        <div class="px-3">
                            <div class="flex flex-nowrap-0 relative w-full sm:w-auto">
                                <img src="../assets/image/slider2.svg" alt="sitting area"
                                    class="object-cover object-center w-full rounded-2xl" />
                                <div class="absolute w-full h-full p-6">
                                    <p class="text-base leading-4 lg:leading-5 text-white hover:text-[#67f5f5]">
                                        Agribisnis
                                        Pengolahan Hasil Pertanian / Agriteknologi Pertanian</p>
                                </div>
                            </div>
                        </div>
                        <div class="px-3">
                            <div class="flex flex-nowrap-0 relative w-full sm:w-auto">
                                <img src="../assets/image/slider3.svg" alt="sitting area"
                                    class="object-cover object-center w-full rounded-2xl" />
                                <div class="absolute w-full h-full p-6">
                                    <p class="text-base leading-4 lg:leading-5 text-white hover:text-[#67f5f5]">
                                        Agribisnis
                                        Tanaman Pangan dan Holtikultura / Agribisnis Pertanian</p>
                                </div>
                            </div>
                        </div>
                        <div class="px-3">
                            <div class="flex flex-nowrap-0 relative w-full sm:w-auto">
                                <img src="../assets/image/slider4.svg" alt="sitting area"
                                    class="object-cover object-center w-full rounded-2xl" />
                                <div class="absolute w-full h-full p-6">
                                    <p class="text-base leading-4 lg:leading-5 text-white hover:text-[#67f5f5]">
                                        Agribisnis Ternak
                                        Ruminansia / Agribisnis Ternak</p>
                                </div>
                            </div>
                        </div>
                        <div class="px-3">
                            <div class="flex flex-nowrap-0 relative w-full sm:w-auto">
                                <img src="../assets/image/slider5.svg" alt="sitting area"
                                    class="object-cover object-center w-full rounded-2xl" />
                                <div class="absolute w-full h-full p-6">
                                    <p class="text-base leading-4 lg:leading-6 text-white hover:text-[#67f5f5]">
                                        Agribisnis Ternak
                                        Unggas / Agribisnis Ternak</p>
                                </div>
                            </div>
                        </div>
                    </VueSlickCarousel>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
export default {
    name: "MyComponent",
    components: { VueSlickCarousel },
    data() {
        return {
            settings: {
                dots: false,
                infinite: true,
                arrows: false,
                speed: 500,
                slidesToShow: 0,
                slidesToScroll: 1,
                touchThreshold: 5
            },
            windowWidth: window.innerWidth,
        }
    },
    methods: {
        showNext() {
            this.$refs.carousel.next();
        },
        showPrev() {
            this.$refs.carousel.prev();
        },
    },
    mounted() {
        if (this.windowWidth > 1339) {
            this.settings.slidesToShow = 4
        } else if (this.windowWidth > 1079) {
            this.settings.slidesToShow = 4
        } else if (this.windowWidth > 767) {
            this.settings.slidesToShow = 2
        } else {
            this.settings.slidesToShow = 1
        }
    }
};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,400;0,700;0,900;1,400&display=swap');
@import url('https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css');

.slider {
    width: 100%;
    position: relative;
}

.slide-ana {
    height: 100px;
}

.slide-ana>div {
    width: 100%;
    height: 100%;
    position: absolute;
    transition: all 5s;
}

@media (min-width: 300px) and (max-width: 884px) {
    .slider {
        height: 160px;
    }
}

@media (min-width: 768px) and (max-width: 1023px) {
    .slider {
        height: 130px;
    }
}

@media (min-width: 1024px) and (max-width: 1280px) {
    .slider {
        height: 100px;
    }
}

.slider2 {
    width: 100%;
    height: 100px;
    position: relative;
    overflow: hidden;
}

.slide-ana2 {
    height: 100%;
}

.slide-ana2>div {
    width: 100%;
    height: 100%;
    position: absolute;
    transition: all 1s;
}

@media (min-width: 300px) and (max-width: 1023px) {
    .slider2 {
        height: 378px;
    }
}
</style>
