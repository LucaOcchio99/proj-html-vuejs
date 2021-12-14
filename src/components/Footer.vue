<template>
  <section>
   <div class="first">
      <img src="../assets/logo_01-640w.png" alt="">
      <p>  A Functional HTML Template for Corporate &amp; Business.</p>
      <p> <i class="fas fa-phone"></i> +1 (305) 1234-5678</p>
      <p> <i class="fas fa-envelope"></i> hello@example.com</p>
      <p> <i class="fas fa-map-marker-alt"></i> Main Avenue, 987</p>
      <button> GET IN TOUCH </button>
   </div>

     <div v-for="(service, index) in services" :key="`prod-${index}`">
        
        <FooterRepeat :titolo="service.titolo" :link_uno="service.link_uno" 
                       :link_due="service.link_due" :link_tre="service.link_tre"
                        :link_quattro="service.link_quattro" :link_cinque="service.link_cinque"  
                         :link_sei="service.link_sei"/>
   
   </div> 

  </section>
</template>

<script>
import FooterRepeat from '@/components/FooterRepeat.vue'

export default {
 name: 'Footer',
 components: {
   FooterRepeat,
 },
 data() {
   return {
     services: [
       {
         titolo: 'About',
         link_uno: 'The Company',
         link_due: 'Institutional',
         link_tre: 'Social & Events',
         link_quattro: 'Innovation',
         link_cinque: 'Enviornment',
         link_sei: 'Technology',
       },
       {
         titolo: 'Services',
         link_uno: 'Audit & Assurance',
         link_due: 'Financial Advisory',
         link_tre: 'Analytics M&A',
         link_quattro: 'Middle Marketing',
         link_cinque: 'Legal Consulting',
         link_sei: 'Regulator Risk',
       },
       {
         titolo: 'Support',
         link_uno: 'Responsability',
         link_due: 'Team of Use',
         link_tre: 'About Cookies',
         link_quattro: 'Privacy Policy',
         link_cinque: 'Accessibility',
         link_sei: 'Information',
       }
     ]
   }
 }
}
</script>

<style scoped lang="scss">
  section {
      display: flex;
      justify-content: space-between;
      background: rgb(214, 205, 193);
      padding-top: 3rem;
      padding-bottom: 3rem;
      .first {
          width: 225px;
          border: 1px solid black;
 
          padding: 2rem;
          button {
              margin-top: 1rem;
          }
            
          i {
              margin-right: 6px;
          }
          h2 {
              padding-bottom: 2rem;
          }
          img {
              height: 30px;
          }
      }
  }
</style>