<template>
  <section>
    <div class="text">
        <h5 style="color: #50828c">OUR BUSINESS AREAS</h5>
        <h1>Excellence in <span style="color: #50828c">Services</span> </h1>
     
      <div class="text_button">
        <p>
           We are leaders in providing consultancy services with a set of cutting-edge technologies and a team of <br> 
           experienced and renowned professionals. These are some options that you can hire.
        </p>

        <button>SEE ALL</button>
      </div>  
    
    </div>
    <div></div>
  </section>
</template>

<script>
export default {
  name: 'Services',
}
</script>

<style scoped lang="scss">
section {
  padding-top: 6rem;
  background: #a5a09d;
}
.text_button {
    display: flex;
    justify-content: space-between;
  
  button {
     padding-left: 1rem;
     padding-right: 1rem; padding: 1rem;
     border: none;
     border-radius: 1rem;
     cursor: pointer;

     background: #22918e;
     color: white;
  }
}

.text h1 {
  padding-top: 2rem;
  padding-bottom: 2rem;

  font-size: 2rem;
}

</style>