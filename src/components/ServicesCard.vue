<template>
  <section>
      
       <div v-for="(service, index) in services" :key="`serv-${index}`">
         
          <Card :titolo="service.titolo" :testo="service.testo"/>
       </div>

  </section>
</template>

<script>
import Card from '@/components/Card.vue';

export default {
name: 'ServicesCard',
components: {
   Card,
},
data() {
   return {
      services: [
         {
            titolo: 'Audit  Assurance',
            testo: 'Lorem ipsum dolor sit amet consectetur adipiscing elit.',
         },
         {
            titolo: 'Financial Advisory',
            testo: 'Lorem ipsum dolor sit amet consectetur adipiscing elit.',
         },
         {
            titolo: 'Analytics and M&A',
            testo: 'Lorem ipsum dolor sit amet consectetur adipiscing elit.',
         },
         {
            titolo: 'Middle Marketing',
            testo: 'Lorem ipsum dolor sit amet consectetur adipiscing elit.',
         },
         {
            titolo: 'Legal Consulting',
            testo: 'Lorem ipsum dolor sit amet consectetur adipiscing elit.',
         },
         {
            titolo: 'Regulator Risk',
            testo: 'Lorem ipsum dolor sit amet consectetur adipiscing elit.',
         },

      ]
   }
}
}
</script>

<style scoped lang="scss">
section {
   padding-bottom: 6rem;
   display: flex;
   justify-content: space-between;
   flex-wrap: wrap;
}
</style>