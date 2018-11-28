<template>
  <div class="home">
    <h1>{{ msg }}</h1>
    <router-link to="/About">About</router-link>
    <btn type="primary" @click="sayHello">Primary</btn>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to Home'
    }
  },
  methods: {
    sayHello: function() {
      alert("Hello")
    }
  }
}
</script>