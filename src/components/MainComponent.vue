<template>
    <!-- This example requires Tailwind CSS v2.0+ -->
    <div class="flex flex-col md:flex-row my-3">
        <div id="intro" class="order-last md:order-first">
            <h1 class="text-4xl font-bold mb-2">Achmad Fadhil</h1>
            <h3 class="text-xl mb-4">Web Developer</h3>
            <p class="text-gray-400">Passionate web developer that mainly focuses on developing a sustainable web application in order to support the business process carried by the company.</p>

            <div class="mt-8">
                <a href="https://wa.me/6282251369305" class="inline-flex items-center py-2 px-3 text-sm font-medium text-center text-white bg-blue-600 rounded-lg hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800 mr-5" target="_blank">Contact Me <i class="uil uil-whatsapp ml-1"></i> </a>
            </div>
        </div>

        <div id="photo" class="order-1">
            <svg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg" class="w-full">
                <mask id="mask0" mask-type="alpha">
                    <path fill="#BAE6FF" d="M40.1,-71.3C47.6,-65.1,46.4,-45.6,54.3,-31.5C62.3,-17.4,79.3,-8.7,79.5,0.1C79.6,8.9,62.9,17.8,52.2,27.1C41.6,36.4,36.9,46.1,29.2,52.5C21.5,58.9,10.7,62.1,-1.4,64.6C-13.6,67.1,-27.2,68.9,-34.6,62.3C-42,55.7,-43.1,40.6,-49.4,28.8C-55.7,17.1,-67,8.5,-70.3,-1.9C-73.5,-12.2,-68.6,-24.5,-60.2,-32.6C-51.8,-40.8,-40,-44.8,-29.4,-49.3C-18.8,-53.7,-9.4,-58.5,3.4,-64.5C16.3,-70.4,32.5,-77.5,40.1,-71.3Z" transform="translate(100 100)" />
                </mask>
                <g mask="url(#mask0)">
                    <path d="M40.1,-71.3C47.6,-65.1,46.4,-45.6,54.3,-31.5C62.3,-17.4,79.3,-8.7,79.5,0.1C79.6,8.9,62.9,17.8,52.2,27.1C41.6,36.4,36.9,46.1,29.2,52.5C21.5,58.9,10.7,62.1,-1.4,64.6C-13.6,67.1,-27.2,68.9,-34.6,62.3C-42,55.7,-43.1,40.6,-49.4,28.8C-55.7,17.1,-67,8.5,-70.3,-1.9C-73.5,-12.2,-68.6,-24.5,-60.2,-32.6C-51.8,-40.8,-40,-44.8,-29.4,-49.3C-18.8,-53.7,-9.4,-58.5,3.4,-64.5C16.3,-70.4,32.5,-77.5,40.1,-71.3Z" transform="translate(100 100)" />
                    <image id="profilPic" x="18" y="10" :xlink:href="profpic"/>
                </g>
            </svg>
        </div>
    </div>

    <div></div>


</template>

<script>
import profilpic from '../assets/pp.jpeg'

export default {
  name: 'MainComponent',
  data: () => {
      return {
          profpic: profilpic
      }
  }
}
</script>

<style scoped>
    #profilPic{
        width: 170px;
    }
</style>