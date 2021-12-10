<template>
  <section>
    
    <div class="superior_cards">
       <div class="card">
          
       </div>

       <div class="card"></div>

       <div class="card"></div>
    </div>

    <div class="lower_cards">

        <div class="card"></div>

        <div class="card"></div>

        <div class="card"></div>
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
        height: 250px;
        width: 300px;
        border: 1px solid black;
    }
}

.lower_cards {
   margin-top: 2rem;
}

</style>