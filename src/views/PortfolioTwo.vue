<template>
  <div class="home main-content">
    <div class="left-content slideUp">
      <router-link to="/portfolio/one"><img src="../assets/arrow-up.svg" alt="Arrow up icon to go to portfolio one item" class="arrow arrow-up"></router-link>
      <h1>MOBILE UI</h1>
      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui, aspernatur!</p>
      <p class="subtxt">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Debitis, ut tempore eius earum nam dolorem reiciendis. Temporibus earum nisi nihil?</p>
      <router-link to="/portfolio/three"><img src="../assets/arrow-down.svg" alt="Arrow down icon to go to portfolio three item" class="arrow arrow-down"></router-link>
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

  $page-color: #48D886;

  h1 {
    color: $page-color !important;
  }

  .img2 {
    background: url('../assets/phone.jpg');
    background-size: cover;
    background-position: 50%;

    img {
      width: 50%;
    }
  }
</style>

