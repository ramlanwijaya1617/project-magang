<template>
    <div class="datasiswa">
        <div class="flex-wrap grid grid-cols-2 info relative">
            <img class="w-full absolute" src="../assets/image/Frame 171.svg" alt="" />
            <div class="container -pt-20 lg:pt-16 relative">
                <p class="text-black text-base lg:text-2xl pt-5 lg:pt-2 font-semibold relative">
                    <small>Data Siswa SMKN 1 Cibadak</small>
                </p>
                <div class="flex items-center">
                    <h1 class="text-black text-1xl lg:pt-5 pt-3 lg:text-3xl font-bold">
                        Data Siswa
                    </h1>
                    <img class="w-7 lg:w-12 pl-3 lg:pl-5 pt-5 lg:pt-6" src="../assets/image/datasiswa.svg" alt="" />
                </div>
            </div>
            <div class="container">
                <h1 class="text-black text-sm lg:text-2xl font-bold relative lg:py-24 py-10 ml-16 lg:ml-24">
                    Agribisnis Hasil Pertania ( X.A.3 )
                </h1>
            </div>
        </div>
        <h1 class="mx-5 lg:mx-20 mt-5 md:mt-10 lg:mt-16 font-bold text-sm lg:text-base text-black hover:text-[#949494]">
            Home&emsp;&ensp;/&emsp;&ensp;Data Siswa&emsp;&ensp;/&emsp;&ensp;AGRIBISNIS
            HASIL PERTANIAN &emsp;&ensp;/&emsp;&ensp; X A 3X
        </h1>
        <h1 class="text-black text-1xl lg:pt-8 pt-5 mb-6 lg:text-3xl font-bold ml-5 lg:ml-20">
            Data kelas X A3
        </h1>

        <div class="mt-5 lg:mt-7 mx-10 lg:mx-20">
            <table class="table-auto w-full text-sm lg:text-base font-medium">
                <tbody>
                    <tr class="h-10 lg:h-14 text-base lg:text-xl text-white">
                        <td class="w-10 lg:w-20 text-start pl-3 lg:pl-4 bg-[#13A1A1]">
                            No
                        </td>
                        <td class="bg-[#13A1A1]">NIS</td>
                        <td class="bg-[#13A1A1]">Nama Siswa</td>
                        <td class="bg-[#13A1A1]">Jenis Kelamin</td>
                    </tr>
                    <tr v-for="(list, index) in listDaftarSiswa" :key="index" class="h-10 lg:h-14">
                        <td class="pl-3 lg:pl-6">{{ index + 1 }}</td>
                        <td class="">{{ list.nis }}</td>
                        <td class="">{{ list.nama }}</td>
                        <td class="">{{ list.jenisKelamin }}</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <Footer />
    </div>
</template>
<script>
import Footer from "../components/Footer.vue";
export default {
    components: {
        Footer,
    },

    data() {
        return {
            listDaftarSiswa: [
                {
                    nis: "10151609857",
                    nama: "AA Faisal Abdullah",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609858",
                    nama: "Ai Nuraeni",
                    jenisKelamin: "P",
                },
                {
                    nis: "10151609859",
                    nama: "Andhika Pratama",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609862",
                    nama: "Dian Angraeni Putri",
                    jenisKelamin: "P",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
                },
                {
                    nis: "10151609861",
                    nama: "Daudy Sultan Syahbian",
                    jenisKelamin: "L",
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
