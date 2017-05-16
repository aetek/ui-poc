<template>
    <div id="app">
        <div class="header-container">
            <app-header></app-header>
        </div>
        <div class="content-container">
            <app-home></app-home>
        </div>
    </div>
</template>

<script>
  import Header from './Components/Shared/Header.vue'
  import Home from './Components/Site/Home.vue'

  export default {
    name: 'app',
    data () {
      return {}
    },
    components: {
      appHome: Home,
      appHeader: Header
    }
  }
</script>

<style>
    .content-container {
        margin-top: 60px;
    }
</style>
