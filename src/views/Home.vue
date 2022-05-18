<template>
  <div class="mainContainerBanner">
    <div class="image_banner opacity-bg">
      <button class="btn-promo">
        Confira nossas promoções
      </button>
    </div>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
}
</script>

<style lang="scss" scoped>
.mainContainerBanner {
  width: 100%;
  height: 850px;
  background-image: url("@/assets/img/burger.jpg");
  .image_banner{
    display: flex;
    justify-content: center;
    }
    .btn-promo{
      margin-top: 600px;
      border: none;
      padding: 20px 90px;
      border-radius: 30px;
      color: white;
      background-color: #fcba03;
      font-weight: 600;
      font-size: 1rem;
      cursor: pointer;
      @media (max-width: 700px) {
        padding: 20px 30px;
      }
      &:hover{
        transition: 0.5s ease-out;
        background-color: #916a00;
      }
  }
}
</style>
