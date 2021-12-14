<template>
  <div id="app">
    <Contact />
    <Header />
    <Hero />
    <TheNetwork />
    <Services />
    <ServicesCard />
     <Process />
    <ProcessList />
    <Footer /> 
    <FooterTwo />
  </div>
</template>

<script>
import Contact from '@/components/Contact.vue';
import Header from '@/components/Header.vue';
import Hero from '@/components/Hero.vue';
import TheNetwork from '@/components/TheNetwork.vue';
import Services from '@/components/Services.vue';
import ServicesCard from '@/components/ServicesCard.vue';
import Footer from '@/components/Footer.vue';
import FooterTwo from '@/components/FooterTwo.vue';
import Process from '@/components/Process.vue';
import ProcessList from '@/components/ProcessList.vue';

export default {
  name: 'App',
  components: {
    Contact,
    Header,
    Hero,
    TheNetwork,
    Services,
    ServicesCard,
    Footer,
    FooterTwo,
    Process,
    ProcessList,
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
