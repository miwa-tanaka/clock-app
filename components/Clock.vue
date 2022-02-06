<template>
  <div>
    <div style="background: pink">
      <h1>hello world</h1>
    </div>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        timeZone: null
      }
     },
     created () {
       this.hoge()
     },
     methods: {
       hoge () {
         console.log('ああああああ')

       }
     }
  }
</script>
