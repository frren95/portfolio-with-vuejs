<template>
  <div class="home main-content">
    <div class="left-content slideUp">
      <h1>CRYPTO LOGO</h1>
      <p class="subtxt">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Debitis, ut tempore eius earum nam dolorem reiciendis. Temporibus earum nisi nihil?</p>
      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui, aspernatur!</p>

      <router-link to="/portfolio/two"><img src="../assets/arrow-down.svg" alt="Arrow down icon to go to portfolio two item" class="arrow arrow-down"></router-link>
    </div>
    <div class="right-content img2">
      <img src="../assets/logo.svg" alt="Crypto logo image">
    </div>
  </div>
</template>

<script>

export default {
  name: 'one'
  }
</script>

<style lang="scss" scoped>

  $page-color: #625B7E;

  h1 {
    color: $page-color !important;
  }

  .img2 {
    background: $page-color;

    img {
      width: 50%;
    }
  }
</style>

