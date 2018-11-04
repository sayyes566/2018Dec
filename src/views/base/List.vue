<template>
<div>
 <b-list-group>
  <b-list-group-item >
   <b-link :to="{ path: 'discuss' }" router-tag="li" active-class="router-link-active">
     所有討論
   </b-link>
  </b-list-group-item>
  <b-list-group-item href="#" active>任務</b-list-group-item>
  <b-list-group-item href="#">影片（待續）</b-list-group-item>
  <b-list-group-item href="#foobar" disabled>辯論賽（待續）</b-list-group-item>
 </b-list-group>
</div>
</template>
<!-- navbar-1.vue -->
<script>
export default {
  name: 'List'
}
</script>

<style>
 ui.navbar-nav > li > a:hover, ui.navbar-nav > li > a:focus {
    background-color: #FFFF00;
    color: #FFC0CB;
}

</style>

