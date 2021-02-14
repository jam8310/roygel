<template>
  <section>
    <!-- CATALOGUE -->

    <div class="catalogue">
      <h2>Notre catalogue</h2>
    </div>

    <!-- CRUSTACE  -->

    <div class="produits">
      <div class="produit">
        <div class="crustace1 produit1"></div>
        <div class="crustace2 produit2"></div>
        <div class="text">
          <span class="spanRight">01</span>
          <h4 class="textRight">Crustacés</h4>
        </div>
      </div>

      <!-- MOLLUSQUE -->

      <div class="produit">
        <div class="text">
          <span class="spanLeft">02</span>
          <h4 class="textLeft">Mollusques</h4>
        </div>
        <div class="mollusque1 produit1"></div>
        <div class="mollusque2 produit2"></div>
      </div>
  
      <!-- POISSON ET FILETS -->

      <div class="produit">
        <div class="poisson1 produit1"></div>
        <div class="poisson2 produit2"></div>
        <div class="text">
          <span class="spanRight">03</span>
          <h4 class="textRight size">Poissons & filets</h4>
        </div>
      </div>

      <!-- VOLAILLES ET VIANDES -->

      <div class="produit">
        <div class="text">
          <span class="spanLeft">04</span>
          <h4 class="textLeft">Volailles & Viandes</h4>
        </div>
        <div class="viande1 produit1"></div>
        <div class="viande2 produit2"></div>
      </div>

      <!-- LEGUMES & AROMATES -->

      <div class="produit">
        <div class="legume1 produit1"></div>
        <div class="legume2 produit2"></div>
        <div class="text">
          <span class="spanRight">05</span>
          <h4 class="textRight size">Légumes & Aromates</h4>
        </div>
      </div>

      <!-- TAPAS & PLATS CUISINES -->

      <div class="produit">
        <div class="text">
          <span class="spanLeft">06</span>
          <h4 class="textLeft">Tapas & Plats Cuisinés</h4>
        </div>
        <div class="tapas1 produit1"></div>
        <div class="tapas2 produit2"></div>
      </div>

      <!-- FRITES & POMME DE TERRE -->

      <div class="produit">
        <div class="frite1 produit1"></div>
        <div class="frite2 produit2"></div>
        <div class="text">
          <span class="spanRight">07</span>
          <h4 class="textRight size">Frites & Pomme de terre</h4>
        </div>
      </div>

      <!-- TAPAS & PLATS CUISINES -->

      <div class="produit">
        <div class="text">
          <span class="spanLeft">08</span>
          <h4 class="textLeft">Pains & Viennoiseries</h4>
        </div>
        <div class="pain1 produit1"></div>
        <div class="pain2 produit2"></div>
      </div>

      <!-- DESSERTS -->

      <div class="produit">
        <div class="dessert1 produit1"></div>
        <div class="dessert2 produit2"></div>
        <div class="text">
          <span class="spanRight">09</span>
          <h4 class="textRight size">Desserts</h4>
        </div>
      </div>

      <!-- GLACES -->

      <div class="produit">
        <div class="text">
          <span class="spanLeft">10</span>
          <h4 class="textLeft">&nbsp;Glaces</h4>
        </div>
        <div class="glace1 produit1"></div>
        <div class="glace2 produit2"></div>
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
.produit{
  width:80%;
  margin: 5px auto;
  position: relative;
  height: 150px;
  overflow: hidden;
  display: flex;
  align-items: center;
}
.produit1{
  height:100%;
  background-size: cover;
}
.produit2{
  height:100%;
  background-size: cover;
}
/* RIGHT */

.text{
  width:30%;
  height:100%;
  position: relative;
}
.produits span{
  position: absolute;
  top: 10%;
  font-size: 80px;
  font-family: 'fontP';
  font-weight: bold;
  letter-spacing: -5px;
}
.produits h4{
  position: absolute;
  top:65%;
  text-transform: uppercase;
  font-size: 20px;
  font-family: 'fontP';
}

/* LEFT */

.textLeft, .spanLeft{
  left:0;
}
.spanRight{
  right: 5px;
}
.textRight{
  right:0;
}


/* CRUSTACE */

.crustace1{
  width:40%;
  background-image: url('../assets/img/crustace1.jpg');
  background-position-x: 50%;
  background-position-y: 50%;
 
}
.crustace2{
  width:30%;
  margin: 0 5px;
  background-image: url('../assets/img/crustace2.jpg');
  background-position-y: 50%;
}

/* MOLLUSQUE*/

.mollusque1{
  width:28%;
  margin: 0 5px;
  background-image: url('../assets/img/mollusque1.jpg');
  background-position-x: 40%;
  background-position-y: 45%;
}
.mollusque2{
  width:42%;
  background-image: url('../assets/img/mollusque2.jpg');
  background-position-y: 50%;
}


/* POISSON ET FILET */

.poisson1{
  width:40%;
  background-image: url('../assets/img/poisson1.jpg');
  background-position-x: 35%;
  background-position-y: 15%;
}
.poisson2{
  width:30%;
  margin: 0 5px;
  background-image: url('../assets/img/poisson2.jpg');
  background-position-y: 50%;
}

/* VIANDE*/

.viande1{
  width:28%;
  margin: 0 5px;
  background-image: url('../assets/img/viande1.jpg');
  background-position-x: 0%;
  background-position-y: 100%;
}
.viande2{
  width:42%;
  background-image: url('../assets/img/viande2.jpg');
  background-position-y: 50%;
}

/* LEGUMES ET AROMATES */

.legume1{
  width:40%;
  background-image: url('../assets/img/legume1.jpg');
  background-position-x: 35%;
  background-position-y: 100%;
}
.legume2{
  width:30%;
  margin: 0 5px;
  background-image: url('../assets/img/legume2.jpg');
  background-position-y: 50%;
}

/* TAPAS & PLATS CUISINES*/

.tapas1{
  width:28%;
  margin: 0 5px;
  background-image: url('../assets/img/tapas1.jpg');
  background-position-x: 55%;
  background-position-y: 100%;
}
.tapas2{
  width:42%;
  background-image: url('../assets/img/tapas2.jpg');
  background-position-y: 15%;
}

/* FRITES & POMME DE TERRE */

.frite1{
  width:40%;
  background-image: url('../assets/img/frite1.jpg');
  background-position-x: 35%;
  background-position-y: 100%;
}
.frite2{
  width:30%;
  margin: 0 5px;
  background-image: url('../assets/img/frite2.jpg');
  background-position-y: 80%;
}

/* PAINS & VIENNOISERIES*/

.pain1{
  width:28%;
  margin: 0 5px;
  background-image: url('../assets/img/pain1.jpg');
  background-position-x: 55%;
  background-position-y: 100%;
}
.pain2{
  width:42%;
  background-image: url('../assets/img/pain2.jpg');
  background-position-y: 15%;
}

/* DESSERTS */

.dessert1{
  width:40%;
  background-image: url('../assets/img/dessert1.jpg');
  background-position-x: 35%;
  background-position-y: 100%;
}
.dessert2{
  width:30%;
  margin: 0 5px;
  background-image: url('../assets/img/dessert2.jpg');
  background-position-y: 55%;
}

/* GLACES */

.glace1{
  width:28%;
  margin: 0 5px;
  background-image: url('../assets/img/glace1.jpg');
  background-position-x: 20%;
  background-position-y: 50%;
}
.glace2{
  width:42%;
  background-image: url('../assets/img/glace2.jpg');
  background-position-y: 50%;
}
</style>
