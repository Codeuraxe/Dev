---
title: "Veille Technologique"
publishDate: "2024-06-07"
img: "/assets/cyber.jpeg"
img_alt: "Image illustrative de la création de site web chez Markodex"
description: "Stage dans le secteur informatique chez Markodex"
tags:
  - Stage
  - Développement Web
  - WordPress
---

<div class="section hidden">
  <h2 class="titre-section-reduit">Veille Technologique</h2>
  <p><strong>Qu'est-ce que la veille technologique ?</strong><br>
  La veille technologique consiste à surveiller les évolutions techniques et les innovations dans un secteur d’activité. Elle inclut la collecte et la diffusion d’informations sur les changements en matière de recherche, développement, brevets, lancement de nouveaux produits, matériaux, processus, concepts, etc. Cela permet d’anticiper les impacts potentiels sur l’environnement et l’organisation.<br><br>
      
  <strong>Les principaux outils de ma veille</strong><br>
  J'ai effectué ma veille technologique grâce à des newsletters telles que Feedly, un agrégateur de flux RSS qui permet de suivre en temps réel les menaces émergentes dans le domaine de la cybersécurité. En plus des informations fournies par Feedly, j'utilise des newsletters spécifiques comme celle de Dark Reading et CyberScoop pour rester à jour sur les dernières actualités en cybersécurité. Je consulte également régulièrement des sites spécialisés comme Hitek.fr et Hardware.fr pour les dernières tendances en technologie.<br><br>

  <strong>Sujet de ma veille</strong><br>
  Pour ma veille technologique, j'ai choisi de traiter le sujet de la cybersécurité. Ma thématique est : Quels sont les enjeux et les innovations en cybersécurité ?<br><br>

  Afin de répondre à cette thématique, ma veille se repose sur trois thèmes principaux :<br><br>

  <strong>Thème 1 : Qu'est-ce que la cybersécurité ?</strong><br>
  La cybersécurité est la pratique consistant à protéger les systèmes, les réseaux et les programmes contre les attaques numériques visant à accéder, modifier ou détruire des informations sensibles, extorquer de l'argent aux utilisateurs ou interrompre les processus commerciaux normaux.<br>
  Source : Kaspersky<br><br>

  <strong>Thème 2 : Les défis de la cybersécurité</strong><br>
  Les cyberattaques deviennent de plus en plus complexes et difficiles à détecter. Les cybercriminels utilisent des techniques avancées pour contourner les défenses traditionnelles. Les cyberattaques peuvent avoir des conséquences dévastatrices pour les entreprises, notamment des pertes financières importantes, une atteinte à la réputation, et des interruptions de service.<br>
  Source : Symantec<br><br>

  <strong>Thème 3 : Innovations en cybersécurité</strong><br>
  L'IA et l'apprentissage automatique jouent un rôle de plus en plus important dans la cybersécurité. Ces technologies permettent d'analyser rapidement de grandes quantités de données pour détecter des comportements suspects et identifier des menaces potentielles en temps réel.<br>
  Source : McAfee<br><br>

  La technologie blockchain offre une méthode sécurisée et transparente pour réaliser des transactions. Elle est de plus en plus utilisée pour renforcer la sécurité des données et prévenir les fraudes dans diverses industries.<br>
  Source : Deloitte<br><br>

  <strong>Conclusion</strong><br>
  La veille technologique en cybersécurité permet de rester informé sur les dernières menaces et innovations dans ce domaine crucial. En suivant les évolutions et en adoptant de nouvelles technologies, les entreprises peuvent mieux se protéger contre les cyberattaques et garantir la sécurité de leurs informations sensibles.
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
