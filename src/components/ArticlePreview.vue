<script setup>
import retroPCs from "/public/image-retro-pcs.jpg";
import topLaptops from "/public/image-top-laptops.jpg";
import gaming from "/public/image-gaming-growth.jpg";
</script>

<template>
  <div class="articles">
    <ul class="articleList">
      <li class="artilecPrev"><img class="prevImg" :src="retroPCs"
        alt="Retro PCs">
        <div class="prevCont">
          <h1 class="prevNum">01</h1>
          <h2 class="prevTitle">Reviewing Retro PCs</h2>
          <p class="prevArtCont">What happens when old PCs are given modern upgrades?</p>
        </div>
      </li>
      <li class="artilecPrev"><img class="prevImg" :src="topLaptops"
        alt="Top 10 Laptops">
        <div class="prevCont">
          <h1 class="prevNum">02</h1>
          <h2 class="prevTitle">Top 10 Laptops of 2022</h2>
          <p class="prevArtCont">Our best pics for various needs and budgets.</p>
        </div>
      </li>
      <li class="artilecPrev"><img class="prevImg" :src="gaming"
        alt="The Growth of Gaming">
        <div class="prevCont">
          <h1 class="prevNum">03</h1>
          <h2 class="prevTitle">The Growth of Gaming</h2>
          <p class="prevArtCont">How the pandemic has sparked fresh opportunties.</p>
        </div>
      </li>
    </ul>
  </div>
</template>

<style scoped>




.articleList {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  list-style: none;
  padding-left: 15px;
}

.artilecPrev {
  display: flex;
}

.prevImg {
  max-height: 254px;
}
 .prevCont {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  margin-left: 20px;
 }

 .prevNum {
  font-size: 3rem;
  font-weight: 600;
  color: var(--grayishBlue);
 }

 .prevTitle {
  font-size: 1.2rem;
  font-weight: 600;
  color: var(--veryDarkBlue);
  
 }

 .prevArtCont {
  font-size: 1rem;
  color: var(--darkGrayishBlue);
  margin-bottom: -1%;
 }


@media (min-width: 1024px) {
}
</style>
