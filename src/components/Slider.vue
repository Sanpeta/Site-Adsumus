<template>
  <v-carousel cycle :height="heightScreen" hide-delimiters :show-arrows="false">
    <v-carousel-item v-for="(item,i) in items" :key="i" :src="item.src">
      <v-row class="pl-3 fill-height" align="center" justify="center">
        <div class="display-3 white--text font-weight-normal pr-5" align="center">
          <span class="green--text font-weight-medium col-md-8 col-12 text--justify">Estamos aqui</span> para ajudá-los a chegar ao <span class="red--text font-weight-medium">Topo</span>
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
        // {
        //   src: "https://images.unsplash.com/photo-1519389950473-47ba0277781c?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80",
        //   //author: "Photo by Maranda Vandergriff on Unsplash"
        // },
        {
          // src: "@/src/assts/sliderFirst.jpg",
          src: "https://images.unsplash.com/photo-1504610926078-a1611febcad3?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=80",
          //author: "Photo by Maranda Vandergriff on Unsplash"
        }
      ],
      heightScreen: screen.height - 200,
    };
  },
};
</script>