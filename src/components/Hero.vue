<template>
  <section>
    <div class="content"> 
      <div> 
         <h5>FUSION &amp; ACQUISITIONS</h5>
        <div class="titolo" style="color: #50828c">
         <h1>Insurance</h1>
         <h1>Consulting</h1>
        </div> 
      </div>
      <div class="top">
         <input type="text" placeholder="Name">
         <input type="text" placeholder="Email">
      </div>
      <div class="bottom">
          <input type="text" placeholder="Phone">
          <input type="text" placeholder="More Info">
      </div>

      <button class="one">GET IN TOUCH</button>
      <button class="two">READ MORE</button>
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
    background: #e8ecea;
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

 padding: 4px;
}
.top input:first-child,
.bottom input:first-child {
    margin-right: 1rem;
}
.one {
    margin-top: 1rem;
    margin-right: 1rem;

    padding: 1rem;
    border: none;

    color: white;
    background: #22918e;
    border-radius: 1rem;
}

.two {
    margin-top: 1rem;
    margin-right: 1rem;

    padding: 1rem;

    color: #22918e;
    border-color: #22918e;
    border-radius: 1rem;
}

.titolo {
  padding-top: 2rem;
  padding-bottom: 2rem;

  font-size: 2rem;
}

</style>