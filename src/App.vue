<template>
  <div>
    <Navbar :logo="logo" :alt="app_name" />
    <router-view />
    <!-- <Banner /> -->
    <Footer />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";
// import Banner from "./components/Banner.vue";

export default {
  components: {
    Navbar,
    Footer,
    // Banner
  },
  data() {
    return {}
  },
};
</script>

<style lang="scss">
* {
  font-family: Arial, Helvetica, sans-serif;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
*::-webkit-scrollbar {
  width: 10px;
}
*::-webkit-scrollbar-thumb {
  background-color: gray;
  border-radius: 20px;
}

.mainContainer {
  width: 100%;
  height: 850px;
}

h1 {
  text-align: center;
  font-size: 42px;
  margin-bottom: 30px;
  color: #222;
}
</style>
