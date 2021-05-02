<template>
  <div class="bg-white">
    <Nav />
    <div class="bg-white flex flex-col md:flex-row md:mx-auto md:justify-center md:max-w-screen-xl">
      <div class="p-4 bg-white md:flex-auto space-y-4 md:w-2/3">
        <MyHeader/>
        <my-panel />
        <my-panel />
        <my-panel class="mb-0" />
        <div class="mb-4 flex flex-row flex-nowrap justify-center bg-white text-center">
          <span class="box-border border border-gray-500 border-r-0 px-3 py-1 bg-white cursor-pointer rounded-l-sm hover:bg-gray-300">Older</span>
          <span class="box-border border rounded-r-sm border-gray-500 px-3 py-1 bg-white">Newer</span>
        </div>
      </div>
      <div class="p-4 md:mt-4 md:flex-1 space-y-4">
        <search-panel/>
        <web-panel-info/>
      </div>
    </div>
    <my-footer />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Nav from './components/Nav.vue'
import MyHeader from './components/common/Header.vue'
import MyPanel from './components/common/Panel.vue'
import MyFooter from './components/MyFooter.vue'
import SearchPanel from './components/SearchPanel.vue'
import WebPanelInfo from './components/common/PanelInfo.vue'

export default defineComponent({
  name: 'App',
  components: {
    MyHeader,
    MyPanel,
    MyFooter,
    SearchPanel,
    WebPanelInfo,
    Nav
  }
})
</script>
