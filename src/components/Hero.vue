<template>
  <section>
    <div class="content"> 
      <div> 
         <h5>FUSION &amp; ACQUISITIONS</h5>
         <h1>Insurance</h1>
         <h1>Consulting</h1>
      </div>
      <div class="top">
         <input type="text" placeholder="Name">
         <input type="text" placeholder="Email">
      </div>
      <div class="bottom">
          <input type="text" placeholder="Phone">
          <input type="text" placeholder="More Info">
      </div>

      <button>GET IN TOUCH</button>
      <button>READ MORE</button>
    </div> 
  </section>
</template>

<script>
export default {
  name: 'Hero',
}
</script>

<style scoped lang="scss">
section {
    background: lightgrey;
    background-image: url(../assets/bg-6.jpg); 
    background-size: contain;
    background-repeat: no-repeat;
    display: flex;
    justify-content: flex-end;
    align-items: center;
   height: 500px;
}
input {
 border: none;
 margin-top: 6px;
}
.top input:first-child,
.bottom input:first-child {
    margin-right: 1rem;
}
button {
    margin-top: 1rem;
    margin-right: 1rem;
}
</style>