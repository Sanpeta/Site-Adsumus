<template>
  <v-content class="white">
    <h1 class="black-text mt-5" align="center">QUEM SOMOS</h1>
    <v-row class="mb-10" align="center" justify="center">
      <v-col class="col-md-5 col-12">
        <p
          class="pr-10 text-justify display-1 font-weight-medium"
        >Startup de soluções tecnológicas focada no desenvolvimento de sistemas personalizados. A Adsumus está habilitada a atender os mais diversos processos das empresas, automatizando tarefas rotineiras de forma integrada através de sistemas desktops, plataformas web, aplicativos e sites.</p>
      </v-col>
      
      <v-col class="col-md-5 col-12">
        <v-img class="pl-10">
          <v-row align="center" justify="center">
            <v-img
              src="../assets/somos.jpeg"                          
            ></v-img>
          </v-row>
        </v-img>
      </v-col>
    </v-row>
  </v-content>
</template>

<script>
export default {
  data() {
    return {
      altura: screen.height
    }    
  }
}
</script>