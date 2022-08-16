<template>
    <div class="programstudi3">
        <div class="info relative">
            <img class="w-full img-fluid absolute" src="../assets/image/Frame 171.svg" alt="Responsive image" />
            <div class="container -pt-20 lg:pt-20 relative">
                <p class="text-black text-base lg:text-2xl pt-5 lg:pt-2 font-semibold">
                    <small>Organisasi SMKN 1 Cibadak</small>
                </p>
                <div class="flex items-center">
                    <h1 class="text-black text-1xl lg:pt-5 pt-3 lg:text-3xl font-bold">
                        Organinsasi
                    </h1>
                    <img class="w-7 lg:w-12 pl-3 lg:pl-5 pt-5 lg:pt-6" src="../assets/image/logoorganisasi.svg"
                        alt="" />
                </div>
                <h1 class="mt-10 lg:mt-28 font-bold text-base lg:text-1xl text-black hover:text-[#949494]">
                    Home&emsp;&ensp;/&emsp;&ensp;Organisasi&emsp;&ensp;/&emsp;&ensp;Dewan
                    Guru
                </h1>
            </div>
        </div>
        <h1 class="text-black text-1xl lg:pt-8 pt-5 mb-6 lg:text-3xl font-bold ml-5 lg:ml-20">
            Dewan Guru
        </h1>

        <div class="mt-5 lg:mt-14 mx-4 lg:mx-20 lg:mb-20">
            <table class="table-auto w-full text-sm lg:text-base font-medium">
                <thead>
                    <tr class="h-10 lg:h-14">
                        <th class="text-white w-14 text-start pl-3 lg:pl-4 bg-[#13A1A1] text-base lg:text-lg">
                            No
                        </th>
                        <th class="text-white text-start bg-[#13A1A1] text-base lg:text-lg pr-20">
                            Nama
                        </th>
                        <th class="text-white text-start bg-[#13A1A1] text-base lg:text-lg">
                            Pendidikan
                        </th>
                        <th class="text-white text-start bg-[#13A1A1] text-base lg:text-lg">
                            Bidang Tugas
                        </th>
                        <th class="bg-[#13A1A1]"></th>
                    </tr>
                </thead>
                <tbody>
                    <tr v-for="(list, index) in listDaftarSiswa" :key="index" class="h-10 lg:h-14">
                        <td class="pl-3 lg:pl-6">{{ index + 1 }}</td>
                        <td class="">{{ list.nama }}</td>
                        <td class="">{{ list.pendidikan }}</td>
                        <td class="">{{ list.bidangtugas }}</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <Footer />
    </div>
</template>

<script>
import Footer from "../components/Footer.vue"
export default {
    components: {
        Footer,
    },



    data() {
        return {
            listDaftarSiswa: [
                {
                    nama: "Drs. Juanda, M.Si",
                    pendidikan: "S2/STIAMI Jakarta/2005",
                    bidangtugas: "Kepala Sekolah, Guru Biologi",
                },
                {
                    nama: "Inda Laela, S.Ag.",
                    pendidikan: "S1/IAIN Sunan Gunung Djati/1988",
                    bidangtugas: "Guru PAI",
                },
                {
                    nama: "Drs. Juanda, M.Si",
                    pendidikan: "S2/STIAMI Jakarta/2005",
                    bidangtugas: "Kepala Sekolah, Guru Biologi",
                },
                {
                    nama: "Inda Laela, S.Ag.",
                    pendidikan: "S1/IAIN Sunan Gunung Djati/1988",
                    bidangtugas: "Guru PAI",
                },
                {
                    nama: "Drs. Juanda, M.Si",
                    pendidikan: "S2/STIAMI Jakarta/2005",
                    bidangtugas: "Kepala Sekolah, Guru Biologi",
                },
                {
                    nama: "Inda Laela, S.Ag.",
                    pendidikan: "S1/IAIN Sunan Gunung Djati/1988",
                    bidangtugas: "Guru PAI",
                },
                {
                    nama: "Drs. Juanda, M.Si",
                    pendidikan: "S2/STIAMI Jakarta/2005",
                    bidangtugas: "Kepala Sekolah, Guru Biologi",
                },
                {
                    nama: "Inda Laela, S.Ag.",
                    pendidikan: "S1/IAIN Sunan Gunung Djati/1988",
                    bidangtugas: "Guru PAI",
                },
                {
                    nama: "Drs. Juanda, M.Si",
                    pendidikan: "S2/STIAMI Jakarta/2005",
                    bidangtugas: "Kepala Sekolah, Guru Biologi",
                },
                {
                    nama: "Inda Laela, S.Ag.",
                    pendidikan: "S1/IAIN Sunan Gunung Djati/1988",
                    bidangtugas: "Guru PAI",
                },
                {
                    nama: "Drs. Juanda, M.Si",
                    pendidikan: "S2/STIAMI Jakarta/2005",
                    bidangtugas: "Kepala Sekolah, Guru Biologi",
                },
                {
                    nama: "Inda Laela, S.Ag.",
                    pendidikan: "S1/IAIN Sunan Gunung Djati/1988",
                    bidangtugas: "Guru PAI",
                },
                {
                    nama: "Drs. Juanda, M.Si",
                    pendidikan: "S2/STIAMI Jakarta/2005",
                    bidangtugas: "Kepala Sekolah, Guru Biologi",
                },
                {
                    nama: "Inda Laela, S.Ag.",
                    pendidikan: "S1/IAIN Sunan Gunung Djati/1988",
                    bidangtugas: "Guru PAI",
                },
                {
                    nama: "Drs. Juanda, M.Si",
                    pendidikan: "S2/STIAMI Jakarta/2005",
                    bidangtugas: "Kepala Sekolah, Guru Biologi",
                },
            ],
        };
    },
};
</script>
<style lang="css" scoped>
table tr {
    @apply bg-[#72DFDF];
}

table tr:nth-child(even) {
    background-color: #edffff !important;
}

table tr:nth-last-child(1) {
    @apply border-b-4 border-[#13A1A1];
}
</style>