<template>
  <div id="app">
    <Contact />
    <Header />
    <Hero />
  </div>
</template>

<script>
import Contact from '@/components/Contact.vue';
import Header from '@/components/Header.vue';
import Hero from '@/components/Hero.vue';

export default {
  name: 'App',
  components: {
    Contact,
    Header,
    Hero,
  }
}
</script>

<style lang="scss">
* {
  padding: 0;
  border: 0;
  box-sizing: border-box;
}

section {
  padding-left: 16rem;
  padding-right: 16rem;
}

a {
  text-decoration: none;
}

li {
  list-style: none;
}
</style>
