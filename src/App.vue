<template>
  <div id="app">
    <nav class="nav has-shadow">
    </nav>
    <section class="main-section section">
      <div class="container content">
        <img src="./assets/logo.png">
        <h1>{{ msg }}</h1>
        <h2>Essential Links</h2>
      </div>
    </section>
    <footer class="footer">
        <span class="icon">
  <i class="fab     fa-linkedin-in"></i>
</span>
<span class="icon">
  <i class="fas fa-home"></i>
</span>
<span class="icon">
  <i class="fas fa-home"></i>
</span>
<span class="icon">
  <i class="fas fa-home"></i>
</span>

    </footer>
  </div>

</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
@import '~bulma';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
