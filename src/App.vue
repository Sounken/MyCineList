<template>
  <div id="app">
    <div class="menu">
      <Menu />
    </div>
    <div class="header">
      <Header />
    </div>
  </div>

</template>

<script>
import Menu from './menu/menu.vue'
import Header from './header/header.vue'

export default {
  components: {
    Menu,
    Header
  }
};
</script>


<style>
body {
  background-color: #F5F5F5;
  font-family: 'helvetica neue', sans-serif;
}

#app {
  display: flex;
  flex-direction: column;
}
</style>