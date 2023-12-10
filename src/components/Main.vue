<template>
   <SectionBanner/>
   <SectionPessoas/>
   <SectionInfo/>
</template>
<script lang="ts">
import { defineComponent } from 'vue';
import SectionBanner from './SectionBanner.vue';
import SectionInfo from './SectionInfo.vue'
import SectionPessoas from './SectionPessoas.vue';
export default defineComponent({
  name: 'Main',
  components:{
    SectionBanner,
    SectionInfo,
    SectionPessoas,
  }
});
</script>
<style>

</style>
