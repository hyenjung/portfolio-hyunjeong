<template lang="pug">
  #app.container
   .main-wrapper
      Header

</template>

<script>
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: { Header }
}
</script>

<style lang="scss">
#app {
	@include flex($SB, $ST);
	flex-direction: column;
	height: 100vh;
}
</style>