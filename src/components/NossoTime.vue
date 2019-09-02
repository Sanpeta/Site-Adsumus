<template>
  <v-content class="white pb-10">
    <h1 class="black-text mt-5" align="center">
      Time
      <span class="green--text">Adsumus</span>
    </h1>
    <v-row class="mb-10" align="center" justify="center">
      <v-col class="col-md-2 col-12">
        <v-card
          class="mx-auto"
          :flat="flat"
          :loading="loading"
          :outlined="outlined"
          :elevation="elevation"
          :raised="raised"
          :width="width"
          :height="height"
        >
          <v-card-text>I'm card text</v-card-text>
          <v-card-actions v-if="actions">
            <v-btn icon>
              <v-icon>mdi-heart</v-icon>
            </v-btn>
            <v-btn text>Click</v-btn>
            <v-btn outlined>Click</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>

      <v-col class="col-md-2 col-12">
        <v-card
          class="mx-auto"
          :flat="flat"
          :loading="loading"
          :outlined="outlined"
          :elevation="elevation"
          :raised="raised"
          :width="width"
          :height="height"
        >
         
            <v-img aling="center" alt="Avatar" src="../assets/sid.jpg"></v-img>
         

          <v-card-text align="center">I'm card text</v-card-text>
          <v-card-actions v-if="actions">
            <v-btn icon>
              <v-icon>mdi-heart</v-icon>
            </v-btn>
            <v-btn text>Click</v-btn>
            <v-btn outlined>Click</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>

      <v-col class="col-md-2 col-12">
        <v-card
          class="mx-auto"
          :flat="flat"
          :loading="loading"
          :outlined="outlined"
          :elevation="elevation"
          :raised="raised"
          :width="width"
          :height="height"
        >
          <v-img
            v-if="media"
            class="white--text"
            height="200px"
            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
          >
            <v-card-title class="align-end fill-height">I'm a title</v-card-title>
          </v-img>
          <v-card-title v-else>I'm a title</v-card-title>

          <v-card-text>I'm card text</v-card-text>
          <v-card-actions v-if="actions">
            <v-btn icon>
              <v-icon>mdi-heart</v-icon>
            </v-btn>
            <v-btn text>Click</v-btn>
            <v-btn outlined>Click</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
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
v-img {
  border-radius: 50%;
}
</style>