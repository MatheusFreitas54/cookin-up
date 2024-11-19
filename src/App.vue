<script lang="ts">
  import Banner from './components/Banner.vue';
import BotaoPrincipal from './components/BotaoPrincipal.vue';
  import ConteudoPrincipal from './components/ConteudoPrincipal.vue';
import Rodape from './components/Rodape.vue';

  export default {
    components: { Banner, ConteudoPrincipal, BotaoPrincipal, Rodape }
  }
</script>

<template>
  <Banner />
  <ConteudoPrincipal />
  <BotaoPrincipal />
  <Rodape />
</template>

<style scoped>
</style>