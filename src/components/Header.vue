<script setup>
defineProps({
  
})
</script>

<template>
  <div class="header">
    <h1>Im the header now!</h1>
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

.header {
  background-color: var(--softOrange);
}



@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
