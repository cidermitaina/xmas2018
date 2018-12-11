<template lang="pug">
section
  h1
    | Merry Christmas
  .santa
    img(src="~/assets/img/mv.png" alt="santa")
</template>

<style lang="scss" scoped>

  section {
    width: 50%; 
    background:#E53934;
    h1 {
      font-family: 'Lobster', cursive;
      color: #fff;
      text-align: center;
      font-size: 3em;
      padding-top: 80px;
    }
    .santa {
      width: 50%;
      margin: 80px auto 0;
      height: 100%;
      img {
          width: 100%;
      }
    }
  }
// ======================================================
  // SP
  @media screen and (max-width: 768px) {
    
    section {
      width: 100%;
      padding-bottom: 80px;
    }

  }
</style>
