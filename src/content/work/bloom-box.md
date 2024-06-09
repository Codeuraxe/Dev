---
title: MediatekDocuments
publishDate: 2019-12-01 00:00:00
img: /assets/mediatekdoc.PNG
img_alt: A bright pink sheet of paper used to wrap flowers curves in front of rich blue background
description: |
 Projet C#
tags:
  - Dev
  - Branding
  - Backend
---

<div class="container">
  <div class="section">
  <h2 class="titre-section-reduit">Contexte</h2>
    <p>MediaTek86 est un réseau qui gère les médiathèques de la Vienne, et qui a pour rôle de fédérer les prêts de livres, DVD et CD et de développer la médiathèque numérique pour l’ensemble des médiathèques du département.

Afin de gérer le catalogue et les commandes de documents, MediaTek86 a confié un projet de développement d'une application de gestion à la société InfoTechServices 86.<br>
    <a href="/assets/contexteFormation.pdf" target="_blank">Télécharger le contexte détaillé</a>
</p>
  </div>
  <div class="section">
    <h1 class="texte-reduit">Mission</h1>
    <p class="content">
      Le but de cet atelier est de faire évoluer une application de bureau (C#) exploitant une API REST (PHP) pour l'accès à une base de données relationnelle MySQL et qui permet de gérer les documents des médiathèques de la chaîne MediaTek86. Un premier développeur s'est occupé de la construction de la base de données et du développement de certaines fonctionnalités de l'application.

Il s'agit d'une application de bureau, prévue d'être installée sur plusieurs postes dans la médiathèque et accédant à la même base de données. Le but est d'y ajouter de nouvelles fonctionnalités pour réaliser la gestion du catalogue des médiathèques et des commandes de documents.<br>
      <a href="/assets/dossierDocAP3.pdf" target="_blank">Télécharger le contrat de développement</a>
    </p>
  </div>
</div>

<div class="content">
  <h2 class="titre-section-reduit">Résumé des missions effectuées</h2>
  <div class="content">
    <h5>Mission 1 : Gérer les documents </h5>
    <p><strong>Ajout, modification et suppression des documents</strong> : 
      J'ai développé des fonctionnalités permettant d'ajouter, modifier et supprimer des livres, des DVD et des revues. J'ai mis en place des conditions pour s'assurer que la suppression d'un document n'est possible que s'il n'est pas lié à une commande en cours.
    </p>
  </div>

  <div class="content">
    <h5>Mission 2 : Gérer les commandes </h5>
    <p><strong>Gérer les commandes de livres ou de DVD </strong> : 
      J'ai créé une interface permettant de gérer les différentes étapes des commandes (enregistrement, réception, livraison, paiement). J'ai automatisé l'ajout des exemplaires commandés dans la base de données.
    </p>
    <p><strong>Gérer les commandes de revues </strong> : 
      J'ai développé une fonctionnalité permettant de gérer les commandes de revues, incluant la réalisation d'abonnements et leur renouvellement automatique. J'ai mis en place une interface pour afficher les revues commandées et gérer les renouvellements.
    </p>
  </div>

  <div class="content">
    <h5>Mission 3 : Gérer le suivi de l'état des exemplaires </h5>
    <p><strong>Suivi de l'état des exemplaires</strong> : 
      J'ai développé une fonctionnalité pour suivre l'état des documents physiques, incluant les livres, les DVD et les revues. J'ai créé des listes pour gérer les états tels que "neuf", "usagé", "détérioré", et "inutilisable".
    </p>
  </div>

  <div class="content">
    <h5>Mission 4 : Mettre en place des authentifications </h5>
    <p><strong>Authentification et gestion des droits d'accès</strong> : 
      J'ai mis en place un système d'authentification pour gérer les différents niveaux d'accès selon les rôles (administrateurs, employés). J'ai intégré Keycloak pour gérer l'accès des utilisateurs et restreindre certaines fonctionnalités aux administrateurs uniquement.
    </p>
  </div>

  <div class="content">
    <h5>Mission 5 : Assurer la sécurité, la qualité et intégrer des logs </h5>
    <p><strong>Corriger les problèmes de sécurité </strong> : 
      J'ai identifié et corrigé les problèmes de sécurité dans le code, notamment la sécurisation des appels à l'API. J'ai mis en place des procédures pour valider et accepter les correctifs via des pull requests.
    </p>
    <p><strong>Contrôler la qualité </strong> : 
      J'ai utilisé SonarQube pour effectuer une analyse statique du code et identifier les problèmes de qualité. J'ai résolu les issues détectées par SonarQube.
    </p>
    <p><strong>Intégrer des logs </strong> : 
      J'ai enregistré les actions et les erreurs dans des fichiers de logs pour faciliter le suivi et le diagnostic des problèmes.
    </p>
  </div>

  <div class="content">
    <h5>Mission 6 : documenter </h5>
    <p><strong>Créer les documentations techniques </strong> : 
      J'ai généré les documentations techniques pour l'application C# et l'API REST.
    </p>
    <p><strong>Créer la documentation utilisateur en vidéo </strong> : 
      J'ai créé une vidéo de présentation des fonctionnalités de l'application, d'une durée maximale de 10 minutes.
    </p>
  </div>

  <div class="content">
    <h5>Mission 7 : Déployer et gérer les sauvegardes des données </h5>
    <p><strong>Déployer le projet </strong> : 
      J'ai déployé l'API et la base de données chez un hébergeur. J'ai créé un installateur pour l'application C# afin de faciliter son installation.
    </p>
    <p><strong>Gérer les sauvegardes des données </strong> : 
      J'ai automatisé les tâches de sauvegarde quotidienne de la base de données pour garantir la sécurité des données.
    </p>
  </div>
</div>

<div class="content">
  <h1 class="texte-reduit">Outils et langages utilisés</h1>
  <ul>
    <li><strong>IDE :</strong> Visual Studio 2019</li>
    <li><strong>Serveur :</strong> WampServer</li>
    <li><strong>Langages :</strong> C#, PHP et SQL</li>
    <li><strong>Base de données :</strong> MySQL</li>
  </ul>

<div class="project-documents-section">
  <h2 class="titre-section-reduit">Documents du projet</h2>
  <p>Ci-dessous, les documents du projet à télécharger ou consulter :</p>

  <h2 class="titre-section-reduit2">Accès au cahier des charges</h2>
  <ul>
    <li><a href="/assets/cahierChargesAP3.pdf" target="_blank">Télécharger le cahier des charges</a></li>
  </ul>

  <h2 class="titre-section-reduit2">Accès au dossier documentaire</h2>
  <ul>
    <li><a href="/assets/dossierDocAP3.pdf" target="_blank">Télécharger le dossier documentaire</a></li>
  </ul>

  <h2 class="titre-section-reduit2">Accès au PV de recette</h2>
  <ul>
    <li><a href="/assets/pvRecetteAP3 (1).pdf" target="_blank">Télécharger le PV de recette</a></li> 
  </ul>
  <h2 class="titre-section-reduit2">Accès au modèle MCD</h2>
  <ul>
    <li><a href="/assets/mediatekDocumentsBddMCD.png" target="_blank">Accès au modèle MCD</a></li> 
  </ul>
  <h2 class="titre-section-reduit2">Accès au dépôt distant</h2>
  <ul>
    <li><a href="https://github.com/Codeuraxe/MediatekDocuments" target="_blank">Accès au dépôt distant - C#</a></li><p> En cas d'erreur, veuillez vous rendre sur <br> https://github.com/Codeuraxe puis repository</p>
  </ul>
  <h2 class="titre-section-reduit2">Accès au dépôt distant - Api</h2>
  <ul>
    <li><a href="https://github.com/Codeuraxe/rest_mediatekdocuments" target="_blank">Accès au dépôt distant - Api</a></li>
  </ul>
  <h2 class="titre-section-reduit2">Accès à l'Api en ligne</h2>
  <ul>
    <li><a href="https://mediatek-documents.site/" target="_blank">Accès à l'Api en ligne</a></li>
  </ul>
  <h2 class="titre-section-reduit2">Accès à la BDD en ligne</h2>
  <ul>
    <li><a href="https://hpanel.hostinger.com/redirect?l=phpMyAdmin&db_name=u731223545_mediatek&domain=mediatek-documents.site" target="_blank">Lien vers la BDD en ligne</a></li>
  </ul>

  <h2 class="titre-section-reduit2">Accès à la documentation</h2>
  <ul>
    <li><a href="/assets/Documentation.chm" target="_blank">Lien vers la documentation chm</a></li> 
  </ul>
</div>
<h2 class="titre-section-reduit2">Accès à l'applicationInstallateur client lourd</h2>
  <ul>
    <li><a href="/assets/MediaTekDocuments.zip" target="_blank">Installateur client lourd</a></li> 
  </ul>
</div>
<div class="content">
   <h2 class="titre-section-reduit">Documentation Utilisateur</h2>
</div>

<div class="content">
   <h2 class="titre-section-reduit2">Présentation vidéo de l'application</h2>
   <iframe width="560" height="315" src="https://www.youtube.com/embed/pF4WbKWJLrw?si=d-FUtawEiiJhbXbb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe><br><br>
  </div>

  <div class="content">
   <h2 class="titre-section-reduit">Compte-rendu d'activité</h2>
  <a href="/assets/compterendumediatekdocuments.pdf" target="_blank">lien Compte-rendu d'activité</a>
  </div>

<div class="bloc">
        <h5>Bloc 1 : Services informatiques aux organisations</h5>
        <ul>
            <li>Gérer le patrimoine informatique :
                <ul>
                    <li>Mettre en place et vérifier les niveaux d’habilitation associés à un service</li>
                    <li>Gérer des sauvegardes</li>
                </ul>
            </li>
            <li>Répondre aux incidents et aux demandes d’assistance et d’évolution :
                <ul>
                    <li>Traiter des demandes concernant les applications</li>
                </ul>
            </li>
            <li>Développer la présence en ligne de l'organisation :
                <ul>
                    <li>Participer à l’évolution d’un site Web exploitant les données de l’organisation</li>
                </ul>
            </li>
            <li>Travailler en mode projet :
                <ul>
                    <li>Analyser les objectifs et les modalités d’organisation d’un projet</li>
                    <li>Évaluer les indicateurs de suivi d’un projet et analyser les écarts</li>
                    <li>Planifier les activités</li>
                </ul>
            </li>
            <li>Mettre à disposition des utilisateurs un service informatique :
                <ul>
                    <li>Déployer un service</li>
                    <li>Réaliser les tests d’intégration et d’acceptation d’un service</li>
                </ul>
            </li>
        </ul>
    </div>
    <div class="bloc">
        <h5>Bloc 2 : Conception et développement d'applications</h5>
        <ul>
            <li>Concevoir et développer une solution applicative :
                <ul>
                    <li>Modéliser une solution applicative</li>
                    <li>Exploiter les ressources du cadre applicatif (framework)</li>
                    <li>Identifier, développer, utiliser ou adapter des composants logiciels</li>
                    <li>Exploiter les technologies Web pour mettre en œuvre les échanges entre applications, y compris de mobilité</li>
                    <li>Utiliser des composants d’accès aux données</li>
                    <li>Intégrer en continu les versions d’une solution applicative</li>
                    <li>Réaliser les tests nécessaires à la validation ou à la mise en production d’éléments adaptés ou développés</li>
                    <li>Rédiger des documentations technique et d’utilisation d’une solution applicative</li>
                </ul>
            </li>
            <li>Assurer la maintenance corrective ou évolutive d’une solution applicative :
                <ul>
                    <li>Recueillir, analyser et mettre à jour les informations sur une version d’une solution applicative</li>
                    <li>Évaluer la qualité d’une solution applicative</li>
                    <li>Analyser et corriger un dysfonctionnement</li>
                    <li>Élaborer et réaliser les tests des éléments mis à jour</li>
                </ul>
            </li>
            <li>Gérer les données :
                <ul>
                    <li>Exploiter des données à l’aide d’un langage de requêtes</li>
                    <li>Concevoir ou adapter une base de données</li>
                    <li>Développer des fonctionnalités applicatives au sein d’un système de gestion de base de données</li>
                    <li>Administrer et déployer une base de données</li>
                </ul>
            </li>
        </ul>
    </div>

<style>
  .texte-reduit {
    font-size: 25px; /* Ajustez cette valeur selon vos besoins */
  }
.container {
  display: flex;
  justify-content: space-around;
  align-items: flex-start;
}

.section {
  flex: 1;
  margin: 10px;
}

.section img {
  width: 100%;
  max-width: 600px; /* Ajustez selon la largeur maximale désirée pour les images */
  margin-top: 20px; /* Espacement entre le texte et l'image */
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

.titre-section-reduit3 {
  font-size: 10px; /* Taille de la police spécifiquement réduite pour ce titre */
}

.titre-section-reduit4 {
  font-size: 10px; /* Taille de la police spécifiquement réduite pour ce titre */
}
</style>
