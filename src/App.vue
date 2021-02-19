<template>
  <div id="app">
    <label>
      <input class="input" v-model="message">
    </label>
  </div>
</template>

<script>

export default {
  name: 'Typed',
  data() {
    return {
      message: '',
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
  color: #2c3e50;
  margin-top: 60px;
  background-color: dimgray;
  height: 100%;
  width: 100%;
  font-weight: 600;
}

  .input {
    border-radius: 5px;
    background-color: dimgray;
    border: solid 1px gray;
    box-shadow: 0 0 10px 0 black;
    height: 40px;
    width: 500px;
    font-size: 18px;
    font-weight: 700;
    letter-spacing: 1px;
  }
</style>
