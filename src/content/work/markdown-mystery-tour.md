---
title: Stage Markodex
publishDate: 2024-06-07 00:00:00
img: /assets/marko.PNG
img_alt: Image illustrative de la création de site web chez Markodex
description: |
  Stage 
tags:
  - Stage
  - Développement Web
  - WordPress
---

<div class="container">
  <div class="section hidden">
    <h2 class="titre-section-reduit">Contexte</h2>
    <p>J'ai effectué mon stage chez Markodex, une entreprise spécialisée dans les solutions de marquage industriel. L'objectif principal de ce stage était de développer un site web en utilisant WordPress, tout en me familiarisant avec les différentes technologies et méthodologies de développement web utilisées par l'entreprise.</p>
    <div class="info-encadre">
      <h5>Informations sur l'entreprise :</h5>
      <p><strong>Nom :</strong> Markodex</p>
      <p><strong>Spécialisation :</strong> Solutions de marquage industriel, étiquetage et traçabilité</p>
      <p><strong>Localisation :</strong> Ezanville, France</p>
    </div>
  </div>
</div>

<div class="section hidden">
  <h2 class="texte-reduit">Markodex</h2>
  <h5>1. Historique de l'entreprise</h5>
  <p>Fondée en 2010, Markodex s'est rapidement imposée comme un acteur majeur dans le domaine des solutions de marquage industriel. L'entreprise propose une large gamme de produits incluant des imprimantes à jet d'encre, des étiqueteuses et des solutions de traçabilité pour divers secteurs industriels.</p>

  <h5>2. Les activités de l'entreprise aujourd'hui</h5>
  <p>Markodex offre des solutions complètes de marquage industriel et d'étiquetage, notamment des imprimantes à jet d'encre, des étiqueteuses automatiques et des consommables. L'entreprise se distingue par la fiabilité et l'innovation de ses produits, garantissant une traçabilité et un codage efficaces des emballages et des produits.</p>

  <h5>3. Situation actuelle de l'entreprise</h5>
  <p>Markodex continue de croître et d'innover dans le domaine du marquage industriel. Avec une équipe de professionnels dévoués, l'entreprise est reconnue pour sa capacité à fournir des solutions sur mesure et à répondre aux besoins spécifiques de ses clients dans différents secteurs industriels.</p>
</div>

<div class="section hidden">
  <h1 class="texte-reduit">Mission</h1>
  <p class="content">
    Durant ce stage, mes missions incluaient :
    <ul>
      <li>Analyse des besoins des clients et définition des spécifications techniques pour le site web</li>
      <li>Développement et intégration de thèmes et plugins WordPress</li>
      <li>Optimisation SEO et mise en place des bonnes pratiques de référencement</li>
      <li>Tests et débogage du site web pour assurer sa fonctionnalité et sa performance</li>
    </ul>
  </p>
</div>

</div>

<div class="section hidden">
  <h2 class="titre-section-reduit">Documents du projet</h2>
  <p>Ci-dessous, les documents relatifs à ce stage à télécharger ou consulter :</p>

  <h2 class="titre-section-reduit2">Attestation de stage</h2>
  <ul>
    <li><a href="/assets/attestation_markodex.pdf" target="_blank">Télécharger l'attestation</a></li>
  </ul>

  <h2 class="titre-section-reduit2">Bilan de stage</h2>
  <ul>
    <li><a href="/assets/bilan_markodex.pdf" target="_blank">Télécharger le bilan de stage</a></li>
  </ul>
</div>

<style>
  .texte-reduit {
    font-size: 25px; /* Ajustez cette valeur selon vos besoins */
  }
  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .section {
    width: 100%;
    max-width: 800px;
    margin: 10px 0;
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.6s ease-out, transform 0.6s ease-out;
  }
  .section.show {
    opacity: 1;
    transform: translateY(0);
  }
  .section img {
    width: 100%;
    max-width: 600px; /* Ajustez selon la largeur maximale désirée pour les images */
    margin: 20px auto; /* Centrer l'image */
  }
  .texte-reduit {
    margin-bottom: 15px; /* Réduit l'espace sous le titre pour une meilleure cohérence visuelle */
  }
  .content {
    margin-bottom: 10px; /* Contrôle l'espace autour du paragraphe pour un meilleur rendu */
  }
  .titre-section-reduit {
    font-size: 25px; /* Taille de la police spécifiquement réduite pour ce titre */
  }
  .titre-section-reduit2 {
    font-size: 15px; /* Taille de la police spécifiquement réduite pour ce titre */
  }
  .info-encadre {
    border: 1px solid #ccc;
    padding: 10px;
    background-color: #f9f9f9;
    margin: 20px 0; /* Espacement au-dessus et en dessous de l'encadré */
    width: 100%;
    max-width: 600px;
  }
  .info-encadre h2 {
    margin-top: 0;
  }
  .hidden {
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.6s ease-out, transform 0.6s ease-out;
  }
  .show {
    opacity: 1;
    transform: translateY(0);
  }
</style>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    const sections = document.querySelectorAll('.section');

    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('show');
          observer.unobserve(entry.target);
        }
      });
    }, {
      threshold: 0.1
    });

    sections.forEach(section => {
      observer.observe(section);
    });
  });
</script>
