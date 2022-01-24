<template>
  <div class="home">
    <Sidebar/>
    <Contentside/>
  </div>
</template>

<script>
import Sidebar from '@/components/Sidebar.vue'
import Contentside from '@/components/Contentside.vue'

export default {
  name: 'Home',
  components: {
    Sidebar,
    Contentside,
  }
}
</script>

<style>
.home {
  display: flex;
  
}
</style>