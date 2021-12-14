<template>
  <section>
    <div class="left">
       <h4>ABOUT THE NETWORK</h4>
       <h1>The Company</h1>
       <p>Lorem ipsum sit amet, consectetur adipiscing elit. Cras <br>
       iaculis diam varius diam ultricies Iacinia. Marius Iacus tellus, <br>
       ultrices eu volutpat sit amet, finibus a ipsum. </p>
       <p>Curabitur convallis, diam a egestas iaculis, neque lorem interdum <br> interdum felis, in viverra lacus tortor in leo.</p>
    </div>
    
    <div class="right">     
       <div class="top">
          <div class="first"> 
             <h4> <i class="fas fa-medal"></i> Tradition</h4>
             <p>Lorem ipsum dolor sit amet <br> consectetur adipiscing elit.</p>    
          </div>
          
          <div class="second">
              <h4> <i class="fas fa-lock"></i> Security</h4>
              <p>Lorem ipsum dolor sit amet <br> consectetur adipiscing elit.</p>
          </div>   
        </div>

        <div class="bottom">
           <div class="first">  
             <h4> <i class="far fa-sticky-note"></i> Certificate</h4>
             <p>Lorem ipsum dolor sit amet <br> consectetur adipiscing elit.</p> 
             </div>
           
            <div class="second">
              <h4> <i class="fas fa-graduation-cap"></i> Expertise</h4>
              <p>Lorem ipsum dolor sit amet <br> consectetur adipiscing elit.</p>   
            </div>        
        </div>    
    </div>
  
  </section>
</template>

<script>
export default {
  name: 'TheNetwork',
}
</script>

<style scoped lang="scss">
section {
    display: flex;
    justify-content: space-between;
    background-color: burlywood;
    padding-top: 6rem;
    padding-bottom: 6rem;
}
 .top,
 .bottom {
     display: flex;
 }
 .top .first:first-child,
  .bottom .first:first-child{
   margin-right: 2rem;
 }
.bottom {
  margin-top: 2rem;
}
</style>