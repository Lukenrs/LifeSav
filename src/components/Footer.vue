<template>
   <footer class="c footer">
  <div class="content has-text-centered">
    <p>
      Todos os direitos reservados LifeSaver@2023
    </p>
  </div>
</footer>
</template>
<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Footer',
});
</script>
<style>
  .header{
    height: 10vh;
    padding: 0 20px;
  }
  .c{
    background-color: white;
    height: 2vh;
  }
</style>
