<template>
    <div class="">
        <div class="info relative">
            <img class="w-full img-fluid absolute" src="../assets/image/Frame 171.svg" alt="Responsive image" />
            <div class="container -pt-20 lg:pt-20 relative">
                <p class="text-black text-base lg:text-2xl pt-5 lg:pt-2 font-semibold">
                    <small>Tunggu informasi terkini sebagai siswa</small>
                </p>
                <div class="flex items-center">
                    <h1 class="text-black text-1xl lg:pt-5 pt-3 lg:text-3xl font-bold">
                        Informasi
                    </h1>
                    <img class="w-7 lg:w-12 pl-3 lg:pl-5 pt-5 lg:pt-6" src="../assets/image/Vector informasi.svg"
                        alt="" />
                </div>
                <h1 class="mt-16 lg:mt-28 font-bold text-base lg:text-1xl text-black hover:text-[#949494]">
                    Home&emsp;&ensp;/&emsp;&ensp;Informasi
                </h1>
            </div>
        </div>
        <div class="container pt-10">
            <div class="flex flex-wrap items-center">
                <div class="w-full md:w-1/2">
                    <div class="flex gap-10">
                        <h1 class=" font-bold text-base lg:text-xl">
                            Kategori
                        </h1>

                        <button
                            class="bg-[#32B9B9] text-white hover:bg-[#1f6463] text-base font-bold py-2 px-4 mr-auto flex rounded-3xl">
                            Semua Informasi
                            <div class="ml-2">
                                <svg width="24" height="24" viewBox="0 0 25 25" fill="none"
                                    xmlns="http://www.w3.org/2000/svg">
                                    <path
                                        d="M6.34317 7.75732L4.92896 9.17154L12 16.2426L19.0711 9.17157L17.6569 7.75735L12 13.4142L6.34317 7.75732Z"
                                        fill="currentColor" />
                                </svg>
                            </div>
                        </button>
                    </div>
                </div>

                <!-- Search -->
                <div class="w-full md:w-1/2">
                    <div class="flex justify-end">
                        <input type="text"
                            class="outline-none px-2 lg:px-4 py-2 bg-[#F5F5F5] hover:bg-[#ebe9e9] rounded-l-lg"
                            placeholder="Search..." />
                        <button class="px-2 lg:px-3 items bg-[#F5F5F5] hover:bg-[#ebe9e9] rounded-r-lg">
                            <svg class="w-5 h-5 lg:w-6 lg:h-6 text-t [#d4cece]" fill="currentColor">
                                <path
                                    d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z" />
                                <path />
                            </svg>
                        </button>
                    </div>
                </div>
            </div>
            <!-- End Search -->
            <div>
                <h1 class="mt-5 lg:mt-10 font-bold text-base lg:text-xl">
                    Hot news
                </h1>
            </div>

            <div class="flex justify-center lg:mt-10 mb-6 bg-[#F5F5F5] rounded-lg">
                <div class="flex flex-col md:flex-row">
                    <div class="p-6 flex flex-col justify-start mt-10">
                        <h5
                            class="text-black text-xl lg:text-2xl font-semibold lg:font-bold mb-10 hover:text-[#33b3b3]">
                            Cargo Udara Sebagai Lorem ipsum dolor sit amet, consectetur
                        </h5>
                        <p class="text-[#646464] text-xl lg:text-1xl -mb-2 lg:mb-4 text-justify">
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc maximus dolor nulla, vel
                            iaculis felis suscipit vitae. Donec imperdiet ex sed tortor aliquam congue. Pellentesque at
                            luctus nulla, at ultricies dolor.
                        </p>
                        <div class="flex justify-between text-sm text-[#969696] mt-16">
                            <p>1, Mar 2021</p>
                            <p>Admin</p>
                        </div>
                    </div>
                    <img class=" hover:animate-pulse" src="../assets/image/unsplash_berita.svg" alt="" />
                </div>
            </div>

            <div>
                <h1 class="mt-5 lg:mt-10 pb-5 lg:pb-0 pt-3 ml-6 lg:ml-24 font-bold text-base lg:text-xl">
                    Berita Sekolah
                </h1>
            </div>

            <div class="flex">
                <div class="flex flex-col lg:py-10 w-2/3">
                    <div class="grid grid-cols-2 gap-2 pb-7">
                        <div v-for="n in 6" :key="n" class="lg:max-w-sm rounded overflow-hidden row lg:pr-5">
                            <img class="w-96 lg:h-64 hover:animate-pulse" src="../assets/image/berita 6.svg" alt="" />
                            <div class="px-auto lg:py-4 text-justify">
                                <div class="font-semibold lg:font-bold lg:text-2xl text-xl mb-2 hover:text-[#33b3b3]">
                                    Belajar Dirumah
                                </div>
                                <p class="text-[#969696] text-base lg:text-xl text-left">
                                    Lorem ipsum dolor sit amet, consectetur Maecenas et velit sem.
                                    Sambutan Kepala Sekolah SMP Negeri 1 Cibadak
                                </p>
                                <p class="text-sm text-end [#3b3a3a] pt-3 hover:text-[#969696]">
                                    20 Juni 2022
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="container">
                        <button
                            class="bg-[#06918D] text-white hover:bg-[#1f6463] text-base font-bold py-2 lg:py-2.5 px-2 lg:px-8 flex mx-auto pb-3">
                            Load more
                        </button>
                    </div>
                </div>

                <div class="W-1/3 lg:ml-5 lg:mt-4 -mt-7 ml-8">
                    <h1 class=" font-bold text-base lg:text-xl">
                        Umum
                    </h1>
                    <div class="flex flex-col md:flex-row rounded justify-between mt-4">
                        <img class="w-24 h-20 lg:w-40 lg:h-32 hover:animate-pulse" src="../assets/image/mobil.svg"
                            alt="" />
                        <div class="ml-2 py-2 justify-between">
                            <p class="text-black text-xs lg:text-sm lg:ml-1 sm:-ml-2">
                                Lorem ipsum dolor sit amet,<br> consectetur adipiscing elit. <br>Sed
                                vitae enim
                            </p>
                            <div class="flex justify-between text-sm text-[#747272] mt-3 lg:ml-2 sm:-ml-2">
                                <p>Admin</p>
                                <p>1 jan, 2021</p>
                            </div>
                        </div>
                    </div>

                    <div class="flex flex-col md:flex-row rounded justify-between mt-3">
                        <img class="w-24 h-20 lg:w-40 lg:h-32 hover:animate-pulse" src="../assets/image/gambar2.svg"
                            alt="" />
                        <div class="ml-2 py-2 justify-between">
                            <p class="text-black text-xs lg:text-sm lg:ml-1 sm:-ml-2">
                                Lorem ipsum dolor sit amet,<br>consectetur adipiscing elit. <br>Sed
                                vitae enim
                            </p>
                            <div class="flex justify-between text-sm text-[#747272] mt-3 lg:ml-2 sm:-ml-2">
                                <p>Admin</p>
                                <p>23 Mar, 2021</p>
                            </div>
                        </div>
                    </div>

                    <div class="flex flex-col md:flex-row rounded justify-between mt-3">
                        <img class="w-24 h-20 lg:w-40 lg:h-32 hover:animate-pulse" src="../assets/image/gambar 3.svg"
                            alt="" />
                        <div class="ml-2 py-2 justify-between">
                            <p class="text-black text-xs lg:text-sm lg:ml-1 sm:-ml-2">
                                Lorem ipsum dolor sit amet,<br>consectetur adipiscing elit. <br>Sed
                                vitae enim
                            </p>
                            <div class="flex justify-between text-sm text-[#747272] mt-3 lg:ml-2 sm:-ml-2">
                                <p>Admin</p>
                                <p>13 Mar, 2021</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>


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