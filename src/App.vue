<template>
<header>
  <nav>
    <ul>
      <li class="nav-item">
        <img src="./assets/build-a-bot-logo.png" alt="home" class="logo">
        Build-a-Bot
      </li>
    </ul>
  </nav>
</header>
<main>
    <HomePage/>
  </main>
</template>

<script>
import HomePage from './components/HomePage.vue';

export default {
  name: 'App',
  components: {
    HomePage,
  },
};
</script>

<style>
body{
  background-attachment: fixed;
  background-color: lightgray;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
main{
  margin: 0 auto;
  padding: 30px;
  width: 1024;
  background-color: white;
}
header {
  background-color: #999;
  width: 1084px;
  margin: 0 auto;
}
ul {
  padding: 3px;
  display: flex;
}
.nav-item {
  display: inline-block;
  padding: 5px 10px;
  font-size: 22px;
  border-right: 1px solid #bbb;
}
.logo {
  vertical-align: middle;
  height: 30px;
}

</style>
