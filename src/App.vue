<script setup>

import Header from './components/Header.vue'
import Body from './components/Body.vue'
import SideBar from './components/SideBar.vue'
import Footer from './components/Footer.vue'
</script>

<template class="main">
  <header>
    <Header />
    
  </header>

  <main>
    <Body />
    <SideBar />
  </main>
  <footer>
    <Footer />
  </footer>
  
</template>

<style scoped>


body {
  display: flex;
  flex-direction: column;
  background-color: var(--red);
}
main {
  display: flex;
  flex-direction: row;
  
}

@media screen and (min-width: 0px) and (max-width: 600px) {
 header {
  width: 90vw;
 }

 main {
  width: 90vw;
  display: flex;
  flex-direction: column;
 }
}
</style>
