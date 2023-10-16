<template>
  <div>
    <div id="nav">
      <img id="logo" src="../assets/logo.png" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
#nav {
  position: relative;
  right: 120px;
  width: 118%;
  background-color: #0b1641;
  padding: 5px 50px;
  display: flex;
  justify-content: flex-start;
  box-shadow: 0px 5px 0px #252323ba;

}

#nav {
  margin: auto;
  margin-left: 0;
  margin-bottom: 25px;
}

#logo {
  width: 194px;
  height: 32.14px;
}
</style>
