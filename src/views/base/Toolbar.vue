<template>
  <b-button-toolbar key-nav  aria-label="Toolbar with button groups">
    <b-button-group class="mx-1">
      <b-btn>&laquo;</b-btn>
      <b-btn>&lsaquo;</b-btn>
    </b-button-group>
    <b-button-group class="mx-1">
      <b-btn>Edit</b-btn>
      <b-btn>Undo</b-btn>
      <b-btn>Redo</b-btn>
    </b-button-group>
    <b-button-group class="mx-1">
      <b-btn>&rsaquo;</b-btn>
      <b-btn>&raquo;</b-btn>
    </b-button-group>
  </b-button-toolbar>

</template>
<!-- navbar-1.vue -->
<script>
export default {
  name: 'Toolbar'
}
</script>

<style>
 ui.navbar-nav > li > a:hover, ui.navbar-nav > li > a:focus {
    background-color: #FFFF00;
    color: #FFC0CB;
}

</style>

