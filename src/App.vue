<template>

<div>
  <Navbar />
  <div>
    <p style="color: white; font-size: 36px; font-family: 'Roboto';">Ofertas</p>
    <SearchBar />
    <Ordenation />
  </div>
  <br/>
  <div>
    <GameInfo />
  </div>
  <Footer />
  
</div>
</template>

<script>
  import Navbar from "./components/Navbar.vue"
  import Ordenation from "./components/Ordenation.vue"
  import SearchBar from "./components/SearchBar.vue"
  import GameInfo from "./components/gamesInfo.vue"
  import Footer from "./components/Footer.vue"


  export default{
    components:{
      Footer,
      Navbar,
      Ordenation,
      SearchBar,
      GameInfo

    }
  }
</script>
<style>
  * {
    font-family: 'Roboto';
    padding: 0;
    margin: 0;
    box-sizing: border-box;

  }

  .main-container {
    margin: 50px;
    min-height: 250px;
  }

  h1 {
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
    color: #222;
  }
</style>
