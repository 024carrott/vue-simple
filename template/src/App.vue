<template{{#pug}} lang="pug"{{/pug}}>
{{#if pug}}
  #app
    //- 이 곳에 pug 문법을 사용하여 문서를 작성합니다.
{{else}}
  <div id="app">

  </div>
{{/if}}
</template>

<script>
export default {
  name: 'app',
  data () {
    return {

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
