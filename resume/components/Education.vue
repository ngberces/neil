<!--
Author: Berces, Neil Angelo G.
File Name: Education.vue 
Description: Displays my Background Education
-->
<template>
  <div id="education">
    <div class="alert alert-success" role="alert">
      <h1>{{ msg6 }}</h1>
      <p>Elementary: Holy Family Academy</p>
      <p>High School: Holy Family Academy</p>
      <p>College: Holy Angel University</p>
    </div>
  </div>

</template>

<script>
export default {
  name: 'education',
  data () {
    return{
      msg6: 'Background Education'
    }
  }
}
</script>