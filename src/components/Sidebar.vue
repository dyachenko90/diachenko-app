<template>
  <div class="sidebar">
    <ul>
      <li>
        <img src="../assets/img/politic.png" alt="Политика">
        <a href="/">Политика</a>
      </li>
      <li>
        <img src="../assets/img/economic.png" alt="Экономика">
        <a href="/">Экономика</a>
      </li>
      <li>
        <img src="../assets/img/sport.png" alt="Спорт">
        <a href="/">Спорт</a>
      </li>
      <li>
        <img src="../assets/img/science.png" alt="Наука">
        <a href="/">Наука</a>
      </li>
      <li>
        <img src="../assets/img/health.png" alt="Здоровье">
        <a href="/">Здоровье</a>
      </li>
      <li>
        <img src="../assets/img/technologies.png" alt="Технологии">
        <a href="/">Технологии</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Sidebar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
img {
  width: 70px;
}
ul {
 
  list-style-type: none;
  padding: 0;
}
li {
  margin-left: 10px;
  display: flex;
  align-items: center;
  margin-top: 15px;
}
li a {
  margin-left: 15px;
  text-decoration: none;
  font-size: 24px;
  font-weight: 500;
  color: rgb(66, 64, 65);
  text-shadow: 3px -3px #bab8bd;
}
a:hover {
  color: #424ab9;
}
.sidebar {
  min-width: 400px;
  height: auto;background: content-box linear-gradient(to bottom, rgb(189, 180, 182, 0.8), rgba(76, 175, 80, 0.8));
  
  border-right: 2px solid rgba(63, 47, 2, 0.7);
  border-radius: 8%;
}

</style>
