<template>
  <div id="app">
    <gaze-point />
  </div>
</template>

<script>
{{#isEnabled plugins 'vue-router'}}
{{else}}
{{/isEnabled}}
  export default {
    name: '{{ name }}'{{#isEnabled plugins 'vue-router'}}{{else}},{{/isEnabled}}
{{#isEnabled plugins 'vue-router'}}
{{else}}
    components: {
      
    }
{{/isEnabled}}
  }
</script>

<style>
  /* CSS */
</style>
