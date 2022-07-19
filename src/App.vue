<template>
  <div class="container">
    <NavBar />
    <Header />
  </div>

</template>

<script>
import NavBar from './components/NavBar'
import Header from './components/Header'

export default {
  name: 'App',
  components: {
    NavBar,
    Header
  }
}
</script>
<style>
  @import './sass/main.css';
</style>