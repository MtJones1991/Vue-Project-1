<template>
  <div id="app">
    <h1> {{ title }} </h1>

    <Navbar />
    <Blogs />

  </div>
</template>

<script>

import Navbar from './Navbar'
import Blogs from './Blogs'

export default {
  name: 'app',
  components: {
    Navbar,
    Blogs
  },
  data () {
    return {
      title: 'Vue Project-1',
    }
  },
  methods: {

  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
}

h1 {
  color: #444;
  font-weight: normal;
  text-align: center;
}
</style>
