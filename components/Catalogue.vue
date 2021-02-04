<template>
  <section>
    <!-- CATALOGUE -->

    <div class="catalogue">
      <h2>Notre catalogue</h2>
    </div>

    <!-- CRUSTACE  -->

    <div class="produits">
      <div class="one">
        <div class="crustace1"></div>
        <div class="crustace2"></div>
        <div class="text">
          <span class="spanRight">01</span>
          <h4 class="textRight">Crustacés</h4>
        </div>
      </div>

      <!-- MOLLUSQUE -->

      <div class="two">
        <div class="text">
          <span class="spanLeft">02</span>
          <h4 class="textLeft">Mollusques</h4>
        </div>
        <div class="mollusque1"></div>
        <div class="mollusque2"></div>
      </div>
  
      <!-- POISSON ET FILETS -->

      <div class="three">
        <div class="poisson1"></div>
        <div class="poisson2"></div>
        <div class="text">
          <span class="spanRight">03</span>
          <h4 class="textRight size">Poissons et filets</h4>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
/*  CATALOGUE  */

.catalogue{
  width:80%;
  margin: 0 auto;
  position: relative;
  height: 150px;
  overflow: hidden;
  background-image: url('../assets/img/catalogue.jpg');
  background-position-x: 50%;
  background-position-y: 85%;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
}

h2{
  position: absolute;
  top:50%;
  transform: translateY(-50%);
  font-size: 40px;
  color: #fff;
  text-transform: uppercase;
  font-family: 'fontMenu';
  text-shadow: -2.5px 2.5px 0 #000;
}

/* CRUSTACE */
.one{
  width:80%;
  margin: 5px auto;
  position: relative;
  height: 150px;
  overflow: hidden;
  display: flex;
  align-items: center;
}
.crustace1{
  width:40%;
  height:100%;
  background-image: url('../assets/img/crustace1.jpg');
  background-position-x: 50%;
  background-position-y: 50%;
  background-size: cover;
}
.crustace2{
  width:30%;
  height:100%;
  margin: 0 5px;
  background-image: url('../assets/img/crustace2.jpg');
  background-position-y: 50%;
  background-size: cover;
}
.text{
  width:30%;
  height:100%;
  position: relative;
}
.produits span{
  position: absolute;
  top: 17%;
  font-size: 100px;
  font-family: 'fontP';
  font-weight: bold;
  letter-spacing: -5px;
}
.produits h4{
  position: absolute;
  top:87%;
  text-transform: uppercase;
  font-size: 20px;
  font-family: 'fontP';
}

/* MOLLUSQUE*/

.two{
  width:80%;
  margin: 5px auto;
  position: relative;
  height: 150px;
  overflow: hidden;
  display: flex;
  align-items: center;
}
.mollusque1{
  width:28%;
  height:100%;
  margin: 0 5px;
  background-image: url('../assets/img/mollusque1.jpg');
  background-position-x: 40%;
  background-position-y: 45%;
  background-size: cover;
}
.mollusque2{
  width:42%;
  height:100%;
  background-image: url('../assets/img/mollusque2.jpg');
  background-position-y: 50%;
  background-size: cover;
}
.textLeft, .spanLeft{
  left:0;
}
.spanRight{
  right: 5px;
}
.textRight{
  right:0;
}

/* POISSON ET FILET */

.three{
  width:80%;
  margin: 5px auto;
  position: relative;
  height: 150px;
  overflow: hidden;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}
.poisson1{
  width:40%;
  height:100%;
  background-image: url('../assets/img/poisson1.jpg');
  background-position-x: 35%;
  background-position-y: 15%;
  background-size: cover;
}
.poisson2{
  width:30%;
  height:100%;
  margin: 0 5px;
  background-image: url('../assets/img/poisson2.jpg');
  background-position-y: 50%;
  background-size: cover;
}

</style>
