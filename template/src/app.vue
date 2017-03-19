<template>
  <div id="app">
    <link href="https://fonts.googleapis.com/earlyaccess/notosansjapanese.css" rel="stylesheet" />
    {{#router}}
    <router-view></router-view>
    {{/router}}
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Component from 'vue-class-component'
@Component({
  methods: {
    sayHello: function
  }
})
export default App extends Vue{
  name: "app",
  methods: {
    sayHello: () => {
      console.log('sayHello')
    }
  }
}
</script>

<style>
</style>

