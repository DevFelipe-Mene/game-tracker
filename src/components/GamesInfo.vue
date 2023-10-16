<template>
  <div>
    <div id="list" v-for="game in games">
      <div id="info">
        <p id="title">{{ game.title }}</p>
        <p id="price">{{ game.salePrice }}</p>
        <p id="percent">{{ formatPercet }}</p>
        <button id="detail-button">Detalhes</button>
      </div>
    </div>
  </div>
</template>

<script>
import gameData from "../gamesInfo.json";

function formatPercent(games) {
    const formated = games.savings.toFixed(0);
    console.log(formated)
    return formated;
}

export default {
  name: "GameInfo",
  data() {
    return { games: gameData };
  },
};
</script>

<style>
#list {
  margin-top: 20px;
  border: 1px solid black;
  border-radius: 10px;
  width: 380px;
  height: 251px;
  display: inline-flex;
  margin-left: 10px;
  box-shadow: 0px 5px 0px #252323ba;

}

#info {
  background-color: #0b1641;
  height: 125px;
  position: relative;
  top: 125px;
  width: 380px;
  border-radius: 5px;
  color: white;
}

#title {
  font-family: Roboto;
  font-size: 24px;
  font-weight: 300;
  line-height: 28px;
  letter-spacing: 0em;
  text-align: left;
}

#price{
    position: relative;
    float: right;
    top: 60px;
    right: 100px;
}


#detail-button {
    position: relative;
    top: 40px;
  border: 1px solid black;
  border-radius: 10px;
  width: 116px;
  height: 39px;
  background-color: #c70160;
  color: white;
  font-size: 18px;
  margin-left: 10px;
}
</style>
