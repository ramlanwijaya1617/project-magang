<template>
    <!-- Navbar -->
    <nav
        class="container flex items-center justify-between  lg:bg-transparent bg-[#06918D] lg:absolute lg:left-1/2 -translate-x-1/2 top-0 w-full z-50 py-5 lg:py-10">
        <div class="w-full md:block flex-grow lg:flex lg:items lg:w-auto text-right mr-1">
            <div class="text-sm lg:flex-grow">
                <a v-for="(item, index) in navigations1" :key="index" href="item.link"
                    class="block mt-2 mr-6 lg:inline-block text-gray-100 hover:text-[#33b3b3] lg:mr-10">
                    {{ item.label }}
                    <svg class="ml-1 w-5 h-5" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                            d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                            clip-rule="evenodd"></path>
                    </svg>
                </a>
            </div>
        </div>
        
        <div class="flex items-center text-white">
            <img src="../assets/image/image 111.svg" class="sm:mr-3 ml-10 h-12" alt="SMKN 1 Cibadak" />
            <span class="invisible lg:visible font-semibold text-xl tracking-tight mr-10">SMKN 1 Cibadak</span>
        </div>

        <button class=" focus:outline-none text-white block lg:hidden">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 mr-6 item-bold" viewBox="0 0 24 24"
                stroke="currentColor" strokeWidth={2}>
                <path strokeLinecap="round" strokeLinejoin="round" d="M4 6h16M4 12h16M4 18h16" />
            </svg>
        </button>

        <div class="w-full md:block flex-grow lg:flex lg:items lg:w-auto text-right mr-1">
            <div class="text-sm lg:flex-grow">
                <a v-for="(item, index) in navigations" :key="index" href="item.link"
                    class="block mt-2 mr-6 lg:inline-block text-gray-100 hover:text-[#33b3b3] lg:mr-10">
                    {{ item.label }}
                    <svg class="ml-1 w-5 h-5" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                            d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                            clip-rule="evenodd"></path>
                    </svg>
                </a>
            </div>
        </div>
    </nav>
    <!-- End Navbar -->
</template>

<script>
export default {
    data() {
        return {
            navigations1 : [
                {
                    "label": "Home ",
                    "link": "/Home"
                },
                {
                    "label": "Program Studi",
                    "link": "/Program Studi"
                },
                {
                    "label": "Data Siswa",
                    "link": "/Data Siswa"
                },
            ],
            navigations: [
                {
                    "label": "Organisasi",
                    "link": "/Organisasi"
                },
                {
                    "label": "Info",
                    "link": "/Info"
                },
                {
                    "label": "Berita",
                    "link": "/Berita"
                },
                {
                    "label": "Tentang",
                    "link": "/Tentang"
                },
                {
                    "label": "Kontak",
                    "link": "/Kontak"
                }
            ]
        }
    },
}
</script>

