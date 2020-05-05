<template>
  <div id="app">
    <header>
      <nav>
        <ul>
          <li class="nav-item">
            Dynamic
          </li>
          <li class="nav-item market">
            Market
          </li>
        </ul>
      </nav>
    </header>
    <main>
      <HomePage />
    </main>
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue'

export default {
  name: 'App',
  components: {
    HomePage
  }
};
</script>

<style>
body{
  background: linear-gradient(to bottom, #00CCAA, #fff731);
  /*background: linear-gradient(to bottom, #00677B, #C6E9E0);*/
  background-attachment: fixed;
  background-size: 100% 150%;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>

<style scoped>
main{
  margin: 0 auto;
  padding: 30px;
  background-color: white;
  max-width: 1024px;
  height: auto;
  border-radius: 10px;
  display: flex;
  justify-content: center;
}
header {
  border-radius: 10px;
  background-color: white;
  max-width: 1084px;
  margin: 0 auto;
}
ul {
  padding: 5px 10px;
  display: flex;
}
.nav-item {
  color: #464646;
  display: flex;
  font-size: 22px;
  letter-spacing: 3px;
}
.market{
  font-weight: bold;
}
</style>
