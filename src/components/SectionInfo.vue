<template>
  <section class="a section">
    <div class="container">
      <div class="columns is-flex-direction-column is-vcentered is-centered">
        <h1 class="title pb-4">Dúvidas</h1>
        <div class="columns is-flex-direction-column is-vcentered is-centered">
          <article class="message is-info">
            <div class="message-header">
              <p>Quanto tempo demoro pra doar sangue?</p>
            </div>
            <div class="message-body">
              O processo de doação de sangue geralmente leva de 10 a 15 minutos, mas o tempo total que você passará no
              local de doação pode ser cerca deu ma hora, incluindo o registro e a triagem médica.
            </div>
          </article>
          <article class="message is-info">
            <div class="message-header">
              <p>Preciso estar em jejum para doar?</p>
            </div>
            <div class="message-body">
              Não é necessário estar em jejum antes de doar sangue. No entanto, é aconselhável comer uma refeição leve e
              balanceada nas horas que antecedem a doação. Esse tipo de refeição ajuda o doador a não desmaiar durante a extração do sangue.
            </div>
          </article>
          <article class="message is-info">
            <div class="message-header">
              <p>Posso doar sangue gripado?</p>
            </div>
            <div class="message-body">
              Se você estiver doente, com febre ou infecções ativas, é melhor adiar a doação até estar completamente
              recuperado. Isso ajuda a evitar a transmissão de infecções e etc. Foque na sua recuperação e após isso, estará disposto para a doação.
            </div>
          </article>

        </div>

      </div>

    </div>

  </section>
</template>
  
<script lang="ts">
import { defineComponent } from 'vue';


export default defineComponent({
  name: 'SectionInfo',
});
</script>
  
<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
.a{background-color: #FAFAFA;}
</style>
  