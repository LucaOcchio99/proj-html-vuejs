<template>
  <section>
   <div>
      <img src="../assets/logo_01-640w.png" alt="">
      <p>  A Functional HTML Template for Corporate &amp; Business.</p>
      <p> <i class="fas fa-phone"></i> +1 (305) 1234-5678</p>
      <p> <i class="fas fa-envelope"></i> hello@example.com</p>
      <p> <i class="fas fa-map-marker-alt"></i> Main Avenue, 987</p>
      <button> GET IN TOUCH</button>
   </div>

   <div>
     <h2>About</h2>
     <p> <i class="fas fa-chevron-right"></i> <a href="">The company</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Institutional</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Social &amp; Events</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Innovation</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Environment</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Technology</a> </p>
   </div>

   <div>
     <h2>Services</h2>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Audit &amp; Assurance</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Financial Advisory</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Analytics M&amp;A</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Middle Marketing</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Legal Consulting</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Regulatory Risk</a> </p>
   </div>

   <div>
     <h2>Support</h2>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Responsability</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Terms of Use</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">About Cookies</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Privacy Policy</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Accessibility</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">Information</a> </p> 
   </div>       
  </section>
</template>

<script>
export default {
 name: 'Footer',
}
</script>

<style scoped lang="scss">
  section {
      display: flex;
      justify-content: space-between;
      background: rgb(214, 205, 193);
      padding-top: 3rem;
      padding-bottom: 3rem;

      div {
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