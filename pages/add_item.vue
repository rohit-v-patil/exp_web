
<template>
<section class="hero">
  <div class="hero-body">
	<div class="container">
    

  <div class="field">
    <label class="label" for="nameInput">Name : </label>
      <div class="control">
        <input class="input" id="nameInput" type="text" placeholder="Item Name">
      </div>
  </div>

  <div class="field">
    <label class="label" for="idInput">Item ID : </label>
      <div class="control">
        <input class="input" id="idInput" type="text" placeholder="Item ID">
      </div>
  </div>

<div class="field">
  <label class="label" for="priceInput">Price : </label>
  <div class="control">
    <input class="input" id="priceInput" type="text" placeholder="Price">
  </div>
</div>

<div class="control">
  <button type="submit" class="button is-info">Submit</button>
 </div> 

 

</div>
</div>
</section>
</template>
<style>

.item_frm{
  border: 2px;
  padding: 10px;
  width: 500px;
  align-content: center;
  margin-left: 35%;
  margin-right: 30%;
  margin-top: 5%;
  
}

.hero-body {
    background: url(/assets/img1.jpeg) center / cover;

    }
.field{
  margin-right: 30%;
  margin-left: 30%;
}
.button{
  margin-right: 30%;
  margin-left: 30%;
}
</style>
