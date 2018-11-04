<template>
<b-navbar toggleable="md" type="dark" fixed="top" variant="dark">

  <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

  <b-navbar-brand href="#" v-b-popover.hover="'鍵盤大俠們，是時候站上高峰決鬥吧！ '" 
  title="你是大俠">大俠 Daxia</b-navbar-brand>

  <b-collapse is-nav id="nav_collapse">

    <b-navbar-nav>
      
      <b-nav-item ><b-link :to="{ path: 'home' }" router-tag="li" active-class="router-link-active">選單</b-link>
</b-nav-item>
      <b-nav-item ><b-link :to="{ path: 'login' }" router-tag="li" active-class="router-link-active">登入</b-link>
</b-nav-item>
    </b-navbar-nav>

    <!-- Right aligned nav items -->
    <b-navbar-nav class="ml-auto">

      <!--b-nav-form>
        <b-form-input size="sm" class="mr-sm-2" type="text" placeholder="Search"/>
        <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
      </b-nav-form-->
       <!--b-navbar-nav>
         <b-nav-item>
          <font-awesome-icon icon="marker" />
         </b-nav-item>
       </b-navbar-nav-->
      <!--b-nav-item-dropdown text="Lang" right>
        <b-dropdown-item href="#">EN</b-dropdown-item>
        <b-dropdown-item href="#">ES</b-dropdown-item>
        <b-dropdown-item href="#">RU</b-dropdown-item>
        <b-dropdown-item href="#">FA</b-dropdown-item>
      </b-nav-item-dropdown-->

      <b-nav-item-dropdown right>
        <!-- Using button-content slot -->
        <template slot="button-content">
          <em>User</em>
        </template>
        <b-dropdown-item href="#">Profile</b-dropdown-item>
        <b-dropdown-item href="#">Signout</b-dropdown-item>
      </b-nav-item-dropdown>
    </b-navbar-nav>

  </b-collapse>
</b-navbar>
</template>
<!-- navbar-1.vue -->
<script>
export default {
  name: 'Navbar'
}
</script>

<style>
 ui.navbar-nav > li > a:hover, ui.navbar-nav > li > a:focus {
    background-color: #FFFF00;
    color: #FFC0CB;
}

</style>

