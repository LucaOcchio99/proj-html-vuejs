<template>
 <div>
     <h2>{{titolo}}</h2>
     <p> <i class="fas fa-chevron-right"></i> <a href="">{{link_sei}} </a></p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">{{link_uno}}</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">{{link_due}}</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">{{link_tre}}</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">{{link_quattro}}</a> </p>
     <p> <i class="fas fa-chevron-right"></i> <a href="">{{link_cinque}}</a> </p>
 </div>
</template>

<script>

export default {
name: 'FooterRepeat',
props: {
      titolo: String,
      link_uno: String,
      link_due: String,
      link_tre: String,
      link_quattro: String,
      link_cinque: String,
      link_sei: String,
}
}
</script>

<style scoped lang="scss">
 div {
          width: 225px;
          padding: 2rem;
          background: rgba(0, 0, 0, 0.527);
          border-radius: 1rem;


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
</style>