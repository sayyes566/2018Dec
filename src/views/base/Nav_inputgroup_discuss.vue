<template>
<div>
  <b-input-group>
    <b-input-group-prepend>
      <b-btn variant="outline-info">Button</b-btn>
    </b-input-group-prepend>

    <b-form-input type="number" min="0.00"></b-form-input>

    <b-input-group-append>
      <b-btn variant="outline-secondary">Button</b-btn>
      <b-btn variant="outline-secondary">Button</b-btn>
    </b-input-group-append>
  </b-input-group>
</div>
</template>
<!-- navbar-1.vue -->
<script>
export default {
  name: 'Nav_inputgroup_discuss'
}
</script>

<style>
 ui.navbar-nav > li > a:hover, ui.navbar-nav > li > a:focus {
    background-color: #FFFF00;
    color: #FFC0CB;
}

</style>

