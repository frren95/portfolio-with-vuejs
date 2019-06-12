<template>
  <div class="home main-content">
    <div class="left-content slideUp">
      <router-link to="/portfolio/two"><img src="../assets/arrow-up.svg" alt="Arrow up icon to go to portfolio two item" class="arrow arrow-up"></router-link>
      <h1>PRINT</h1>
      <p class="subtxt">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Debitis, ut tempore eius earum nam dolorem reiciendis. Temporibus earum nisi nihil?</p>
      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui, aspernatur!</p>
    </div>
    <div class="right-content img2"></div>
  </div>
</template>

<script>
export default {
  name: 'one'
}
</script>

<style lang="scss" scoped>

  $page-color: #5478a7;

  h1 {
    color: $page-color !important;
  }

  .img2 {
    background: url('../assets/card.jpg');
    background-size: cover;
    background-position: 50%;

    img {
      width: 50%;
    }
  }
</style>

