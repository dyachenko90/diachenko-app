<template>
  <div id="nav">
    <img class="logo" src="./assets/img/icon3.png" alt="Лого">
    <router-link to="/"> Главная |</router-link> 
    <router-link to="/about"> Редактор новостей |</router-link> 
    <router-link to="/reg"> Регистрация </router-link>
  </div>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 20px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #424ab9;
}
*{
  box-sizing: border-box;
}
body {
  display: flex;
  flex-direction: column;
  margin: 0 auto;
  background: content-box url('./assets/img/bg-main.jpg') ;
}
.logo {
  width: 100px;
  margin-right: auto;
}
router-link {
  margin-right: 8px;
}

</style>
