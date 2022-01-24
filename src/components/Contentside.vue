<template>
    <div class="content">
        <h2>Все новости</h2>
        <div class="card-news">
            <img src="../assets/img/news-content.jpg" alt="Новость">
            <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi vel, doloremque quam doloribus nulla impedit quis hic optio modi dicta rem laboriosam nemo. Dolor ratione iste, cum deleniti quae sint.</div>
        </div>
        <div class="card-news">
            <img src="../assets/img/news-content.jpg" alt="Новость">
            <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi vel, doloremque quam doloribus nulla impedit quis hic optio modi dicta rem laboriosam nemo. Dolor ratione iste, cum deleniti quae sint.</div>
        </div>
        <div class="card-news">
            <img src="../assets/img/news-content.jpg" alt="Новость">
            <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi vel, doloremque quam doloribus nulla impedit quis hic optio modi dicta rem laboriosam nemo. Dolor ratione iste, cum deleniti quae sint.</div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Contentside',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>


.content {
    max-width: auto;
    margin-left: 15px;
    background: content-box linear-gradient(to left, rgb(189, 180, 182, 0.8), rgba(76, 175, 80, 0.8));
    border-right: 2px solid rgba(63, 47, 2, 0.7);
    border-radius: 5%;
}
.card-news {
    display: flex;
    align-items: center;
    margin: 15px;
    background: content-box linear-gradient(to right top, rgb(189, 180, 182, 0.5), rgba(243, 233, 242, 0.5));
    border-radius: 5%;

}


</style>
