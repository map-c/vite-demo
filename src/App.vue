<template>
  <div class="bg-white">
    <Nav />
    <MyHeader/>
    <my-panel />
    <my-panel />
    <my-panel />
    <p>test</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Nav from './components/Nav.vue'
import MyHeader from './components/common/Header.vue'
import MyPanel from './components/common/Panel.vue'

export default defineComponent({
  name: 'App',
  components: {
    MyHeader,
    MyPanel,
    Nav
  }
})
</script>
