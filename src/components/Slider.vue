<template>
  <v-carousel cycle>
    <v-carousel-item v-for="(item,i) in items" :key="i" :src="item.src">
      <v-row class="fill-height" align="center" justify="center">
        <div class="display-3 white--text">
          {{ i + 1}} Slide          
          <div class="text-center">
            <v-btn color="green darken-3">Saiba mais</v-btn>
          </div>
        </div>
      </v-row>
    </v-carousel-item>
  </v-carousel>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          src: "https://images.unsplash.com/photo-1565728744382-61accd4aa148?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1052&q=80",
          //author: "Photo by Maranda Vandergriff on Unsplash"
        },
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/planet.jpg",
          //author: "Photo by Maranda Vandergriff on Unsplash"
        }
      ]
    };
  }
};
</script>