<template>
  <div class="home">
    <div class="intro-wrapper">
      <div class="image"></div>
      <div>
        <h1 class="title3 name">Alexandre Curot</h1>
        <p class="text2 job">Développeur web</p>
        <p>Bordeaux</p>
      </div>
    </div>

    <h2 class="title">Compétences</h2>
    <p class="skills-wrapper">
      HTML, CSS, <span class="blue">Symfony</span>, Mysql, <span class="blue">Vue</span> 
      </p>
     
      

   

    <h2 class="title">Formation</h2>
    <div class="diplomas-wrapper">
      <h3 class="title2">Développement web</h3>
        <p class="title3">2023</p>
        <p class="text2">Formations et prestations</p>
        <p>Apprentissage du Vue.js, perfectionnement sur symfony, et intervention sur diverses plateformes web tel que Wordpress et diverses CMS...</p>
        <h3 class="title2">Formation de Développeur Web</h3>
        <p class="title3">2017-2022</p>
        <p class="text2">OpenClassrooms.</p>
        <p>Formation en autonomie dirigé php, html, symfony, création de boutiques, forum, plateformes diverses</p>
        <h3 class="title2">Formation Musique Cycle Pro: 3 années de professionnalisation dans le milieu musical et l’art de la scène</h3>
        <p class="title3">2013-2017</p>
        <p class="text2">Ciam Bordeaux.</p>
        <p>Professionnalisation dans le domaine des musique actuelles aux travers des instruments et pratique du solfège</p>
        <h3 class="title2">Baccalauréat Général: Littéraire</h3>
        <p class="title3">2012</p>
        <p class="text2">Lycée privé général: Cours Polles</p>
      </div>


      <h2 class="title">Expériences</h2>
    <div class="experiences-wrapper">
      
        <h3 class="title2">Aeroport Merignac</h3>
        <p class="title3">2022-2023</p>
        <p class="text2">Relay</p>
        <p>Formation sécurité, conseils clientèles et gestion logistiques</p>
        <h3 class="title2">Hôte de caisse</h3>
        <p class="title3">2019-2022</p>
        <p class="text2">E.Leclerc (Etudiant)</p>
        <p>Vente et conseils clitentèles, logistiques</p>
        <h3 class="title2">Développement web</h3>
        <p class="title3">2021</p>
        <p class="text2">AgencyCom</p>
        <p>Intervention sur diverses CMS customs et Wordpress, modifications de styles, ajout de fonctionnalités, audits, conseils techniques</p>
      </div>
    </div>
</template>

<script>
export default {
  name: 'HomeVue',
  
}
</script>

<style scoped>
p.text2 {
    color: #5c5c5c;
}
.home {
    max-width: 1000px;
    padding: 20px;
    margin: auto;
}
.intro-wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 2rem;
}
.image {
  background-image: url('@/assets/img/alex.jpg');
  width: 150px;
  height: 150px;
  border-radius: 20px;
  background-position: 50% 10%;
  margin-right: 20px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.name {
  font-size: 28px;
  line-height: 24px;
  text-transform: uppercase;
}
.job {
  font-size: 18px;
  margin-bottom: 24px;
}

.skills-wrapper {
  text-align: center;
}
.skills-wrapper span.important {
  color: var(--color-main);
  font-weight: bold;
}

.diplomas-wrapper > div:nth-child(n + 2),
.experiences-wrapper > div:nth-child(n + 2) {
  margin-top: 2rem;
}

.details {
  padding-left: 20px;
}

.title {
  font-size: 20px;
  font-weight: bold;
  letter-spacing: 4px;
  text-align: center;
  margin-bottom: 1rem;
  margin-top: 4rem;
  text-transform: uppercase;
}

.title2 {
  font-size: 18px;
  font-weight: bold;
  color: var(--accent-color);
  
}
.title3 {
  font-size: 18px;
  font-weight: bold;
  color:white;
 
}

.text4 {
  text-align: center;
}
.blue{
  color:var(--accent-color);
  font-weight: 700;
}
.white{
  color:white;
}

</style>