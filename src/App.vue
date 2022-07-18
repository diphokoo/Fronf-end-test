<template>
  <div class="container">
    <NavBar />
  </div>

</template>

<script>
import NavBar from './components/NavBar'

export default {
  name: 'App',
  components: {
    NavBar
  }
}
</script>
<style>
  @import './sass/main.css';
</style>