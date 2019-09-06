<template>
  <v-content class="black">
    <v-img src="https://media.giphy.com/media/dsto7xQFDnMRDU7UWz/giphy.gif" max-height="500">
      <h1 v-if="largura > 420" class="white--text my-5 pt-5 fonte-ajustada-title" align="center">Sobre Nós</h1>
      <h1 v-else class="white--text my-5 pt-5 fonte-ajustada-title-2" align="center">Sobre Nós</h1>
      <v-row class="mb-10" align="center" justify="center">
        <v-col class="col-md-6 col-12">
          <p v-if="largura > 420"
            class="text-center font-weight-light white--text fonte-ajustada"
          >Startup de soluções tecnológicas focada no desenvolvimento de sistemas personalizados. A Adsumus está habilitada a atender os mais diversos processos das empresas, automatizando tarefas rotineiras de forma integrada através de sistemas desktops, plataformas web, aplicativos e sites.</p>
          <p v-else class="text-center font-weight-light white--text fonte-ajustada-2"
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
      altura: screen.height,
      largura: screen.width
    };
  },
};
</script>

<style>
.fonte-ajustada-title {
  font-size: 300%;
}
.fonte-ajustada {
  font-size: 170%;
}
.fonte-ajustada-title-2 {
  font-size: 150%;
}
.fonte-ajustada-2 {
  font-size: 100%;
}
</style>