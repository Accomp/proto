<template>
  <div class="site-wrapper">
    <CharacterPane />
  </div>
</template>

<script>
import CharacterPane from '~/components/CharacterPane.vue'

export default {
  components: {
    CharacterPane,
  },
}
</script>

<style>
.site-wrapper {
  align-items: center;
  background: url('https://i.imgur.com/L1yNFTY.jpeg') center center;
  border: 2px solid #000;
  display: flex;
  justify-content: center;
  margin: 0 auto;
  min-height: 100vh;
  text-align: center;
}
</style>
