<template{{#pug}} lang="pug"{{/pug}}>
{{#if pug}}
  #app
    img(:src="vue.path", :alt="vue.label")
{{else}}
  <div id="app">
    <img :src="vue.path" :alt="vue.label">
  </div>
{{/if}}
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      vue: {
        path: './assets/logo.png',
        label: 'Vue.js'
      }
    }
  }
}
</script>

<style{{#sass}} lang="sass"{{/sass}}>
  {{#if sass}}
  html
    font-size: 100%
    background: #fff
  body
    margin: 0
  {{else}}
  html {
    font-size: 100%;
    background: #fff;
  }
  body {
    margin: 0
  }
  {{/if}}
</style>
