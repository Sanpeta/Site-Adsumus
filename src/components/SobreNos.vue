<template>
  <v-content class="black">
    <v-img src="https://media.giphy.com/media/dsto7xQFDnMRDU7UWz/giphy.gif" max-height="550">
    <h1 class="white--text my-10 pt-5 fonte-ajustada-title" align="center">Sobre Nós</h1>
    <v-row class="mb-10" align="center" justify="center">
      <v-col class="col-md-5 col-12">
        <p
          class="text-center font-weight-light white--text fonte-ajustada"
        >Startup de soluções tecnológicas focada no desenvolvimento de sistemas personalizados. A Adsumus está habilitada a atender os mais diversos processos das empresas, automatizando tarefas rotineiras de forma integrada através de sistemas desktops, plataformas web, aplicativos e sites.</p>
      </v-col>
    </v-row>
    </v-img>
  </v-content>
</template>

<script>
export default {
  data() {
    return {
      altura: screen.height
    };
  }
};
</script>

<style>
.fonte-ajustada {
  font-size: 200%;
}
.fonte-ajustada-title {
  font-size: 300%;
}
</style>