<script setup>
//import HelloWorld from './components/HelloWorld.vue'
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
}
main {
  display: flex;
  flex-direction: row;
  
}

@media (min-width: 1024px) {
 
}
</style>
