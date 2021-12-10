<template>
  <section>
    
    <div class="superior_cards">
       <div class="card">
          <div class="icone">
             <i class="fas fa-desktop"></i>
             <i class="fas fa-arrow-right"></i>
          </div>
          <div>
             <h2>Audit  Assurance</h2>
             <p>Lorem ipsum dolor sit amet <br> consectetur adipiscing elit.</p>
          </div>
       </div>

       <div class="card">
         <div class="icone">
             <i class="fas fa-desktop"></i>
             <i class="fas fa-arrow-right"></i>
          </div>
          <div>
             <h2>Financial Advisory</h2>
             <p>Lorem ipsum dolor sit amet <br> consectetur adipiscing elit.</p>
          </div>
       </div>

       <div class="card">
         <div class="icone">
             <i class="fas fa-desktop"></i>
             <i class="fas fa-arrow-right"></i>
          </div>
          <div>
             <h2>Analytics and M&amp;A</h2>
             <p>Lorem ipsum dolor sit amet <br> consectetur adipiscing elit.</p>
          </div>
       </div>
    </div>

    <div class="lower_cards">

        <div class="card">
          <div class="icone">
             <i class="fas fa-desktop"></i>
             <i class="fas fa-arrow-right"></i>
          </div>
          <div>
             <h2>Middle Marketing</h2>
             <p>Lorem ipsum dolor sit amet <br> consectetur adipiscing elit.</p>
          </div>
        </div>

        <div class="card">
          <div class="icone">
             <i class="fas fa-desktop"></i>
             <i class="fas fa-arrow-right"></i>
          </div>
          <div>
             <h2>Legal Consulting</h2>
             <p>Lorem ipsum dolor sit amet <br> consectetur adipiscing elit.</p>
          </div>
        </div>

        <div class="card">
          <div class="icone">
             <i class="fas fa-desktop"></i>
             <i class="fas fa-arrow-right"></i>
          </div>
          <div>
             <h2>Regulator Risk</h2>
             <p>Lorem ipsum dolor sit amet <br> consectetur adipiscing elit.</p>
          </div>
        </div>
    </div>

  </section>
</template>

<script>
export default {
name: 'ServicesCard',
}
</script>

<style scoped lang="scss">
.superior_cards,
 .lower_cards {
   display: flex;
   justify-content: space-between;
    
    .card {
        border: 1px solid black;
        width: 300px;
        padding: 3rem;
    }
}

.icone {
  display: flex;
  justify-content: space-between;
}

.lower_cards {
   margin-top: 2rem;
}

</style>