<template>
    <section class="section">
        <div class="container">
            <div class="columns is-flex-wrap-wrap">
                <div class="column is-4">
                    <div class="level">
                        <div class="level-right">
                            <figure class="image is-128x128">
                                <img class="is-rounded" src="../assets/pessoa1.png" alt="">
                            </figure>
                        </div>
                    </div>
                    <h5 class="title is-5">Pedro Daniel (B+)</h5>
                    <p class="subtitle is-6">Código Hemoam: 9933</p>
                    <p>Sofreu um acidente de carro e está em condição grave.</p>
                </div>
                <div class="column is-4">
                    <div class="level">
                        <div class="level-right">
                            <figure class="image is-128x128">
                                <img class="is-rounded" src="../assets/pessoa2.png" alt="">
                            </figure>
                        </div>
                    </div>
                    <h5 class="title is-5">Angelina Cavalcante (A+)</h5>
                    <p class="subtitle is-6">Código Hemoam: 2211</p>
                    <p>Está passando por um processo cirúrgico.</p>
                </div>
                <div class="column is-4">
                    <div class="level">
                        <div class="level-right">
                            <figure class="image is-128x128">
                                <img class="is-rounded" src="../assets/pessoa1.png" alt="">
                            </figure>
                        </div>
                    </div>
                    <h5 class="title is-5">Carlos Eduardo (O+)</h5>
                    <p class="subtitle is-6">Código Hemoam: 3943</p>
                    <p>Perda de sangue devido a uma hemorragia interna.</p>
                </div>
                <div class="column is-4">
                    <div class="level">
                        <div class="level-right">
                            <figure class="image is-128x128">
                                <img class="is-rounded" src="../assets/pessoa2.png" alt="">
                            </figure>
                        </div>
                    </div>
                    <h5 class="title is-5">Fernanda Souza (B-)</h5>
                    <p class="subtitle is-6">Código Hemoam: 2044</p>
                    <p>Transplante de coração.</p>
                </div>
            </div>

        </div>

       

    </section>
</template>
    
<script lang="ts">
import { defineComponent } from 'vue';


export default defineComponent({
    name: 'SectionPessoas',
});
</script>
    
<style>
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
</style>
    