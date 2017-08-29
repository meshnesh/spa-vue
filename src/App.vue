<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <router-link v-bind:to="'/'">Home</router-link>
    <router-link v-bind:to="'/about'">About</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>
