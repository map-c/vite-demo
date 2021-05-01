<template>
  <nav class="w-auto py-2 px-4 bg-gray-700 text-white">
    <div class="flex flex-row justify-between p-2">
      <span class="text-white">Riverside</span>
      <span class="text-current cursor-pointer select-none" @click="handleShowNav">Menu</span>
    </div>
    <ul class="w-auto transition-all" v-show="showNav">
      <li :class="['p-2', 'text-gray-50', 'select-none', 'cursor-pointer', 'active:bg-white']">Home</li>
      <li class="p-2 text-gray-50 text-opacity-40 select-none cursor-pointer active:bg-gray-50 active:text-black">Service</li>
      <li class="p-2 text-gray-50 text-opacity-40 select-none cursor-pointer">Contact</li>
      <li class="p-2 text-gray-50 text-opacity-40 select-none cursor-pointer">About</li>
    </ul>
  </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Nav',
  data () {
    return {
      showNav: false
    }
  },
  methods: {
    handleShowNav () {
      this.showNav = !this.showNav
    }
  }
})
</script>

