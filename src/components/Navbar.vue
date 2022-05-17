<template>
  <nav id="nav">
    <router-link :to="{name: 'Home'}" id="logo_url">
      <img id="logo" :src="logo" :alt="alt" />
    </router-link>
    <router-link :to="{name: 'Home'}">Home</router-link> |
    <router-link :to="{name: 'Pedidos'}">Pedidos</router-link>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
  props: ["logo", "alt"],
};
</script>

<style lang="scss" scoped>
#nav {
  background-color: #222;
  border-bottom: 4px solid #111;
  padding: 15px 50px;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  a {
    color: #fcba03;
    text-decoration: none;
    margin: 12px;
    transition: 0.5s;
    &:hover {
    color: #fff;
    }
  }

  #logo_url {
    margin: auto;
    margin-left: 0;
  }

  #logo {
  width: 40px;
  height: 40px;
  }
}
</style>