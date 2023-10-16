<template>
  <div id = "searchBar">
    <i class="fas fa-search" aria-hidden="true"></i>
    <input id="searchBar" type="text" placeholder="Procurar" />
  </div>
</template>

<script>
  export default {
    name: "SearchBar"
  }

</script>

<style >
  #searchBar{
    width: 380px;
    height: 50px;
    border: 1px solid black;
    border-radius: 8px;
    background-color: #0B1641;
    color: white  ;
    box-shadow: 0px 5px 0px #252323ba;

  }
</style>
