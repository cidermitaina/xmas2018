<template lang="pug">
main
  Mv
  Article
</template>

<script>
import Mv from '~/components/Mv.vue'
import Article from '~/components/Article.vue'

export default {
  components: {
    Mv,
    Article
  }
}
</script>

<style>

  main {
    display: flex;
    height: 100%;
    overflow: hidden;
  }

/* SP */
  @media screen and (max-width: 768px) {
    
    main {
      display: block;
      height: auto;
    }

  }
</style>
