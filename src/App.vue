<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="500" height="500" />
  </header>

  <main>
    <div class="wrapper">
      <HelloWorld
        msg="Hello PBRX! This is Emilio Setiadarma"
        github-link="https://github.com/emiliosetiadarma"
        username="emiliosetiadarma"
      />
    </div>
    <div class="wrapper">
      <HelloWorld
        msg="Hello PBRX! This is Emilio Setiadarma Test User After Second Test"
        github-link="https://github.com/emiliosetiadarmatest"
        username="emiliosetiadarmatest"
      />
      <HelloWorld
        msg="Hello PBRX! This is Ferdian Estu Anantama"
        github-link="https://github.com/ferdiananantama"
        username="ferdiananantama"
      />
    </div>
	<div class="wrapper">
      <HelloWorld msg="Hello PBRX! This is Nugroho Ari Saputro"
                  github-link="https://github.com/githubpbrx"
                  username="githubpbrx" />
    </div>
<div class="wrapper">
      <HelloWorld msg="Hello PBRX! This is Juvan Daffa Tyowarsa"
                  github-link="https://github.com/juvandaffa23"
                  username="juvandaffa23" />
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
