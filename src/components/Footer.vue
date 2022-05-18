<template>
  <footer class="footer">
    <div class="local">
      <p>Casa do Paulo</p>
      <p>Rua Paulo Dias</p>
      <p>Tanganmandapio/To</p>
    </div>
    <div class="local-r">
      <p>Make Your Burguer</p>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
.footer {
  height: 200px;
  background-color: #222;
  border-top: 4px solid #111;
  color: #fcba03;
  display: flex;
  align-items: center;
  justify-content: space-around;
  width: 100%;

  .local{
    p{
      padding: 5px;
    }
  }
  .local-r{
    p{
      // margin-right: 50px;
    }
  }

  @media (max-width: 700px) {
    .local{
      margin-right: 5px;
    }
    .local-r{
      margin: 0;
      margin-left: 5px;
    }
  }
}
</style>