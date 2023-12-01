<template>
    <nav class="header navbar has-shadow">
        <div class="navbar-brand">
          <a class="navbar-item">
            <img src="../assets/logol.png">
          </a>
        </div>
        <div class="navbar-menu" id="nav-links">
          <div class="navbar-end">
            <a class="navbar-item">Home</a>
            <a class="navbar-item">Doe Sangue</a>
            <a class="navbar-item">Dúvidas</a>
            <a class="navbar-item">Sobre nós</a>
            
          </div>
        </div>
    </nav>
</template>
<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HeaderP',
});
</script>
<style>
  .header{
    height: 10vh;
    padding: 0 20px;
  }
</style>
