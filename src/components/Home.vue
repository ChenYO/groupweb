<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <router-link to="/About">About</router-link>
  </div>
</template>

<script>
export default {
  name: 'About',
  data () {
    return {
      msg: 'Welcome to Home'
    }
  }
}
</script>