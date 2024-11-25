<script setup>

</script>

<template>

<div class="container">
<div class="row">
  <div class="col">
  
      <h1 class="text-center ma-3">учет товаров</h1>
      <div class="mb-3">
      <label for="name" class="form-label">название</label>
      <input type="text" class="form-control" id="name" >
     </div>


     <div class="mb-3">
      <label for="date" class="form-label">Дата дабовления </label>
  <input type="date" class="form-control" id="date" >
     </div>



     <div class="mb-3">
      <label for="count" class="form-label">количество</label>
  <input type="numder" class="form-control" id="count" >
     </div>

     

     <div class="mb-3">
      <label for="price" class="form-label">цена</label>
  <input type="namber" class="form-control" id="price" >
     </div>



     <button type="button" class="btn btn-dark">добавить</button>





</div>
</div>
<div class="row row-cols-1 row-cols-md-2 mt-4">
  <div class="col">
    <div class="card">
 
      <div class="card-body">
        <h5 class="card-title">HP</h5>
        <p class="card-text">$1000</p>
        <p class="card-text">x10</p>
        <p class="card-text">25.11.2024</p>
      </div>
      <div class="card-footer">
        <button class="btn btn-outline-danger">Удалить</button>
      </div>
    </div>
  </div>

</div>
<div class="row">
  <div class="col my-4">
    <h3 class="text-end">общая сумма товаров $423513</h3>
  </div>
</div>




</div>
</template>

