<script setup>

</script>

<template>
  <div class="sidebar">
    <h1 class="sideTitle">New!</h1>
    <div class="sideCont">
      <h2 >Hydrogen VS Electric Cars</h2>
      <p >Will hydrogen-fueled cars ever catch up to Evs?</p>
    </div>
    <div class="sideCont">
      <h2 >The Downsides of AI Artistry</h2>
      <p >What are the possible adverse effects of on-demand AI image generation?</p>
    </div>
    <div class="sideCont">
      <h2 >Is VC Funding Drying Up?</h2>
      <p >Private funding by VC firms is down 50% YOY. We take a look at what that means.</p>
    </div>
  </div>
</template>

<style scoped>

.sidebar {
  background-color: var(--veryDarkBlue);
  padding: 3.5% 3.5% 0 3.5%;
  margin-bottom: 74px;
}
.sideTitle {
  font-weight: 700;
  font-size: 3rem;
  position: relative;
  top: -10px;
  color: var(--softOrange);
}
.sideCont  {
  color: var(--grayishBlue);
  min-height: 20%;
  font-size: 1rem;
  line-height: 2rem;
  padding-top: 30px;
  border-top: 2px solid var(--grayishBlue);
}

.sideCont h2{
  font-size: 2rem;
  font-weight: 600;
  color: var(--offWhite )
}
.sideCont:last-child {
  border-bottom: 0;
}


@media (min-width: 375px) {
}
</style>
