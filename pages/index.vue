<template>
  <div class="container">
    <HeaderTop></HeaderTop>

    <main>

    <!-- EN TETE -->

    <div class="effet">
      <img src="../assets/img/effet.png" class="brosse" alt="">
      <span>Notre Vision</span>
    </div>
    <p>
      Roy gel est une petite entreprise familiale ouverte depuis 1973.... <br>
      Nous vous proposons un tarif général de produits surgelés.
      Notre force est le service , la confiance et la determination à vous donner une entière satisfaction , autant sur la qualité nos produits ainsi que sur la livraison.
    </p>
    <catalogue></catalogue>
    </main>
  </div>
</template>

<script>
import HeaderTop from '@/components/Header'
import Catalogue from '@/components/Catalogue'

export default {
  components: {
    HeaderTop,
    Catalogue
  }
}
</script>

<style>

/* FONT FAMILY */
@font-face {
  font-family: 'fontMenu';
  src: url("../assets/fonts/CoreSansD75Black.otf");
 }
@font-face {
  font-family: 'fontP';
  src: url("../assets/fonts/CoreSansD45Medium.otf");
 }


.container{
  width:100%;
  margin:0 auto;
}
a{
  text-decoration: none;
  color: #333;
}

/* MAIN */

.effet{
  width:100%;
  height:7vw;
  position: relative;
  margin-top: 6vw;
  align-items: center;
}
.effet .brosse{
  position: absolute;
  left: 50%; top:50%;
  transform: translate(-50%, -50%);
  width:23vw;
}
.effet span{
  position: absolute;
  top: 50%; left: 50%;
  transform: translate(-50%, -50%);
  font-size:1.9vw;
  text-transform: uppercase;
  font-weight: bold;
  color: #f1f1f1;
}
p{
  position: relative;
  text-align: center;
  padding-top:10px;
  width:80%;
  margin: 0 auto;
  font-size: 1.5vw;
  padding-bottom:5vw;
  font-family: 'fontMenu';
  color: #999;
  line-height:2.5vw;
}
</style>
