<template>
    <div style="border-radius: 10px; " class="max-w-sm rounded overflow-hidden shadow-lg">
  <img class="w-full" src="./assets/IMG_20230316_210509633~3.jpg" alt="Sunset in the mountains">
  <div style="background-color: aliceblue; " class="px-6 py-4">
    <div class="font-bold text-xl mb-2">Dhanak Logo</div>
    <p class="text-gray-700 text-base">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
    </p>
  </div>
  <div style="background-color: aliceblue;" class="px-6 pt-4 pb-2">
    <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#photography</span>
    <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#travel</span>
    <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#winter</span>
  </div>
  </div>
</template>

<script>
export default {
  name: 'BoxCard',
  props: {
    msg: String
  }
}
</script>

<style scoped>

</style>