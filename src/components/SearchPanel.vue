<template>
<div class="box-border border border-gray-500 rounded-md">
  <div class="px-4 py-2 bg-gray-300 text-lg text-left border rounded-t-md border-gray-300">Search</div>
  <div class="px-4 py-2 flex flex-row flex-nowrap justify-center items-center">
    <input type="text" class="px-2 py-1 flex-1 md:auto border rounded-l-sm border-gray-500 border-r-0 outline-none" placeholder="Search for..." />
    <span class="px-2 py-1 bg-gray-800 border border-gray-500 rounded-r-sm text-white cursor-pointer hover:bg-gray-400">GO!</span>
  </div>
</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'SearchPanel',
})
</script>
