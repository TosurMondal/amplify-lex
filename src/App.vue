<template>
  <div id="app">
    <amplify-authenticator>
      <amplify-sign-in>
      </amplify-sign-in>
    <amplify-sign-out></amplify-sign-out>
  </amplify-authenticator>
  <amplify-chatbot
    bot-name="awsServiceBot_dev"
    bot-title="My ChatBot"
    welcome-message="Hello, how can I help you?"
  />
  </div>
</template>
<script>

export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
