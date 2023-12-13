<template>
  <h1>Ninja Reaction Timer</h1>
  <button @click="start">PLAY</button>
</template>

<script>


export default {
  name: 'App',
  components: {},
  data() {
    return {
      isPlaying: false,
      display: null
    }
  },
  methods:{
    start() {
      this.delay = 2000 + Math.random() * 5000
      this.isPlaying = true
      console.log(delay)
    }

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #444;
  margin-top: 60px;
}


</style>
