<script setup>

</script>

<template>
  <div class="header">
    <img id="logo" src="assets\images\logo.svg" />
    <ul class="topNav">
      <li class="navItem"><a href="####">Home</a></li>
      <li class="navItem"><a href="####">News</a></li>
      <li class="navItem"><a href="####">Popular</a></li>
      <li class="navItem"><a href="####">Trending</a></li>
      <li class="navItem"><a href="####">Categories</a></li>
      <li ><img class="burger" src="assets\images\icon-menu.svg" /></li>
    </ul>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

#logo {
  text-align: center;
  padding-top: 3%;
  height: 100px;
}

a {
  color: var(--darkGrayishBlue);
  text-decoration: none;
  font-weight: 400;
}

a:hover {
  color: var(--veryDarkBlue);
  font-weight: 700;
}

.header {
  
  width: 100%;
  min-height: 20vh;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  margin-bottom: 50px;
  line-height: 50px;
}

.topNav {
  list-style: none;
  display: flex;
  flex-direction: row;
  min-width: 51vw;
  padding-top: 3%;
  
  line-height: 50px;
  justify-content: flex-end;
  text-align: center;

}

.navItem {
  display: inherit;
  
  margin-left: 4vw;
  
}

.burger {
  display: none;
}





@media screen and (min-width: 0px) and (max-width: 600px) {

  #logo {
    height: 15vh;
    vertical-align: middle;
  }
  .navItem {
    display: none;
  }
  .burger  {
    display: inherit;
    padding-top: 0;
    height: 13vh;
    width: 70%;
  }
}
</style>
