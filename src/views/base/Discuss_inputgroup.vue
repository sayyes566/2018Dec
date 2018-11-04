<template>
<div class="top_fixed">
  <b-input-group >
    <!--b-input-group-prepend>
      <b-btn variant="outline-info">搜尋</b-btn>
    </b-input-group-prepend-->

    <b-form-input type="number" min="0.00"></b-form-input>

    <b-input-group-append>
      <b-btn variant="outline-secondary">搜尋</b-btn>
      <b-btn variant="outline-secondary" v-b-popover.hover="'鍵盤大俠們，是時候站上高峰決鬥吧！ '"
  title="你是大俠">
        <font-awesome-icon icon="marker" />發表文章
      </b-btn>
    </b-input-group-append>
  </b-input-group>
</div>
</template>
<!-- navbar-1.vue -->
<script>
export default {
  name: 'Inputgroup_discuss'
}
</script>

<style>
 .top_fixed{
    position:fixed;
    top: 0;
    z-index: 10;
}
</style>

