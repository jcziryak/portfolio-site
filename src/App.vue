<script setup>
import FooterBar from './components/FooterBar.vue';
import NavBar from './components/NavBar.vue';
</script>

<template>
  <NavBar />
  <main>
    <p>Billions and Billions</p>
  </main>
  <FooterBar />
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans:wght@400;700;900&family=Lato:wght@100;300;400;700;900&display=swap');
:root {
  font-size: 18px;
  /* Font Families */
  --heading-font: 'Fira Sans', sans-serif;
  --body-font: 'Lato', sans-serif;

  /* Font Weights */
  --font-thin: 100;
  --font-light: 300;
  --font-regular: 400;
  --font-bold: 700;
  --font-black: 900;

  /* Colors */
  --bg-color: #1C1427;
  --text-color: #7ECA9C;
  --accent-color: #40394A;
  --line-color: #CCFFBD;
}

body {
  background: var(--bg-color);
  display: flex;
  flex-direction: column;
}
</style>
