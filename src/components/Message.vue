<template>
  <div class="message-container">
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: "Message",
  props: { msg: String },
};
</script>

<style scoped>
.message-container {
  color: #000000;
  background-color: #3aff75;
  border: 2px solid #00bb3e;
  border-radius: 5px;
  padding: 10px;
  max-width: 400px;
  text-align: center;
  margin: 30px auto;
}
</style>