<template>
<div>
  <select @change="games" id="order">
    <option value="% de desconto">% de desconto</option>
    <option value="Maior">Maior preço</option>
    <option value="Menor">Menor preço</option>
    <option value="Titulo">Titulo</option>
  </select>
  </div>
</template>

<script>
export default {


  name: "Ordenation",
};
</script>

<style>
#order {
  position: relative;
  float: right;  
  border: 1px solid black;
  border-radius: 10px;
  background-color: #0B1641;
  width: 180px;
  height: 50px;
  top: -50px;
  color: white;
  box-shadow: 0px 5px 0px #252323ba;

}
</style>
