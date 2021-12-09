<template>
  <div id="app">
    <Contact />
    <Header />
    <Hero />
    <TheNetwork />
  </div>
</template>

<script>
import Contact from '@/components/Contact.vue';
import Header from '@/components/Header.vue';
import Hero from '@/components/Hero.vue';
import TheNetwork from '@/components/TheNetwork.vue';

export default {
  name: 'App',
  components: {
    Contact,
    Header,
    Hero,
    TheNetwork,
  }
}
</script>

<style lang="scss">
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

section {
  padding: 1rem 16rem 1rem;
}

a {
  text-decoration: none;
}

li {
  list-style: none;
}
</style>
