
<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" name="" id="" class="searchbar" placeholder="Search...">
      </div>
    </main>


  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      api_key: '077137dcb2faa98dd797e0a1c8b763ce'
    }
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;

}

body {
  font-family: 'monserrat', sans-serif;
}

#app {
  background-image: url(.assets/cold-bg.jpg);
  background-size: cover;
  background-position: bottom;
  transition: 0.4s;
}

main {
  min-height: 100vh;
  padding: 25px;
}


</style>