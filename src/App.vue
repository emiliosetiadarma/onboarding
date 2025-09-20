<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="500" height="500" />
  </header>

  <main>
    <div class="wrapper">
      <HelloWorld msg="Hello Team PBRX! This is Luarensius Arief Rahman" github-link="https://github.com/Wolfzmus" username="wolfzmus"/>
    </div>
    <div class="wrapper">
      <HelloWorld msg="Hello Team PBRX! This is Luarensius Arief Rahman Test User After Second Test"
                  github-link="https://github.com/Wolfzmus/onboardingariefrahman"
                  username="wolfzmus" />
    </div>
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
