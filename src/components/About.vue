<template>
  <div class="about">
    <h1>{{ msg }}</h1>
    <router-link to="/">Home</router-link>
  </div>
</template>

<script>
export default {
  name: 'About',
  data () {
    return {
      msg: 'Welcome to About'
    }
  }
}
</script>