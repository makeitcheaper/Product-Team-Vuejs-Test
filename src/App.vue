<template>
  <div id="app">

  </div>
</template>

<script>

export default {
  name: 'app',
  data() {
    return {
      conversation: [
        {
          sender: 'bot',
          text: "Hello! Please choose from one of the options below:"
        },
        {
          sender: 'user',
          options: [
            'Option A',
            'Option B',
            'Option C'
          ]
        },
        {
          sender: 'bot',
          text: "Option A? Great choice!"
        },
      ]
    }
  }
}
</script>

<style lang="scss">
body, html {
  height: 100%;
  margin: 0;
  background-color: #F7F8F9;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding-top: 60px;
  height: 100%;
}

</style>
