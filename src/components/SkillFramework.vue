<template>
    <section class="w-screen mx-auto mb-10 py-4 bg-white px-4">
        <div class="flex flex-wrap">
            <div class="w-full mt-20 md:w-4/12 ml-auto mr-auto px-4">
                <img src="../assets/img/skill-framework.jpg" class="max-w-full rounded-xl shadow-lg" alt="Wkwkw">
            </div>
            <div class="w-full md:w-5/12 ml-auto mr-auto px-4 bg-white">
                <div class="md:pr-12">
                    <h1 class="w-full my-2 md:text-2xl sm:text-2xl text-5xl font-bold text-center text-gray-700">Skill Framework</h1>
                    <div class="mb-4">
                      <div class="h-1 mx-auto bg-pink-500 w-2/3 opacity-75 my-0 mx-0 rounded"></div>
                    </div>
                    <p class="mt-4 text-lg text-gray-600">
                        Berikut adalah item dan skala keahlian untuk framework :
                    </p>
                    <ul class="list-none mt-4">
                        <li class="grid grid-cols-2 py-2">
                            <p class="text-lg text-gray-600">Express</p>
                            <div class="w-7/8 rounded-md bg-gradient-to-r from-green-400 to-blue-500"></div>
                        </li>
                        <li class="grid grid-cols-2 py-2">
                            <p class="text-lg text-gray-600">Vue</p>
                            <div class="w-3/4 rounded-md bg-gradient-to-r from-green-400 to-blue-500"></div>
                        </li>
                        <li class="grid grid-cols-2 py-2">
                            <p class="text-lg text-gray-600">Tailwindcss</p>
                            <div class="w-2/3 rounded-md bg-gradient-to-r from-green-400 to-blue-500"></div>
                        </li>
                        <li class="grid grid-cols-2 py-2">
                            <p class="text-lg text-gray-600">Docker</p>
                            <div class="w-1/2 rounded-md bg-gradient-to-r from-green-400 to-blue-500"></div>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "SkillFramework"
}
</script>