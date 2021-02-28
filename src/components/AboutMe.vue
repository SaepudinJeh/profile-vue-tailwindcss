<template>
  <section class="w-screen mx-auto px-auto py-4 bg-gradient-to-r from-green-400 to-blue-500">
    <div class="px-16 py-8">
      <h1 class="w-full text-5xl sm:text-2xl font-bold text-center text-white">About Me</h1>
      <div class="mb-4">
        <div
          class="bg-pink-500 w-2/3 md:w-1/6 opacity-72 rounded h-1 mx-auto"
        ></div>
      </div>
      <h2 class="text-3x2 font-bold mb-2 text-white text-center">
        Hay, Saya Agung. Senang berjumpa dengan Anda
      </h2>

      <h3 class="text-lg mb-2 text-white text-center mb-5">
        Saya seorang programmer dan graphic desainer, selain dapat membuat
        aplikasi menggunakan pemograman. Saya juga dapat merancang suatu sistem
        yang dibutuhkan user.
      </h3>

      <!-- Foto Profile -->
      <div class="w-full">
        <div class="px-4 py4">
          <img
            class="shadow-lg rounded-full max-w-full mx-auto text-center w-48"
            src="../assets/img/profile.jpg"
            alt=""
          />
        </div>
      </div>

      <!-- About Skill -->
      <div class="grid grid-cols-1 md:grid-cols-3 bg-white py-4 px-4 md:py-8 md:px-8 m-16 rounded-lg">
        <div class="max-w-sm shadow-lg px-4 py-4 bg-white m-3 text-center">
          <i class="fas fa-laptop-code fa-5x text-blue-500 mb-6 h-8"></i>
          <p class="font-bold text-xl md:text-base mb-6 mt-5 md:mb-2">
            Programming
          </p>
          <div class="p-4">
            <p class="text-gray-600 text-base mb-2">PHP</p>
            <hr class="text-gray-600 mb-2" />
            <p class="text-gray-600 text-base mb-2">.NET</p>
            <hr class="text-gray-600 mb-2" />
            <p class="text-gray-600 text-base mb-2">C++</p>
            <hr class="text-gray-600 mb-2" />
            <p class="text-gray-600 text-base mb-2">Java</p>
            <hr class="text-gray-600 mb-2" />
          </div>
          <div class="px-2 py-4">
            <button
              class="bg-blue-500 hover:bg-blue-700 text-white font-bold px-4 py-2 shadow-md rounded-tl-lg rounded-br-lg md:text-sm"
            >
              Lihat Portofolio
            </button>
          </div>
        </div>

        <!-- Card 2 -->
        <div class="max-w-sm shadow-lg px-4 py-4 bg-white m-3 text-center">
          <i class="fas fa-pencil-ruler fa-5x text-red-500 mb-6 h-8"></i>
          <p class="font-bold text-xl md:text-base mb-6 mt-5 md:mb-2">
            Design
          </p>
          <div class="p-4">
            <p class="text-gray-600 text-base mb-2">Figma</p>
            <hr class="text-gray-600 mb-2" />
            <p class="text-gray-600 text-base mb-2">Photoshop</p>
            <hr class="text-gray-600 mb-2" />
            <p class="text-gray-600 text-base mb-2">Ilustrator</p>
            <hr class="text-gray-600 mb-2" />
            <p class="text-gray-600 text-base mb-2">Adobe XD</p>
            <hr class="text-gray-600 mb-2" />
          </div>
          <div class="px-2 py-4">
            <button
              class="bg-blue-500 hover:bg-blue-700 text-white font-bold px-4 py-2 shadow-md rounded-tl-lg rounded-br-lg md:text-sm"
            >
              Lihat Portofolio
            </button>
          </div>
        </div>

        <!-- Card 3 -->
        <div class="max-w-sm shadow-lg px-4 py-4 bg-white m-3 text-center">
          <i class="fas fa-database fa-5x text-green-500 mb-6 h-8"></i>
          <p class="font-bold text-xl md:text-base mb-6 mt-5 md:mb-2">
            Database
          </p>
          <div class="p-4">
            <p class="text-gray-600 text-base mb-2">MongoDB</p>
            <hr class="text-gray-600 mb-2" />
            <p class="text-gray-600 text-base mb-2">Redis</p>
            <hr class="text-gray-600 mb-2" />
            <p class="text-gray-600 text-base mb-2">MySQL</p>
            <hr class="text-gray-600 mb-2" />
            <p class="text-gray-600 text-base mb-2">IndexedDB</p>
            <hr class="text-gray-600 mb-2" />
          </div>
          <div class="px-2 py-4">
            <button
              class="bg-blue-500 hover:bg-blue-700 text-white font-bold px-4 py-2 shadow-md rounded-tl-lg rounded-br-lg md:text-sm"
            >
              Lihat Portofolio
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AboutMe",
};
</script>