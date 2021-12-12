<template>
    <section>
   
        <div class="left">
           <p> <i class="fas fa-clock"></i> Open Hours: Mon - Sat - 9:00 - 18:00</p> 
        </div>

        <div class="right">
             <span><i class="fas fa-phone"></i> +1(305) 1234-5678</span>
             <span><i class="fas fa-envelope"></i> hello@example.com</span>
             <span><i class="fab fa-facebook-f"></i></span>
             <span><i class="fab fa-twitter"></i></span>      
             <span><i class="fab fa-linkedin-in"></i></span>
        </div>
   
    </section>
</template>

<script>
export default {
   name: 'Contact',
}
</script>

<style scoped lang="scss">
 section {
     background: lightblue;
     
     display: flex;
     justify-content: space-between;
     align-items: center;
 }

 span {
     padding-left: 2rem;
     
 }
</style>