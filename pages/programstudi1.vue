<template>
    <div class="programstudi1">
        <div class="info relative ml-0 lg:ml-2">
            <img class="w-full img-fluid absolute" src="../assets/image/Frame 171.svg" alt="Responsive image" />
            <div class="container -pt-20 lg:pt-20 relative">
                <p class="text-black text-base lg:text-2xl pt-5 lg:pt-2 font-semibold">
                    <small>Jurusan - Jurusan SMKN 1 Cibadak</small>
                </p>
                <div class="flex items-center">
                    <h1 class="text-black text-1xl lg:pt-5 pt-3 lg:text-3xl font-bold">
                        Program Studi
                    </h1>
                    <img class="w-7 lg:w-12 pl-3 lg:pl-5 pt-5 lg:pt-6" src="../assets/image/Vector ps.svg" alt="" />
                </div>
                <h1 class="mt-10 lg:mt-28 font-bold text-base lg:text-1xl text-black hover:text-[#949494]">
                    Home&emsp;&ensp;/&emsp;&ensp;Program Studi
                </h1>
                <h1 class="text-black text-1xl lg:pt-8 pt-5 mb-0 lg:mb-6 lg:text-3xl font-bold">
                    Jurusan - Jurusan di SMKN 1 Cibadak
                </h1>
            </div>
        </div>

        <!-- Jurusan -->
        <section class="overflow-hidden">
            <div class="container flex-col h-full w-full">
                <div class="lg:flex flex-wrap lg-m-1 md:-m-2 pt-5 pb-5">
                    <div class="flex flex-wrap lg:w-1/4">
                        <div class="w-full p-1 md:p-4">
                            <img alt="gallery"
                                class="block object-cover object-center w-full h-full rounded-lg hover:scale-95 lg:hover:scale-110 duration-300 "
                                src="../assets/image/jj1.svg">
                        </div>
                    </div>
                    <div class="flex flex-wrap lg:w-1/4">
                        <div class="w-full p-1 md:p-4">
                            <img alt="gallery"
                                class="block object-cover object-center w-full h-full rounded-lg hover:scale-95 lg:hover:scale-110 duration-300"
                                src="../assets/image/jj2.svg">
                        </div>
                    </div>
                    <div class="flex flex-wrap lg:w-1/4">
                        <div class="w-full p-1 md:p-4">
                            <img alt="gallery"
                                class="block object-cover object-center w-full h-full rounded-lg hover:scale-95 lg:hover:scale-110 duration-300"
                                src="../assets/image/jj3.svg">
                        </div>
                    </div>
                    <div class="flex flex-wrap lg:w-1/4">
                        <div class="w-full p-1 md:p-4">
                            <img alt="gallery"
                                class="block object-cover object-center w-full h-full rounded-lg hover:scale-95 lg:hover:scale-110 duration-300"
                                src="../assets/image/jj4.svg">
                        </div>
                    </div>
                    <div class="flex flex-wrap lg:w-1/4">
                        <div class="w-full p-1 md:p-4">
                            <img alt="gallery"
                                class="block object-cover object-center w-full h-full rounded-lg hover:scale-95 lg:hover:scale-110 duration-300"
                                src="../assets/image/jj5.svg">
                        </div>
                    </div>
                    <div class="flex flex-wrap lg:w-1/4">
                        <div class="w-full p-1 md:p-4">
                            <img alt="gallery"
                                class="block object-cover object-center w-full h-full rounded-lg hover:scale-95 lg:hover:scale-110 duration-300"
                                src="../assets/image/jj6.svg">
                        </div>
                    </div>
                    <div class="flex flex-wrap lg:w-1/4">
                        <div class="w-full p-1 md:p-4">
                            <img alt="gallery"
                                class="block object-cover object-center w-full h-full rounded-lg hover:scale-95 lg:hover:scale-110 duration-300"
                                src="../assets/image/jj7.svg">
                        </div>
                    </div>
                    <div class="flex flex-wrap lg:w-1/4">
                        <div class="w-full p-1 md:p-4">
                            <img alt="gallery"
                                class="block object-cover object-center w-full h-full rounded-lg hover:scale-95 lg:hover:scale-110 duration-300"
                                src="../assets/image/jj8.svg">
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- End Jurusan -->
        <Footer />
    </div>
</template>

<script>
import Footer from "../components/Footer.vue"
export default {
    components: {
        Footer
    }
}
</script>