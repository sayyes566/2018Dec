<template>
<b-navbar toggleable="md" type="dark" fixed="bottom" variant="dark">

  <!--b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

  <b-navbar-brand href="#" v-b-popover.hover="'鍵盤大俠們，是時候站上高峰決鬥吧！ '" 
  title="你是大俠">大俠 Daxia</b-navbar-brand-->

  <b-collapse is-nav id="nav_collapse">

    <b-navbar-nav>


    <b-input-group >
    <!--b-input-group-prepend>
      <b-btn variant="outline-info">搜尋</b-btn>
    </b-input-group-prepend-->

    <b-form-input type="text" ></b-form-input>

    <b-input-group-append>
      <b-btn variant="outline-secondary">搜尋</b-btn>
      <b-btn variant="outline-secondary" v-b-popover.hover="'為了正義發聲 '"
  title="大俠">
        <font-awesome-icon icon="marker" />發表文章
      </b-btn>
    </b-input-group-append>
  </b-input-group>
      


      <!--b-nav-item ><b-link :to="{ path: 'home' }" router-tag="li" active-class="router-link-active">選單</b-link>
</b-nav-item>
      <b-nav-item ><b-link :to="{ path: 'login' }" router-tag="li" active-class="router-link-active">登入</b-link>
</b-nav-item-->
 

</b-navbar-nav>


  </b-collapse>
</b-navbar>
</template>
<!-- navbar-1.vue -->
<script>
export default {
  name: 'Discuss_nav_footer'
}
</script>

<style>

</style>

