<template>
    <section class="section  a">
        <div class="container ">
            <div class="columns is-vcentered is-centered">
                <div class="column is-half">
                    <h1 class="is-size-2 title pb-2">Doe sague, doe vida</h1>
                    <h2 class="is-size-4 subtitle pb-3">Milhares de pessoas precisam dos mais diversos tipos sanguíneos para sua
                        sobrevivência, torne-se um doador e salve vidas!
                    </h2>
                    <button class="button is-medium is-danger is-outlined">Torne-se um doador</button>
                </div>
                <div class="column is-half">
                    <img src="../assets/banner.jpg" class="px-10">
                </div>
            </div>
        </div>
    </section>
</template>
<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({
  name: 'SectionBanner',
});
</script>
<style>
    .b{
        height: 100%;
        width:100%;
        background-color: red;
    }
    .a{background-color: #FAFAFA;}

</style>
