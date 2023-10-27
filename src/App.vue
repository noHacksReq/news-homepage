<script setup>

import Header from './components/Header.vue'
import Body from './components/Body.vue'
import SideBar from './components/SideBar.vue'
import ArticlePreview from './components/ArticlePreview.vue'
</script>

<template class="main">
  <header>
    <Header />
  </header>

  <main>
    <Body />
    <SideBar />
  </main>
 
    <ArticlePreview />
  
  
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

@media screen and (min-width: 0px) and (max-width: 375px) {
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
