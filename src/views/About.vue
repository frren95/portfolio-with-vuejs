<template>
  <div class="about main-content">
    <div class="left-content">
      <h1>About me</h1>
      <p class="subtxt">I design, code, and teach a bunch of other people to do the same.</p>
      <button><router-link to="/portfolio/one">Look at my work</router-link></button>
    </div>
    <div class="right-content">
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem nulla cum nemo rerum aperiam excepturi quis sunt iusto, consectetur sed natus explicabo asperiores earum placeat.</p>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora cumque iure hic error totam ratione impedit, ullam recusandae laboriosam, dolorum autem itaque ea soluta aperiam minima dolorem quis vel voluptates possimus similique fuga explicabo. Accusantium impedit doloribus quidem nobis autem ullam ipsa veritatis corrupti iure, sint laborum ratione maxime illo!</p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .left-content {
    background-color: #FFE476;
  }
  .right-content {
    background-color: #FFF;
    padding: 50px;
    margin-top: 80px;
    display: block;
  }

  button {
    font-size: 1.5em;
    margin-top: 100px;
  }

  .subtxt {
    font-size: 1.5em;
    margin-top: 30px;
  }
</style>

