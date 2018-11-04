<template>
  <div class="home">
    <Navbar />
    <List />
  </div>
</template>

<script>
// @ is an alias to /src

import Navbar from './base/Navbar.vue'




import List from './base/List.vue'
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
export default {
  name: 'home',
  components: {
    Navbar,
    List
    
  }
}
</script>
