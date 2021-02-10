<template>
  <div id="app">
    <link href='https://fonts.googleapis.com/css?family=Lobster' rel='stylesheet'>
    <HeadBar />
    <router-view/>
  </div>
</template>

<script>
  import HeadBar from './components/HeadBar'

  export default {
    components: {
      HeadBar
    },
    // ...
  }
</script>

<style lang="scss">
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
</style>
