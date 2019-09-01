<template>
  <v-app>
    <Navbar />
    <router-view/>
    <BottomAdsumus/>
  </v-app>
</template>

<script>
import Navbar from "./components/Navbar";
// import Home from "./views/Home";
import BottomAdsumus from "./components/BottomAdsumus"

export default {
  name: "App",
  components: {
    Navbar,
    // Home,
    BottomAdsumus
  }
};
</script>
