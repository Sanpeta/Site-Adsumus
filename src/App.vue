<template>
  <v-app>
    <Navbar />
    <Home />
  </v-app>
</template>

<script>
import Navbar from "./components/Navbar";
import Home from "./views/Home";

export default {
  name: "App",
  components: {
    Navbar,
    Home
  }
};
</script>
