<template>
  <header>
    <div class="img">
      <img src="../assets/img/banniere.jpg" class="headerImg" alt="">
      <img src="../assets/img/logo.png" class="logo" alt="">
    </div>
    <nav class="desktop">
      <ul>
        <li class="item"> <a href="#">vision</a></li>
        <li class="item itemLeft"> <a href="#">Catalogue</a></li>
        <li> </li>
        <li> </li>
        <li class="item"> <a href="#">Localisation</a></li>
        <li class="item"> <a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
}
</script>

<style scoped>
/*  BANNIERE  */
.img{
  position: relative;
  width:100%;
}
.headerImg{
  width:100%;
  height:100%;
}
.logo{
  position: absolute;
  top:57%;left:50.2%;
  transform: translateX(-50%);
  /* width:212px; */
  width:20%;
  height:auto;
  border:1px solid #333;
  border-radius: 50%;
}
/*  FIN BANNIERE  */

/*  NAV  */
nav{
  max-width: 100%;
}
ul{
  width:100%;
  display: flex;
  justify-content:space-around;
  align-items: center;
  position: relative;
  padding-left:10px;
}
ul li{
  list-style-type: none;
  text-align: center;
  position: relative;
}
.item{
  max-width: 120px;
  text-transform: uppercase;
  font-weight: bold;
  font-size: 17px;
  font-family: 'fontMenu';
}
.itemLeft{
  padding-left:20px;
}
/*  FIN  NAV  */
</style>
