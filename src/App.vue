<template>
  <main class="">
    <HeaderP/>
    <Main/>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HeaderP from './components/Header.vue';
import Main from './components/Main.vue'

export default defineComponent({
  name: 'App',
  components: {
    HeaderP,
    Main,
  },
});
</script>

<style>
  *{
    padding:0;
    margin:0;
    box-sizing: border-box;
  }
</style>
