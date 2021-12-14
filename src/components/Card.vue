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
        border: none;
        border-radius: 1rem;
        width: 300px;
        padding: 3rem;
        margin-top: 2rem;

        background: white;

        .icone {
          display: flex;
          justify-content: space-between;

          padding-bottom: 1rem;
          font-size: 22px;
        }
    }
    
    h2 {
      padding-bottom: 1rem;
    }
</style>