<template>
  <div>
    <v-toolbar color="black">

    <v-img
      src="../assets/adsumus.png"
      aspect-ratio="1"
      max-width="40"
      max-height="40"
    ></v-img>

      <v-toolbar-title class="px-5 white--text font-weight-bold col-md-4 col-12">ADSUMUS</v-toolbar-title>

      <div class="flex-grow-1"></div>

      <v-toolbar-items class="col-xs-8">
        <v-btn text class="white--text font-weight-medium" to="/">Início</v-btn>
        <v-btn text class="white--text font-weight-medium" to="/sobre">Sobre Nós</v-btn>
        <v-btn text class="white--text font-weight-medium" to="/servicos">Nossos Serviços</v-btn>
        <v-btn text class="white--text font-weight-medium" to="/contato">Contato</v-btn>
      </v-toolbar-items>

    </v-toolbar>
  </div>
</template>