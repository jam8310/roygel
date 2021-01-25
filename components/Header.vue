<template>
  <header>
    <div class="img">
      <img src="../assets/img/banniere.jpg" class="headerImg" alt="">
      <img src="../assets/img/logo.png" class="logo" alt="">
    </div>
    <nav>
      <ul>
        <li class="item"> <nuxt-link to="/"> vision </nuxt-link></li>
        <li class="item"> <nuxt-link to="/">Catalogue </nuxt-link></li>
        <li> </li>
        <li> </li>
        <li class="item "> <nuxt-link to="/">Localisation </nuxt-link></li>
        <li class="item "> <nuxt-link to="/">Contact </nuxt-link></li>
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
  height:auto;
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
ul{
  width:100%;
  display: flex;
  justify-content:space-around;
  align-items: center;
  position: relative;
  /* top:-200px; */
}
ul li{
  list-style-type: none;
  text-align: center;
  position: relative;
  padding: 10px;
}
.item{
  text-transform: uppercase;
  font-weight: bold;
  font-size: 1.5vw;
  font-family: 'fontMenu';
}
.itemLeft{
  position: relative;
  left:-15Px;
}
/*  FIN  NAV  */
</style>
