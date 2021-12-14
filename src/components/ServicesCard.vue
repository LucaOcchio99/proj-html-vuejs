<template>
  <section>
      
       <div v-for="(service, index) in services" :key="`serv-${index}`">
         
          <Card :titolo="service.titolo" 
                 :testo="service.testo"
                   :url="service.url" />
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
            url: 'fas fa-sitemap' ,
            titolo: 'Audit  Assurance',
            testo: 'Lorem ipsum dolor sit amet consectetur adipiscing elit.',
         },
         {
             url:   'fas fa-briefcase' ,
            titolo: 'Financial Advisory',
            testo: 'Lorem ipsum dolor sit amet consectetur adipiscing elit.',
         },
         {
             url:   'far fa-chart-bar' ,
            titolo: 'Analytics and M&A',
            testo: 'Lorem ipsum dolor sit amet consectetur adipiscing elit.',
         },
         {
             url:   'fas fa-plane' ,
            titolo: 'Middle Marketing',
            testo: 'Lorem ipsum dolor sit amet consectetur adipiscing elit.',
         },
         {
             url:  'fas fa-globe-europe' ,
            titolo: 'Legal Consulting',
            testo: 'Lorem ipsum dolor sit amet consectetur adipiscing elit.',
         },
         {
             url: 'fas fa-box' ,
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
   background: #a5a09d;

}
</style>