<template>
  <section>
     <div class="card">
         <p>01</p>
        <h3>Collection of <br> information</h3>
        <p>Lorem ipsum dolor sit amet <br> consecuter</p>
     </div>
     <div class="card">
         <p>02</p>
        <h3>Strategic planning</h3>
        <p>Lorem ipsum dolor sit amet <br> consecuter</p>
     </div>
     <div class="card">
         <p>03</p>
        <h3>Assignment of <br> responsibilities</h3>
        <p>Lorem ipsum dolor sit amet <br> consecuter</p>
     </div>
     <div class="card">
         <p>04</p>
        <h3>Formatting process</h3>
        <p>Lorem ipsum dolor sit amet <br> consecuter</p>
     </div>
     <div class="card">
         <p>05</p>
        <h3>Continuity <br> formalization</h3>
        <p>Lorem ipsum dolor sit amet <br> consecuter</p>
     </div>
  </section>
</template>

<script>
export default {
name: 'ProcessList',
}
</script>

<style scoped lang="scss">
section {
    display: flex;
    justify-content: space-between;

    background-color: lightgreen;

    .card p,
    .card h3 {
        text-align: center;
        
    }
}
</style>