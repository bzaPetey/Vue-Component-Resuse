<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <h3>Reusable Component Test</h3>

  <ResuseableCompenent />
</template>



<script>
import ResuseableCompenent from './components/ReusableComponent'

export default {
  name: 'App',
  components: {
    ResuseableCompenent    
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
