<template>
  <footer id="footer">
    <div class="content">
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
#footer {
  height: 200px;
  background-color: #222;
  border-top: 4px solid #111;
  color: #fcba03;
  display: flex;
  align-items: center;
  justify-content: flex-end;
  width: 100%;
}
.content{
  margin: 0 100px 0 0;
}
</style>