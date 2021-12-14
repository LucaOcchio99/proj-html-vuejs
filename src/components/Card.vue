<template>
  <div class="card">
    <div class="icone">
             <i class="fas fa-desktop"></i>
             <i class="fas fa-arrow-right"></i>
          </div>
          <div>
             <h2>{{titolo}}</h2>
             <p>{{testo}}</p>
          </div> 
  </div>
</template>

<script>
export default {
name: 'Card',
props: {
    titolo: String,
    testo: String
}
};
</script>

<style scoped lang='scss'>
.card {
        border: 1px solid black;
        width: 300px;
        padding: 3rem;
        margin-top: 2rem;
    }
</style>