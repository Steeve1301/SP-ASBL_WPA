<template>
  <div class="view-home container mt-5">
    <div class="row m-0">
      <div class="aboutus col-md-4 d-flex flex-column">
        <img class="logo" src="logo.png" alt="Logo" />
        <ul class="d-flex flex-column text-left">
          <h4 class="text-center">Numéro d'appel: <a href="tel:060313480">060/31.34.80</a></h4>
          <li>Option 1: Service de médiation de dettes</li>
          <li>Option 2: Service social</li>
          <li>Option 3: Informations générales</li>
          <h4 class="text-center">Numéro de fax: <a href="fax:060346445">060/34.64.45</a></h4>
          <li class="text-center">52 Boulevard du Fort, 5660 Mariembourg</li>
        </ul>
      </div>

      <div class="col-md-6 offset-md-2 d-flex align-items-center pop-home">
        <p>Bienvenue sur le site de l'Asbl Solidarités Plurielles de l'Entre-Sambre et Meuse (précédemment Asbl Solidarité Alimentaire de l'Entre-Sambre et Meuse). Vous y trouverez des informations sur la création de l'association, son histoire ainsi que les différents services qu'elle propose. Si vous souhaitez obtenir davantage de renseignements, n'hésitez pas à nous contacter.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #000000;
  text-decoration: none;
}
.pop-home{
  border: 10px solid #343A40;
  background:white;

}

</style>
