<template>
  <b-nav pills right>
    <b-nav-item active  v-b-popover.hover="'鍵盤大俠們，是時候站上高峰決鬥吧！ '"
  title="你是大俠" >
      <font-awesome-icon icon="marker" />
    </b-nav-item>
  </b-nav>

</template>
<!-- navbar-1.vue -->
<script>
export default {
  name: 'Nav_tooltip_discuss'
}
</script>

<style>
 ui.navbar-nav > li > a:hover, ui.navbar-nav > li > a:focus {
    background-color: #FFFF00;
    color: #FFC0CB;
}

</style>

