<template>
  <v-content class="green accent-4" :height="500">
    <h1 class="py-5 pb-10 white--text font-weight-medium" align="center">Nossos Serviços</h1>

<!-- TODAS AS 4 COLUNAS COM AS 4 CARDS   -->
    <v-row justify="center" class="pb-10 mb-10">

<!-- PRIMEIRO CARD -->
      <v-col class="col-12 col-md-2">
        <v-card class="mx-auto pt-1 round" hover>
          <v-img aspect-ratio="1.7" contain src="../assets/sis_web.png" height="200px"></v-img>

          <v-card-title>
            <p>Sistemas WEB</p>
          </v-card-title>

          <v-card-actions>
            <v-btn text color="green">Descubra</v-btn>

            <div class="flex-grow-1"></div>

            <v-btn icon @click="show_1 = !show_1">
              <v-icon>{{ show_1 ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show_1">
              <v-card-text>Soluções inteligentes para faclitar o cotidiano das empresas, com o objetivo de reduzir custos e otimizar processos.</v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
      </v-col>

<!-- SEGUNDA CARD       -->
      <v-col class="col-12 col-md-2">
        <v-card class="mx-auto pt-1 round" hover>
          <v-img aspect-ratio="1.7" contain src="../assets/sis_web.png" height="200px"></v-img>

          <v-card-title>
            <p>Sistemas Desktops</p>
          </v-card-title>

          <v-card-actions>
            <v-btn text color="green">Descubra</v-btn>

            <div class="flex-grow-1"></div>

            <v-btn icon @click="show_2 = !show_2">
              <v-icon>{{ show_2 ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show_2">
              <v-card-text>Soluções inteligentes para faclitar o cotidiano das empresas, com o objetivo de reduzir custos e otimizar processos.</v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
      </v-col>

<!-- TERCEIRA CARD       -->
      <v-col class="col-12 col-md-2">
        <v-card class="mx-auto pt-1 round" hover>
          <v-img aspect-ratio="1.7" contain src="../assets/Mobile.png" height="200px"></v-img>

          <v-card-title>
            <p>Aplicativos</p>
          </v-card-title>

          <v-card-actions>
            <v-btn text color="green">Descubra</v-btn>

            <div class="flex-grow-1"></div>

            <v-btn icon @click="show_3 = !show_3">
              <v-icon>{{ show_3 ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show_3">
              <v-card-text>Produção de aplicativos que permitem a integração com sistemas web facilitando o contato direto com o cliente.</v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
      </v-col>

<!-- QUARTA CARD       -->
      <v-col class="col-12 col-md-2">
        <v-card class="mx-auto pt-1 round" hover>
          <v-img aspect-ratio="1.7" contain src="../assets/ecom.png" height="200px"></v-img>
          <v-card-title>
            <p>Sites</p>
          </v-card-title>

          <v-card-actions>
            <v-btn text color="green">Descubra</v-btn>

            <div class="flex-grow-1"></div>

            <v-btn icon @click="show_4 = !show_4">
              <v-icon>{{ show_4 ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-expand-transition>
            <div v-show="show_4">
              <v-card-text>Desenvolvimento de sites para todos os negócios, com design responsivo para dispositivos móveis.</v-card-text>
            </div>
          </v-expand-transition>
        </v-card>
      </v-col>

    </v-row>
<!-- FIM DAS 4 COLUNAS -->

  </v-content>
</template>

<script>
export default {
  data: () => ({
    show_1: false,
    show_2: false,
    show_3: false,
    show_4: false,
  })
};
</script>

<style>
.round {
    border-radius: 20px;
}

</style>