<template>
  <div class="Discuss">
    <Navbar />
   
    <Discuss_list_badges />
    <Discuss_nav_footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from './base/Navbar.vue'
import Discuss_list_badges from './base/Discuss_list_badges.vue'
import Discuss_nav_footer from './base/Discuss_nav_footer.vue'
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
export default {
  name: 'Discuss',
  components: {
    Navbar,
    
    Discuss_list_badges,
    Discuss_nav_footer
    
  }
}
</script>
