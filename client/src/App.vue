<template>
  <div id="app">
    <header>
      <h1>Take a screenshot</h1>
    </header>
    <main>
      <form @submit.prevent="">
        <input type="url" name="url" id="url" />
        <input type="submit" value="Take screenshot" />
      </form>
      <a href="#">
        <img src="" />
      </a>
    </main>
  </div>
</template>

<script>

export default {
  name: 'App',
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
