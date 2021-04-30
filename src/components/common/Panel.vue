<template>
<div class="m-4 border  border-gray-400 rounded-md shadow-2xl flex flex-col justify-evenly">
  <img class="rounded-t-md" src="https://via.placeholder.com/750x300" alt="">
  <div class="p-5 flex flex-col justify-evenly">
    <h2 class="text-black text-2xl">Post Title</h2>
    <p class="leading-normal mb-2">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis aliquid atque, nulla? Quos cum ex quis soluta, a laboriosam. Dicta expedita corporis animi vero voluptate voluptatibus possimus, veniam magni quis!</p>
    <span class="mt-1 px-3 py-2 w-1/2 bg-blue-600 text-white text-sm text-center rounded-sm">Read More</span>
  </div>
  <div class="px-5 py-3 rounded-b-md border-t-2 border-gray-400 bg-gray-200 text-gray-400 text-sm leading-6">Posted on January 1, 2021 by Start Bootstrap</div>
</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Panel',
})
</script>
