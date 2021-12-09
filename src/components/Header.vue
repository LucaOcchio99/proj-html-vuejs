<template>
  <section>
      <div class="center">
        <div class="left">
           <img src="../assets/logo_01-640w.png" alt="">              
        </div>
        
        <div class="right">
           <ul>
             <li> <a href="">HOME</a> </li>
             <li> <a href="">ABOUT</a> </li>
             <li> <a href="">SERVICES</a> </li>
             <li> <a href="">PROCESS</a> </li>
             <li> <a href="">TEAM</a> </li>
             <li> <a href="">BLOG</a> </li>
             <li><button>GET IN TOUCH</button></li>   
           </ul>  
        </div>
      </div>
  </section>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style scoped lang="scss">
section {
   background: lightcoral;
}

.center {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

ul {
  display: flex;
  align-items: center;

  li {
    padding-left: 1rem;
  }
   
   button {
     padding: 1rem;
     border: none;
     border-radius: 1rem;
     cursor: pointer;
   }

}

img {
  height: 50px;
}
</style>