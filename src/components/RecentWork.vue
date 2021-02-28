<template>
    <section class="py-8 bg-white container mx-auto px-8">
        <div class="text-center mb-8">
            <h1 class="w-full my-2 text-5xl sm:text-2xl font-bold text-gray-700">
                My Recent Work
            </h1>
            <div class="mb-4">
                <div class="h-1 mx-auto bg-pink-500 w-2/3 md:w-1/4 opacity-75 my-0 py-0 rounded"></div>
                <p class="text-lg m-4 text-gray-600">Berikut adalah pekerjaan terbaru saya : </p>
            </div>
            
            <!-- Card Recent Work -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 m-8">
                <div class="bg-white px-4 py-4 m-2 shadow-lg rounded">
                    <img src="../assets/img/1.jpg" alt="" class="w-full rounded-lg">
                    <div class="px-2 py-2 text-center">
                        <p class="font-bold text-xl mb-2 text-gray-700">Sistem Informasi Penelitian</p>
                        <p class="text-gray-700 text-base">Sistem Informasi untuk dosen dan mahasiswa di Universitas XX</p>
                        <div class="px-2 py-4 text-center">
                            <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold px-4 py-2 shadow-md rounded-tr-lg rounded-bl-lg">
                                    Detail
                            </button>
                        </div>
                    </div>
                </div>
                <div class="bg-white px-4 py-4 m-2 shadow-lg rounded">
                    <img src="../assets/img/2.jpg" alt="" class="w-full rounded-lg">
                    <div class="px-2 py-2 text-center">
                        <p class="font-bold text-xl mb-2 text-gray-700">Sistem Informasi Perpustakaan</p>
                        <p class="text-gray-700 text-base">Sistem Informasi Perpustakaan untuk Perpustakaan kota Cirebon</p>
                        <div class="px-2 py-4 text-center">
                            <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold px-4 py-2 shadow-md rounded-tr-lg rounded-bl-lg">
                                    Detail
                            </button>
                        </div>
                    </div>
                </div>
                 <div class="bg-white px-4 py-4 m-2 shadow-lg rounded">
                    <img src="../assets/img/3.jpg" alt="" class="w-full rounded-lg">
                    <div class="px-2 py-2 text-center">
                        <p class="font-bold text-xl mb-2 text-gray-700">Sistem Informasi Keuangan</p>
                        <p class="text-gray-700 text-base">Sistem Informasi Keuangan untuk perusahaan Kota Cirebon</p>
                        <div class="px-2 py-4 text-center">
                            <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold px-4 py-2 shadow-md rounded-tr-lg rounded-bl-lg">
                                    Detail
                            </button>
                        </div>
                    </div>
                </div>
                 <div class="bg-white px-4 py-4 m-2 shadow-lg rounded">
                    <img src="../assets/img/4.jpg" alt="" class="w-full rounded-lg">
                    <div class="px-2 py-2 text-center">
                        <p class="font-bold text-xl mb-2 text-gray-700">Sistem Informasi Asset</p>
                        <p class="text-gray-700 text-base">Sistem Informasi Asset untuk Laboratorium Cirebon</p>
                        <div class="px-2 py-4 text-center">
                            <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold px-4 py-2 shadow-md rounded-tr-lg rounded-bl-lg">
                                    Detail
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "RecentWork"
}
</script>