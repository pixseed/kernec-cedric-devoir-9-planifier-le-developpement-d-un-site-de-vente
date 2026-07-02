# Projet : Trouve ton artisan

<h2>
  Devoir #9 :<br>
  Planifier le développement d'un site de vente
</h2>

<div class="panel panel--grid-2-col panel--center" style="margin-top: 32px">

  <div class="panel__label">Auteur</div>
  <div class="panel__value">Cédric Kernec</div>

  <div class="panel__label">GitHub</div>
  <div class="panel__value"><a href="https://github.com/pixseed" target="_blank" rel="noopener noreferrer">https://github.com/pixseed</a></div>

  <div class="panel__label">Formation</div>
  <div class="panel__value">Développeur Web & Web Mobile - Centre Européen de Formation</div>

  <div class="panel__label">Technologies</div>
  <div class="panel__value"></div>

  <div class="panel__label">Date</div>
  <div class="panel__value">06/2026</div>

  <div class="panel__label">Version</div>
  <div class="panel__value">1.0.0</div>

  <div class="panel__label">Liens utiles</div>
  <div class="panel__value"><a href="" target="_blank" rel="noopener noreferrer"></a></div>

</div>

![Logo - La Socketterie](./assets/logos/logo-complet-la-socketterie.png)

<div class="page-break"></div>

## Sommaire

- [Projet : Trouve ton artisan](#projet--trouve-ton-artisan)
  - [Sommaire](#sommaire)
  - [1. Présentation du projet](#1-présentation-du-projet)
    - [1.1. Contexte du projet](#11-contexte-du-projet)
    - [1.2. Objectif du projet](#12-objectif-du-projet)
    - [1.3. Enjeux du projet](#13-enjeux-du-projet)
    - [1.4. Parties prenantes](#14-parties-prenantes)
    - [1.5. Contraintes du projet](#15-contraintes-du-projet)
    - [1.6. Résultats attendus](#16-résultats-attendus)
  - [2. Analyse des besoins](#2-analyse-des-besoins)
    - [2.1. Identification des acteurs, de leurs rôles et de leurs besoins](#21-identification-des-acteurs-de-leurs-rôles-et-de-leurs-besoins)
    - [2.2. Priorisation des acteurs](#22-priorisation-des-acteurs)
    - [2.3. Identification des besoins fonctionnels](#23-identification-des-besoins-fonctionnels)
      - [2.3.1. Fonctionnalités visiteurs](#231-fonctionnalités-visiteurs)
      - [2.3.2. Fonctionnalités clients](#232-fonctionnalités-clients)
      - [2.3.3. Fonctionnalités commerciales et administratives](#233-fonctionnalités-commerciales-et-administratives)
      - [2.3.4. Fonctionnalités administrateur](#234-fonctionnalités-administrateur)
    - [2.4. Priorisation des fonctionnalités](#24-priorisation-des-fonctionnalités)
  - [3. Product Backlog](#3-product-backlog)
    - [3.1. Personas](#31-personas)
      - [3.1.1. Qui est le visiteur ?](#311-qui-est-le-visiteur-)
      - [3.1.2. Qui est le client ?](#312-qui-est-le-client-)
      - [3.1.3. Qui est l'administrateur ?](#313-qui-est-ladministrateur-)
      - [3.1.4. Qui est le commercial ?](#314-qui-est-le-commercial-)
      - [3.1.5. Qui est le comptable ?](#315-qui-est-le-comptable-)
    - [3.4. Backlog fonctionnel (Epics)](#34-backlog-fonctionnel-epics)
    - [3.5. User Stories](#35-user-stories)
      - [3.5.1. Estimation des User Stories selon la suite de Fibonacci](#351-estimation-des-user-stories-selon-la-suite-de-fibonacci)
      - [3.5.2. Matrice Valeur/Effort des User Stories](#352-matrice-valeureffort-des-user-stories)
      - [3.5.3. Détails des User Stories (Critique = niveau 5)](#353-détails-des-user-stories-critique--niveau-5)
    - [3.6. USE CASES](#36-use-cases)
      - [3.6.1. Diagrammes des cas d'utilisation](#361-diagrammes-des-cas-dutilisation)
      - [3.6.2. Description des cas d'utilisation](#362-description-des-cas-dutilisation)
  - [4. Sprint Backlog prévisionnel](#4-sprint-backlog-prévisionnel)
  - [5. Architecture technique](#5-architecture-technique)
    - [5.1. Architecture générale](#51-architecture-générale)
    - [5.2. Technologies retenues](#52-technologies-retenues)
    - [5.3. Structure des données](#53-structure-des-données)
    - [5.4. Flux de données](#54-flux-de-données)
    - [5.5. Schéma d'architecture](#55-schéma-darchitecture)
  - [6. Hébergements et services tiers](#6-hébergements-et-services-tiers)
    - [6.1. Besoins d'hébergement identifiés](#61-besoins-dhébergement-identifiés)
    - [6.2. Comparaison des solutions](#62-comparaison-des-solutions)
    - [6.3. Choix retenus](#63-choix-retenus)
  - [7. Organisation du projet](#7-organisation-du-projet)
    - [7.1. Kanban](#71-kanban)
    - [7.2. Workflow Git](#72-workflow-git)
  - [8 Diagramme de Gantt](#8-diagramme-de-gantt)
  - [9. Estimation des coûts](#9-estimation-des-coûts)
  - [10. Conclusion](#10-conclusion)

---
<div class="page-break"></div>

## 1. Présentation du projet

### 1.1. Contexte du projet

**La Socketterie** est une entreprise française créée en 2019 et **spécialisée dans la vente de chaussettes dépareillées tricotées**.

L'entreprise dispose actuellement d'une boutique physique située à Nice et **souhaite développer sa présence numérique afin d'augmenter sa visibilité et de commercialiser ses produits en ligne**.

Cette demande intervient dans un contexte particulier puisque l'entreprise participera prochainement à un reprotage télévisé. **Le tournage est prévu dans un délai de trois mois et la diffusion un mois plus tard**.

<div class="card card--danger">
  Le site internet devra donc être suffisamment avancé pour être présenté lors du tournage et totalement opérationnel avant la diffusion du reportage afin de tirer profit de cette visibilité médiatique.
</div>

L'entreprise **cible principalement une population jeune âgée de 20 à 35 ans**. Le futur site devra donc proposer une expérience moderne, intuitive et adaptée aux usages actuels du commerce en ligne.

### 1.2. Objectif du projet

<div class="underline">Les objectifs du projet sont les suivants :</div>

<ul class="custom-list">
  <li>Augmenter la visibilité de l'entreprise sur internet.</li>
  <li>Développer les ventes grâce à une boutique en ligne.</li>
  <li>Mettre en avant l'identité graphique de la marque.</li>
  <li>Présenter les produits et les actualités de l'entreprise.</li>
  <li>Permettre aux visiteurs/clients de contacter facilement l'entreprise.</li>
  <li>Offrir aux clients un espace personnel pour suivre leurs commandes.</li>
  <li>Fournir aux équipes internes des outils de gestions adaptés.</li>
</ul>

### 1.3. Enjeux du projet

<div class="underline">Le projet présente plusieurs enjeux majeurs :</div>

<div class="layout-grid layout-grid--3">
  <div class="card card--center card--with-header">
    <div class="card__title--with-header">Enjeu commercial</div>
    <div class="card__text--with-header">
      Développer une nouvelle source de revenus grâce à la vente en ligne.
    </div>
  </div>
  <div class="card card--center card--with-header">
    <div class="card__title--with-header">Enjeu marketing</div>
    <div class="card__text--with-header">
      Renforcer l'identité de la marque auprès de sa cible principale.
    </div>
  </div>
  <div class="card card--center card--with-header">
    <div class="card__title--with-header">Enjeu organisationnel</div>
    <div class="card__text--with-header">
      Faciliter le travail des équipes commerciales, administratives et comptables.
    </div>
  </div>
  <div class="card card--center card--with-header">
    <div class="card__title--with-header">Enjeu technique</div>
    <div class="card__text--with-header">
      Mettre en place une plateforme fiable, sécurisée, évolutive et maintenable.
    </div>
  </div>
  <div class="card card--center card--with-header">
    <div class="card__title--with-header">Enjeu temporel</div>
    <div class="card__text--with-header">
      Respecter les délais imposés par la diffusion du reportage télévisé.
    </div>
  </div>
</div>

<div class="page-break"></div>

### 1.4. Parties prenantes

| Acteur | Rôle |
|--------|------|
| La Socketterie | Client |
| Lead Developer | Validation métier et technique |
| UX/UI designers | Maquettes & expérience utilisateur |
| Développeurs | Réalisation / Développement (2 alternants disponible à 80%) |
| Freelances | Renfort ponctuel (2 freelances en contrat de 5 jours max.) |
| Équipe commerciale | Gestion produits & commandes |
| Comptabilité | Facturation & export comptable |
| Administrateur | Administration globales du site |

### 1.5. Contraintes du projet

<div class="layout-grid layout-grid--3">
  <div class="card card--center card--danger">
    Délai de 3 mois avant tournage
  </div>
  <div class="card card--center card--danger">
    Diffusion 1 mois après
  </div>
  <div class="card card--center card--danger">
    Paiement Stripe
  </div>
  <div class="card card--center card--danger">
    Français uniquement
  </div>
  <div class="card card--center card--danger">
    Euro uniquement
  </div>
  <div class="card card--center card--danger">
    Commandes UE
  </div>
  <div class="card card--center card--danger">
    SEO
  </div>
  <div class="card card--center card--danger">
    Éco-conception
  </div>
  <div class="card card--center card--danger">
    Conformité règlementaire
  </div>
</div>

### 1.6. Résultats attendus

<div class="underline">À l'issue du projet, La Socketterie disposera :</div>

- d'un site vitrine moderne
- d'une boutique e-commerce fonctionnelle
- d'un espace client sécurisé
- d'un espace d'administration
- d'une solution prête à accueillir un volume de visiteurs plus important

---
<div class="page-break"></div>

## 2. Analyse des besoins

### 2.1. Identification des acteurs, de leurs rôles et de leurs besoins

| Acteur | Rôle | Besoins |
|--------|------|---------|
| Visiteurs | Découvrir la marque. | Consulter les produits et les actualités, rechercher un produit, ajouter un articles au panier, contacter l'entreprise. |
| Clients | Acheter des produits. | Commmander des produits, payer en ligne, suivre ses commandes, gérer son compte client. |
| Service commerciale | Gérer les ventes : Suivi et gestion des commandes. | Mettre à jour les articles, éditer des informations de la commande à envoyer au service logistique, consulter les commandes et leur statut. |
| Service comptabilité | Gérer les facturations. | Consulter les commandes, consulter et éditer les factures, exporter les données (format CSV). |
| Administrateur | Gérer le site : Charger du bon fonctionnement du site. | Accéder à toutes les fonctionnalités du site. |

### 2.2. Priorisation des acteurs

<table>
  <thead>
    <tr>
      <th>Acteur</th>
      <th>Priorité</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>Visiteurs</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Clients</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Administrateur</td>
      <td>
        <span class="badge badge--priority-high">Haute</span>
      </td>
    </tr>
    <tr>
      <td>Commerciaux</td>
      <td>
        <span class="badge badge--priority-medium">Moyenne</span>
      </td>
    </tr>
    <tr>
      <td>Comptables</td>
      <td>
        <span class="badge badge--priority-medium">Moyenne</span>
      </td>
    </tr>
  </tbody>
</table>

<div class="page-break"></div>

### 2.3. Identification des besoins fonctionnels

#### 2.3.1. Fonctionnalités visiteurs

| Fonctionnalité | Description |
|----------------|-------------|
| Catalogue produits | Consulter les produits |
| Recherche | Rechercher un produit |
| Fiche produit | Consulter les détails d'un produit |
| Panier | Préparer une commande |
| Formulaire de contact | Contacter l'entreprise |
| Actualités | Consulter les nouveautés |

#### 2.3.2. Fonctionnalités clients

<ul class="custom-list">
  <li>
    En plus des fonctionnalités visiteurs.
  </li>
</ul>

| Fonctionnalité | Description |
|----------------|-------------|
| Création de compte | S'inscrire |
| Connexion | Accéder à son espace |
| Paiement Stripe | Régler une commande |
| Historique | Consulter les commandes |
| Gestion profil | Modifier ses informations personnelles |

#### 2.3.3. Fonctionnalités commerciales et administratives

| Fonctionnalité | Description |
|----------------|-------------|
| Gestion produits | Ajouter, modifier, supprimer |
| Gestion catégories | Organiser le catalogue |
| Validation commande | Validation et traitement des commandes |
| Paiement sécurisé | Stripe |
| Suivi commandes | État des commandes |
| Facturation | Édition des factures |

#### 2.3.4. Fonctionnalités administrateur

<ul class="custom-list">
  <li>
    En plus des fonctionnalités visiteurs, clients, commerciales et administratives.
  </li>
</ul>

| Fonctionnalité | Description |
|----------------|-------------|
| Gestion utilisateurs | Administrer les comptes |
| Gestion contenus  | Actualités, pages |

<div class="page-break"></div>

### 2.4. Priorisation des fonctionnalités

<table>
  <thead>
    <tr>
      <th>Fonctionnalité</th>
      <th>Priorité</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>Catalogue produits</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Fiche produit</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Recherche produit</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Panier</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Formulaire de contact</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Création de compte</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Connexion</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Paiement Stripe</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Gestion produit</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Gestion catégorie</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Validation commande</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Paiement sécurisé</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Gestion utilisateur</td>
      <td>
        <span class="badge badge--priority-critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Suivi commande</td>
      <td>
        <span class="badge badge--priority-high">Haute</span>
      </td>
    </tr>
    <tr>
      <td>Gestion contenu</td>
      <td>
        <span class="badge badge--priority-high">Haute</span>
      </td>
    </tr>
    <tr>
      <td>Historique</td>
      <td>
        <span class="badge badge--priority-medium">Moyenne</span>
      </td>
    </tr>
    <tr>
      <td>Gestion profil</td>
      <td>
        <span class="badge badge--priority-medium">Moyenne</span>
      </td>
    </tr>
    <tr>
      <td>Facturation</td>
      <td>
        <span class="badge badge--priority-medium">Moyenne</span>
      </td>
    </tr>
    <tr>
      <td>Actualité</td>
      <td>
        <span class="badge badge--priority-low">Faible</span>
      </td>
    </tr>
  </tbody>
</table>

---

<div class="page-break"></div>

## 3. Product Backlog

### 3.1. Personas

#### 3.1.1. Qui est le visiteur ?

Un utilisateur :
- non connecté;
- qui découvre la marque;
- qui recherche éventuellement un produit;
- qui n'a jamais acheté.
  
#### 3.1.2. Qui est le client ?

Un utilisateur :
- possédant un compte;
- ayant déjà effectué ou souhaitant effectuer une commande;
- pouvant accéder à son espace personnel;
- pouvant suivre ses commandes.
  
#### 3.1.3. Qui est l'administrateur ?

Un collaborateur interne :
- disposant des droits complets d'administration;
- responsable du bon fonctionnement du site;
- chargé de la gestion du catalogue, du contenu et des utilisateurs.

#### 3.1.4. Qui est le commercial ?

Un collaborateur interne :
- chargé du traitement des ventes;
- responsable du suivi des commandes;
- en relation avec les clients et le service expédition.
  
#### 3.1.5. Qui est le comptable ?

Un collaborateur interne :
- chargé du suivi financier;
- responsable de la facturation;

<div class="page-break"></div>

<div class="split-layout">

  <div>
    <h3>3.2. Tableau des points d'effort</h3>
    <table class="custom-table custom-table--effort">
      <colgroup>
        <col class="col-number">
        <col class="col-auto">
        <col class="col-auto">
      </colgroup>
      <thead>
        <tr>
          <th>Effort</th>
          <th>Signification</th>
          <th>Temporisation</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>
           <span class="badge badge--number badge--effort-1">1</span>
          </td>
          <td>Très simple</td>
          <td>Moins de 2 heures</td>
        </tr>
        <tr>
          <td>
           <span class="badge badge--number badge--effort-2">2</span>
          </td>
          <td>Simple</td>
          <td>Une demi-journée</td>
        </tr>
        <tr>
          <td>
           <span class="badge badge--number badge--effort-3">3</span>
          </td>
          <td>Faible complexité</td>
          <td>Jusqu'à 2 jours</td>
        </tr>
        <tr>
          <td>
           <span class="badge badge--number badge--effort-5">5</span>
          </td>
          <td>Complexité moyenne</td>
          <td>Quelques jours</td>
        </tr>
        <tr>
          <td>
           <span class="badge badge--number badge--effort-8">8</span>
          </td>
          <td>Complexe</td>
          <td>Environ une semaine</td>
        </tr>
        <tr>
          <td>
           <span class="badge badge--number badge--effort-13">13</span>
          </td>
          <td>Très complexe</td>
          <td>Plus d'une semaine</td>
        </tr>
      </tbody>
    </table>
  </div>

  <div>
    <h3>3.3. Tableau des valeurs métier</h3>
    <table class="custom-table custom-table--value">
      <colgroup>
        <col class="col-number">
        <col class="col-auto">
      </colgroup>
      <thead>
        <tr>
          <th>Valeur</th>
          <th>Signification</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>
            <span class="badge badge--number badge--value-1">1</span>
          </td>
          <td>Faible</td>
        </tr>
        <tr>
          <td>
            <span class="badge badge--number badge--value-2">2</span>
          </td>
          <td>Peu utile</td>
        </tr>
        <tr>
          <td>
            <span class="badge badge--number badge--value-3">3</span>
          </td>
          <td>Utile</td>
        </tr>
        <tr>
          <td>
            <span class="badge badge--number badge--value-4">4</span>
          </td>
          <td>Importante</td>
        </tr>
        <tr>
          <td>
            <span class="badge badge--number badge--value-5">5</span>
          </td>
          <td>Critique</td>
        </tr>
      </tbody>
    </table>
  </div>

</div>

### 3.4. Backlog fonctionnel (Epics)

<table class="custom-table custom-table--epics">
  <colgroup>
    <col class="col-id">
    <col class="col-auto">
    <col class="col-role">
    <col class="col-auto">
  </colgroup>
  <thead>
    <tr>
      <th>ID</th>
      <th>EPIC</th>
      <th>Acteurs principal</th>
      <th>Objectif</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>E-01</td>
      <td>Découverte du catalogue</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td>Découvrir les produits vendus par La Socketterie</td>
    </tr>
    <tr>
      <td>E-02</td>
      <td>Recherche & navigation</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td>Trouver rapidement un produit précis</td>
    </tr>
    <tr>
      <td>E-03</td>
      <td>Consultation des produits</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td>Obtenir les informations détaillées d'un produit</td>
    </tr>
    <tr>
      <td>E-04</td>
      <td>Découverte de l'entreprise</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td>Découvrir l'histoire, les valeurs et les engagements de La Socketterie</td>
    </tr>
    <tr>
      <td>E-05</td>
      <td>Gestion du panier</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td>Préparer une commande en ajoutant des produits</td>
    </tr>
    <tr>
      <td>E-06</td>
      <td>Contact & assistance</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td>Entrer en contact avec l'entreprise</td>
    </tr>
    <tr>
      <td>E-07</td>
      <td>Informations légales</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td>Consulter les informations réglementaires du site</td>
    </tr>
    <tr>
      <td>E-08</td>
      <td>Création du compte</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td>Créer un compte client utilisateur</td>
    </tr>
    <tr>
      <td>E-09</td>
      <td>Commande et paiement</td>
      <td>
        <span class="badge badge--role-customer">Client</span>
      </td>
      <td>Confirmer ou suivre une commande et acheter des produits</td>
    </tr>
    <tr>
      <td>E-10</td>
      <td>Gestion du compte</td>
      <td>
        <span class="badge badge--role-customer">Client</span>
      </td>
      <td>Gérer son espace personnel</td>
    </tr>
    <tr>
      <td>E-11</td>
      <td>Gestion du catalogue</td>
      <td>
        <span class="badge badge--role-sales">Commercial</span>
      </td>
      <td>Gérer les produits du catalogue</td>
    </tr>
    <tr>
      <td>E-12</td>
      <td>Gestion des commandes</td>
      <td>
        <span class="badge badge--role-sales">Commercial</span>
      </td>
      <td>Traiter les commandes client</td>
    </tr>
    <tr>
      <td>E-13</td>
      <td>Facturation</td>
      <td>
        <span class="badge badge--role-accounting">Comptable</span>
      </td>
      <td>Gérer les factures et consulter la liste des commandes</td>
    </tr>
    <tr>
      <td>E-14</td>
      <td>Gestion du contenu</td>
      <td>
        <span class="badge badge--role-admin">Administrateur</span>
      </td>
      <td>Gérer les pages publiques et les actualités</td>
    </tr>
    <tr>
      <td>E-15</td>
      <td>Gestion des comptes internes</td>
      <td>
        <span class="badge badge--role-admin">Administrateur</span>
      </td>
      <td>Gérer les comptes d'accès interne : commerciaux, comptables, etc.</td>
    </tr>
    <tr>
      <td>E-16</td>
      <td>Paramétrage du site</td>
      <td>
        <span class="badge badge--role-admin">Administrateur</span>
      </td>
      <td>Paramétrer les catégories, modes de livraison et paramètres techniques</td>
    </tr>
  </tbody>
</table>

<div class="page-break"></div>

### 3.5. User Stories

<table class="custom-table custom-table--us">
  <colgroup>
    <col class="col-id">
    <col class="col-auto">
    <col class="col-role">
    <col class="col-auto">
    <col class="col-number">
    <col class="col-number">
  </colgroup>
  <thead>
    <tr>
      <th>ID</th>
      <th>EPIC</th>
      <th>Acteur</th>
      <th>User Story</th>
      <th>Effort</th>
      <th>Valeur</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US-V01</td>
      <td class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-01</span>
          <span>Découverte du catalogue</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite consulter le catalogue afin de découvrir les produits proposés</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-V02</td>
      <td rowspan="2" class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-02</span>
          <span>Recherche & navigation</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite rechercher un produit par mot-clé afin de trouver rapidement un article précis</td>
      <td>
        <span class="badge badge--number badge--effort-5">5</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-V03</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite filtrer les produits par catégorie afin d'affiner ma recherche</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-4">4</span>
      </td>
    </tr>
    <tr>
      <td>US-V04</td>
      <td rowspan="2" class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-03</span>
          <span>Consultation des produits</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite consulter la fiche détaillée d'un produit afin d'obtenir toutes les informations nécessaires avant un éventuel achat</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-V05</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite visualiser plusieurs photos d'un produit afin de voir le produit sous différents angles ou différentes couleurs</td>
      <td>
        <span class="badge badge--number badge--effort-2">2</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-3">3</span>
      </td>
    </tr>
    <tr>
      <td>US-V06</td>
      <td rowspan="2" class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-04</span>
          <span>Découverte de l'entreprise</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite consulter la présentation de l'entreprise afin de découvrir son histoire et ses valeurs</td>
      <td>
        <span class="badge badge--number badge--effort-2">2</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-2">2</span>
      </td>
    </tr>
    <tr>
      <td>US-V07</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite consulter les actualités de l'entreprise afin de suivre son activité</td>
      <td>
        <span class="badge badge--number badge--effort-2">2</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-2">2</span>
      </td>
    </tr>
    <tr>
      <td>US-V08</td>
      <td rowspan="4" class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-05</span>
          <span>Gestion du panier</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite ajouter un produit au panier afin de préparer une commande</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-V09</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite modifier la quantité d'un produit afin d'ajuster ma future commande</td>
      <td>
        <span class="badge badge--number badge--effort-2">2</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-4">4</span>
      </td>
    </tr>
    <tr>
      <td>US-V10</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite supprimer un produit du panier afin de mettre à jour ma sélection</td>
      <td>
        <span class="badge badge--number badge--effort-1">1</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-4">4</span>
      </td>
    </tr>
    <tr>
      <td>US-V11</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite consulter le contenu de mon panier afin de vérifier les produits sélectionnés avant de poursuivre ma commande</td>
      <td>
        <span class="badge badge--number badge--effort-2">2</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-V12</td>
      <td class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-06</span>
          <span>Contact & assistance</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite envoyer un message via le formulaire de contact afin d'obtenir une réponse à ma demande</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-3">3</span>
      </td>
    </tr>
    <tr>
      <td>US-V13</td>
      <td rowspan="2" class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-07</span>
          <span>Informations légales</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite consulter les mentions légales afin de connaître les informations réglementaires du site</td>
      <td>
        <span class="badge badge--number badge--effort-1">1</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-2">2</span>
      </td>
    </tr>
    <tr>
      <td>US-V14</td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite consulter les CGV afin de connaître les régles applicables aux achats</td>
      <td>
        <span class="badge badge--number badge--effort-1">1</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-2">2</span>
      </td>
    </tr>
    <tr>
      <td>US-V15</td>
      <td class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-07</span>
          <span>Informations légales</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite consulter la politique de confidentialité afin de connaître l'utilisation de mes données personnelles</td>
      <td>
        <span class="badge badge--number badge--effort-1">1</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-2">2</span>
      </td>
    </tr>
    <tr>
      <td>US-V16</td>
      <td class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-08</span>
          <span>Création du compte</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-visitor">Visiteur</span>
      </td>
      <td class="us-story">En tant que visiteur, je souhaite créer un compte afin de pouvoir passer commande et suivre mes achats</td>
      <td>
        <span class="badge badge--number badge--effort-5">5</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-C01</td>
      <td rowspan="3" class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-09</span>
          <span>Commande et paiement</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-customer">Client</span>
      </td>
      <td class="us-story">En tant que client, je souhaite valider une commande afin de finaliser mon achat</td>
      <td>
        <span class="badge badge--number badge--effort-5">5</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-C02</td>
      <td>
        <span class="badge badge--role-customer">Client</span>
      </td>
      <td class="us-story">En tant que client, je souhaite payer ma commande en ligne afin de confirmer mon achat</td>
      <td>
        <span class="badge badge--number badge--effort-8">8</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-C03</td>
      <td>
        <span class="badge badge--role-customer">Client</span>
      </td>
      <td class="us-story">En tant que client, je souhaite recevoir une confirmation de commande afin d'être informé de la prise en compte de mon achat</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-4">4</span>
      </td>
    </tr>
    <tr>
      <td>US-C04</td>
      <td rowspan="3" class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-10</span>
          <span>Gestion du compte</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-customer">Client</span>
      </td>
      <td class="us-story">En tant client, je souhaite me connecter à mon compte afin d'accéder à mon espace personnel et à mes commandes</td>
      <td>
        <span class="badge badge--number badge--effort-5">5</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-C05</td>
      <td>
        <span class="badge badge--role-customer">Client</span>
      </td>
      <td class="us-story">En tant que client, je souhaite modifier mes informations personnelles afin de maintenir mon profil à jour</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-3">3</span>
      </td>
    </tr>
    <tr>
      <td>US-C06</td>
      <td>
        <span class="badge badge--role-customer">Client</span>
      </td>
      <td class="us-story">En tant que client, je souhaite consulter l'historique de mes commandes afin de suivre mes achats passés</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-3">3</span>
      </td>
    </tr>
    <tr>
      <td>US-S01</td>
      <td rowspan="4" class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-11</span>
          <span>Gestion du catalogue</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-sales">Commercial</span>
      </td>
      <td class="us-story">En tant que commercial, je souhaite ajouter un nouveau produit au catalogue afin de proposer de nouveaux articles à la vente</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-S02</td>
      <td>
        <span class="badge badge--role-sales">Commercial</span>
      </td>
      <td class="us-story">En tant que commercial, je souhaite accéder au formulaire d'édition de produit afin de pouvoir modifier un article</td>
      <td>
        <span class="badge badge--number badge--effort-5">5</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-S03</td>
      <td>
        <span class="badge badge--role-sales">Commercial</span>
      </td>
      <td class="us-story">En tant que commercial, je souhaite supprimer un produit afin de retirer un article du catalogue</td>
      <td>
        <span class="badge badge--number badge--effort-2">2</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-4">4</span>
      </td>
    </tr>
    <tr>
      <td>US-S04</td>
      <td>
        <span class="badge badge--role-sales">Commercial</span>
      </td>
      <td class="us-story">En tant que commercial, je souhaite organiser le catalogue par catégorie afin de faciliter la navigation des visiteurs</td>
      <td>
        <span class="badge badge--number badge--effort-2">2</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-4">4</span>
      </td>
    </tr>
    <tr>
      <td>US-S05</td>
      <td rowspan="2" class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-12</span>
          <span>Gestion des commandes</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-sales">Commercial</span>
      </td>
      <td class="us-story">En tant que commercial, je souhaite consulter les commandes afin d'assurer leur suivi</td>
      <td>
        <span class="badge badge--number badge--effort-2">2</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-S06</td>
      <td>
        <span class="badge badge--role-sales">Commercial</span>
      </td>
      <td class="us-story">En tant que commercial, je souhaite modifier le statut d'une commande afin de suivre son traitement et la mettre à jour</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-F01</td>
      <td class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-13</span>
          <span>Facturation</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-accounting">Comptable</span>
      </td>
      <td class="us-story">En tant que comptable, je souhaite consulter les commandes validées afin de préparer les opérations de facturation</td>
      <td>
        <span class="badge badge--number badge--effort-2">2</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-4">4</span>
      </td>
    </tr>
    <tr>
      <td>US-F02</td>
      <td rowspan="2" class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-13</span>
          <span>Facturation</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-accounting">Comptable</span>
      </td>
      <td class="us-story">En tant que comptable, je souhaite générer une facture afin de disposer d'un document comptable associé à une commande validée</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-F03</td>
      <td>
        <span class="badge badge--role-accounting">Comptable</span>
      </td>
      <td class="us-story">En tant que comptable, je souhaite exporter les données comptables afin de les intégrer au système comptable de l'entreprise</td>
      <td>
        <span class="badge badge--number badge--effort-5">5</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-3">3</span>
      </td>
    </tr>
    <tr>
      <td>US-A01</td>
      <td rowspan="4" class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-14</span>
          <span>Gestion du contenu</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-admin">Administrateur</span>
      </td>
      <td class="us-story">En tant qu'administrateur, je souhaite créer une actualité afin d'informer les visiteurs du site</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-2">2</span>
      </td>
    </tr>
    <tr>
      <td>US-A02</td>
      <td>
        <span class="badge badge--role-admin">Administrateur</span>
      </td>
      <td class="us-story">En tant qu'administrateur, je souhaite modifier une actualité afin de mettre à jour les informations publiées</td>
      <td>
        <span class="badge badge--number badge--effort-2">2</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-2">2</span>
      </td>
    </tr>
    <tr>
      <td>US-A03</td>
      <td>
        <span class="badge badge--role-admin">Administrateur</span>
      </td>
      <td class="us-story">En tant qu'administrateur, je souhaite supprimer une actualité afin de retirer une information obsolète</td>
      <td>
        <span class="badge badge--number badge--effort-1">1</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-2">2</span>
      </td>
    </tr>
    <tr>
      <td>US-A04</td>
      <td>
        <span class="badge badge--role-admin">Administrateur</span>
      </td>
      <td class="us-story">En tant qu'administrateur, je souhaite gérer les contenus statiques du site afin de maintenir les pages publiques à jour</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-4">4</span>
      </td>
    </tr>
    <tr>
      <td>US-A05</td>
      <td rowspan="3" class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-15</span>
          <span>Gestion des comptes internes</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-admin">Administrateur</span>
      </td>
      <td class="us-story">En tant qu'administrateur, je souhaite créer un compte interne afin de permettre l'accès aux collaborateurs autorisés</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-4">4</span>
      </td>
    </tr>
    <tr>
      <td>US-A06</td>
      <td>
        <span class="badge badge--role-admin">Administrateur</span>
      </td>
      <td class="us-story">En tant qu'administrateur, je souhaite modifier un compte interne afin de maintenir les informations et les accès des utilisateurs interne à jour</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-4">4</span>
      </td>
    </tr>
    <tr>
      <td>US-A07</td>
      <td>
        <span class="badge badge--role-admin">Administrateur</span>
      </td>
      <td class="us-story">En tant qu'administrateur, je souhaite désactiver un compte interne afin de supprimer les accès d'un utilisateur</td>
      <td>
        <span class="badge badge--number badge--effort-2">2</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-4">4</span>
      </td>
    </tr>
    <tr>
      <td>US-A08</td>
      <td rowspan="4" class="epic-column">
        <div class="stack-cell">
          <span class="epic-number">E-16</span>
          <span>Paramétrage du site</span>
        </div>
      </td>
      <td>
        <span class="badge badge--role-admin">Administrateur</span>
      </td>
      <td class="us-story">En tant qu'administrateur, je souhaite paramétrer les catégories de produits afin d'organiser efficacement le catalogue</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-A09</td>
      <td>
        <span class="badge badge--role-admin">Administrateur</span>
      </td>
      <td class="us-story">En tant qu'administrateur, je souhaite paramétrer les modes de livraison disponibles afin de proposer différentes solutions d'expédition aux clients</td>
      <td>
        <span class="badge badge--number badge--effort-5">5</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
    <tr>
      <td>US-A10</td>
      <td>
        <span class="badge badge--role-admin">Administrateur</span>
      </td>
      <td class="us-story">En tant qu'administrateur, je souhaite accéder aux paramètres techniques du site afin d'assurer son bon fonctionnement</td>
      <td>
        <span class="badge badge--number badge--effort-3">3</span>
      </td>
      <td>
        <span class="badge badge--number badge--value-5">5</span>
      </td>
    </tr>
  </tbody>
</table>

<div class="page-break"></div>

#### 3.5.1. Estimation des User Stories selon la suite de Fibonacci

Les User Stories sont estimées selon la suite de Fibonacci (1, 2, 3, 5, 8, 13, 21...) afin de prendre en compte la complexité et l'incertitude croissance.

<table class="custom-table custom-table--fibo">
  <colgroup>
    <col style="width: 14%">
    <col style="width: 54%">
    <col style="width: 32%">
  </colgroup>
  <thead>
    <tr>
      <th>Story Point</th>
      <th>User Stories</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <div class="stack-cell">
          <span class="fibo-title">1 point</span>
          <span class="fibo-subtitle">Très simple</span>
        </div>
      </td>
      <td>
        <div class="grid-cell--5-col cell-center">
          <span class="badge badge--small badge--role-visitor">US-V10</span>
          <span class="badge badge--small badge--role-visitor">US-V13</span>
          <span class="badge badge--small badge--role-visitor">US-V14</span>
          <span class="badge badge--small badge--role-visitor">US-V15</span>
          <span class="badge badge--small badge--role-admin">US-A03</span>
        </div>
      </td>
      <td>US simple avec une complexité minimale.</td>
    </tr>
    <tr>
      <td>
        <div class="stack-cell">
          <span class="fibo-title">2 points</span>
          <span class="fibo-subtitle">Simple</span>
        </div>
      </td>
      <td>
        <div class="grid-cell--5-col cell-center">
          <span class="badge badge--small badge--role-visitor">US-V05</span>
          <span class="badge badge--small badge--role-visitor">US-V06</span>
          <span class="badge badge--small badge--role-visitor">US-V07</span>
          <span class="badge badge--small badge--role-visitor">US-V09</span>
          <span class="badge badge--small badge--role-visitor">US-V11</span>
          <span class="badge badge--small badge--role-sales">US-S03</span>
          <span class="badge badge--small badge--role-sales">US-S04</span>
          <span class="badge badge--small badge--role-sales">US-S05</span>
          <span class="badge badge--small badge--role-accounting">US-F01</span>
          <span class="badge badge--small badge--role-admin">US-A02</span>
          <span class="badge badge--small badge--role-admin">US-A07</span>
        </div>
      </td>
      <td>Un peu plus complexe. Fonctionnalité simple avec peu de dépendances.</td>
    </tr>
    <tr>
      <td>
        <div class="stack-cell">
          <span class="fibo-title">3 points</span>
          <span class="fibo-subtitle">Faible complexité</span>
        </div>
      </td>
      <td>
        <div class="grid-cell--5-col cell-center">
          <span class="badge badge--small badge--role-visitor">US-V01</span>
          <span class="badge badge--small badge--role-visitor">US-V03</span>
          <span class="badge badge--small badge--role-visitor">US-V04</span>
          <span class="badge badge--small badge--role-visitor">US-V08</span>
          <span class="badge badge--small badge--role-visitor">US-V12</span>
          <span class="badge badge--small badge--role-customer">US-C03</span>
          <span class="badge badge--small badge--role-customer">US-C05</span>
          <span class="badge badge--small badge--role-customer">US-C06</span>
          <span class="badge badge--small badge--role-sales">US-S01</span>
          <span class="badge badge--small badge--role-sales">US-S06</span>
          <span class="badge badge--small badge--role-accounting">US-F02</span>
          <span class="badge badge--small badge--role-admin">US-A01</span>
          <span class="badge badge--small badge--role-admin">US-A04</span>
          <span class="badge badge--small badge--role-admin">US-A05</span>
          <span class="badge badge--small badge--role-admin">US-A06</span>
          <span class="badge badge--small badge--role-admin">US-A08</span>
          <span class="badge badge--small badge--role-admin">US-A10</span>
        </div>
      </td>
      <td>Complexité modérée avec quelques dépendances nécessitant quelques règles et interactions.</td>
    </tr>
    <tr>
      <td>
        <div class="stack-cell">
          <span class="fibo-title">5 points</span>
          <span class="fibo-subtitle">Complexité moyenne</span>
        </div>
      </td>
      <td>
        <div class="grid-cell--5-col cell-center">
          <span class="badge badge--small badge--role-visitor">US-V02</span>
          <span class="badge badge--small badge--role-visitor">US-V16</span>
          <span class="badge badge--small badge--role-customer">US-C01</span>
          <span class="badge badge--small badge--role-customer">US-C04</span>
          <span class="badge badge--small badge--role-sales">US-S02</span>
          <span class="badge badge--small badge--role-accounting">US-F03</span>
          <span class="badge badge--small badge--role-admin">US-A09</span>
        </div>
      </td>
      <td>US complexe impliquant de multiples dépendances. Fonctionnalité complexe avec plusieurs règles métier.</td>
    </tr>
    <tr>
      <td>
        <div class="stack-cell">
          <span class="fibo-title">8 points</span>
          <span class="fibo-subtitle">Complexe</span>
        </div>
      </td>
      <td>
        <div class="grid-cell--5-col cell-center">
          <span class="badge badge--small badge--role-customer">US-C02</span>
        </div>
      </td>
      <td>US très complexe ou à forte incertitude. Envisagez de la décomposer.</td>
    </tr>
    <tr>
      <td>
        <div class="stack-cell">
          <span class="fibo-title">13 points</span>
          <span class="fibo-subtitle">Très complexe</span>
        </div>
      </td>
      <td class="empty-cell">Aucune User Story estimée à ce niveau</td>
      <td>Trop important ou trop risqué pour être estimé avec précision. Il faut le diviser en US plus petites.</td>
    </tr>
  </tbody>
</table>

<div class="fibo-legend">
  <span class="legend-title">Légende :</span>
  <span class="badge badge--small badge--role-visitor">Visiteur</span>
  <span class="badge badge--small badge--role-customer">Client</span>
  <span class="badge badge--small badge--role-sales">Commercial</span>
  <span class="badge badge--small badge--role-accounting">Comptable</span>
  <span class="badge badge--small badge--role-admin">Administrateur</span>
</div>

<div class="page-break"></div>

#### 3.5.2. Matrice Valeur/Effort des User Stories

La matrice Valeur / Effort permet de visualiser les User Stories selon deux critèes : leur **valeur métier** (axe vertical) et leur **effort de développement estimé** (axe horizontal, selon la suite Fibonacci). Cette représentation facilite la priorisation des fonctionnalités en mettant en évidence les tâches offrant le meilleur rapport entre valeur apportée et coût de réalisation.

![Matrice Valeur/Effort](./docs/images/matrice-valeur-effort-us.png)

<div class="fibo-legend">
  <span class="legend-title">Légende :</span>
  <span class="badge badge--small badge--role-visitor">Visiteur</span>
  <span class="badge badge--small badge--role-customer">Client</span>
  <span class="badge badge--small badge--role-sales">Commercial</span>
  <span class="badge badge--small badge--role-accounting">Comptable</span>
  <span class="badge badge--small badge--role-admin">Administrateur</span>
</div>

<div class="bold underline" style="margin-top: 16px">Lecture de la la matrice</div>

- Les User Stories situées en **haut à gauche** présentent une **forte valeur pour un faible effort**. Elles constituent les fonctionnalités à développer en priorité (Quick Wins).
- Les User Stories **en haut à droite** aportent **une forte valeur** mais nécessitent **un effort important**. Elles représentent des investissements stratégiques à planifier.
- Les User Stories **en bas à gauche** demandent **peu d'effort** mais apportent **une valeur limitée**. Elles peuvent être intégrées en fonction des ressources disponibles.
- Les User Stories **en bas à droite** combinent **un effort élevé et une faible valeur**. Elles sont généralement reportées ou réévaluées.

<div class="page-break"></div>

#### 3.5.3. Détails des User Stories (Critique = niveau 5)

<div class="us-card">

  <div class="us-card__header">
    US-V01 - Consulter le catalogue des produits
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-visitor">Visiteur</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-3">3</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant que <span class="bold">visiteur</span>,<br>
        je souhaite consulter le catalogue<br>
        afin de découvrir les produits proposés.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>Le catalogue doit être accessible sans authentification.</li>
        <li>Les produits doivent être affichés sous forme de liste ou de grille.</li>
        <li>Chaque produit doit afficher au minimum son nom, sa catégorie, son prix et son image principale.</li>
        <li>Les produits indisponibles doivent être identifiables visuellement.</li>
        <li>Les produits doivent être classés par catégorie.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> que je suis sur le site de La Socketterie,<br>
            <span class="bold">lorsque</span> j'accède au catalogue,<br>
            <span class="bold">alors</span> la liste des produits est affichée.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> qu'un produit est indisponible,<br>
            <span class="bold">lorsque</span> je consulte le catalogue,<br>
            <span class="bold">alors</span> le produit apparaît comme indisponible mais sa fiche détaillée reste consultable sans pouvoir ajouter le produit au panier.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Fonction centrale du site.</li>
        <li>Première fonctionnalité utilisée par la majorité des visiteurs.</li>
        <li>Sans catalogue : pas de découverte produit, pas d'achat et pas de chiffre d'affaires.</li>
        <li>Complexité faible à moyenne : page catalogue, récupération des produits et affichage des cartes produits.</li>
      </ul>
    </div>

  </div>

</div>

<div class="us-card">

  <div class="us-card__header">
    US-V02 - Rechercher un produit par mot-clé
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-visitor">Visiteur</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-5">5</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant que <span class="bold">visiteur</span>,<br>
        je souhaite rechercher un produit via un mot-clé<br>
        afin de trouver rapidement un article précis.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>Le moteur de recherche est accessible depuis le catalogue.</li>
        <li>La recherche porte sur le nom ou le type du produit.</li>
        <li>Les résultats sont mis à jour après validation de la recherche.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> que je consulte le catalogue,<br>
            <span class="bold">lorsque</span> je saisis un mot-clé existant,<br>
            <span class="bold">alors</span> les produits correspondant sont affichés.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> qu'aucun produit ne correspond à la recherche,<br>
            <span class="bold">lorsque</span> j'effectue une recherche,<br>
            <span class="bold">alors</span> un message indique qu'aucun résultat n'a été trouvé.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Fonction essentielle pour améliorer l'expérience utilisateur.</li>
        <li>Permet de trouver rapidement un produit sans parcourir tout le catalogue.</li>
        <li>Fonction très utilisée sur les sites e-commerce comportant de nombreux articles.</li>
        <li>Complexité moyenne : mise en place d'un champ de recherche, filtrage des produits, gestion des résultats et des cas sans correspondance.</li>
      </ul>
    </div>

  </div>

</div>

<div class="us-card">

  <div class="us-card__header">
    US-V04 - Consulter la fiche détaillée d'un produit
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-visitor">Visiteur</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-3">3</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant que <span class="bold">visiteur</span>,<br>
        je souhaite consulter la fiche détaillée d'un produit<br>
        afin d'obtenir toutes les informations nécessaires avant un éventuel achat.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>Chaque produit possède une page détaillée.</li>
        <li>La fiche produit affiche au minimum : le nom du produit, sa catégorie, sa description, ses images et son état de disponibilité.</li>
        <li>Un produit indisponible doit être clairement identifié.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> que je consulte le catalogue,<br>
            <span class="bold">lorsque</span> je sélectionne un produit,<br>
            <span class="bold">alors</span> sa fiche détaillée est affichée.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> qu'un produit est indisponible,<br>
            <span class="bold">lorsque</span> je consulte sa fiche produit,<br>
            <span class="bold">alors</span> son indisponibilité est indiquée.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Fonction indispensable avant achat.</li>
        <li>Permet au visiteur d'obtenir toutes les informations utiles sur un produit.</li>
        <li>Favorise la conversion en commande.</li>
        <li>Complexité faible à moyenne : création d'une page produit, affichage des informations détaillées et gestion de la disponibilité.</li>
      </ul>
    </div>

  </div>

</div>

<div class="us-card">

  <div class="us-card__header">
    US-V08 - Ajouter un produit au panier
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-visitor">Visiteur</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-3">3</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant que <span class="bold">visiteur</span>,<br>
        je souhaite ajouter un produit au panier<br>
        afin de préparer une commande.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>Un produit disponible peut être ajouté au panier.</li>
        <li>Le panier conserve les produits sélectionnés même après déconnexion.</li>
        <li>La quantité initiale est égale à 1.</li>
        <li>La couleur initiale est celle paramétrée par défaut.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> que je consulte une fiche produit,<br>
            <span class="bold">lorsque</span> je clique sur "Ajouter au panier",<br>
            <span class="bold">alors</span> le produit est ajouté au panier.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> que je consulte une fiche produit,<br>
            <span class="bold">lorsque</span> le produit est indisponible,<br>
            <span class="bold">alors</span> les sélecteurs de choix ainsi que le bouton "Ajouter au panier" sont désactivés.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Première étape du processus d'achat.</li>
        <li>Sans panier, aucune commande ne peut être préparée.</li>
        <li>Fonction centrale d'un site e-commerce.</li>
        <li>Complexité moyenne : gestion du panier, ajout d'article et conservation des données utilisateur.</li>
      </ul>
    </div>

  </div>

</div>


<div class="us-card">

  <div class="us-card__header">
    US-V11 - Consulter le contenu de son panier
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-visitor">Visiteur</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-2">2</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant que <span class="bold">visiteur</span>,<br>
        je souhaite consulter le contenu de mon panier<br>
        afin de vérifier les produits sélectionnés avant de poursuivre ma commande.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>Le panier affiche l'ensemble des produits ajoutés.</li>
        <li>Le prix unitaire, les choix de couleurs, de taille et la quantité sont visibles.</li>
        <li>Le montant total est calculé automatiquement.</li>
        <li>Le panier reste accessible à tout moment depuis le site.</li>
        <li>Le panier s'affiche dans un panel.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> que j'ai ajouté un ou plusieurs produits au panier,<br>
            <span class="bold">lorsque</span> j'accède au panier,<br>
            <span class="bold">alors</span> la liste des produits sélectionnés est affichée et le montant total de la commande est calculé.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> que mon panier est vide,<br>
            <span class="bold">lorsque</span> j'accède au panier,<br>
            <span class="bold">alors</span> un message indique que le panier est vide.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Permet au visiteur de vérifier sa future commande.</li>
        <li>Fonction essentielle avant la validation d'un achat.</li>
        <li>Complexité faible : affichage des produits, calcul du montant total et gestion du panier vide.</li>
      </ul>
    </div>

  </div>

</div>

<div class="us-card">

  <div class="us-card__header">
    US-V16 - Créer un compte client
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-visitor">Visiteur</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-5">5</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant que <span class="bold">visiteur</span>,<br>
        je souhaite créer un compte<br>
        afin de pouvoir passer commande et suivre mes achats.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>Une adresse email unique est obligatoire.</li>
        <li>Un mot de passe est requis.</li>
        <li>Les informations obligatoires doivent être renseignées.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> que je suis sur le formulaire d'inscription,<br>
            <span class="bold">lorsque</span> je renseigne des informations valides,<br>
            <span class="bold">alors</span> mon compte est créé.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> qu'une erreur survient,<br>
            <span class="bold">lorsque</span> les informations sont invalides,<br>
            <span class="bold">alors</span> la création de compte n'est pas exécutée et le formulaire de contact retourne un message explicite sur l'erreur.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Prérequis à la validation d'une commande.</li>
        <li>Permet le suivi des achats et la personnalisation de l'expérience utilisateur.</li>
        <li>Complexité moyenne : gestion des comptes, validation des données et contrôle des doublons.</li>
      </ul>
    </div>

  </div>

</div>

<div class="us-card">

  <div class="us-card__header">
    US-C01 - Valider une commande
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-customer">Client</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-5">5</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant que <span class="bold">client</span>,<br>
        je souhaite valider une commande<br>
        afin de finaliser mon achat.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>L'utilisateur doit être authentifié.</li>
        <li>Le panier doit contenir au moins un produit.</li>
        <li>Le montant total doit être calculé avant validation (TVA, frais de port, etc.).</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> que je suis connecté et que mon panier contient des produits,<br>
            <span class="bold">lorsque</span> je valide ma commande,<br>
            <span class="bold">alors</span> une commande est créée.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> que je ne suis pas connecté,<br>
            <span class="bold">lorsque</span> je tente de valider ma commande,<br>
            <span class="bold">alors</span> je suis redirigé vers la connexion.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Fonction critique du processus d'achat.</li>
        <li>Transforme un panier en commande réelle.</li>
        <li>Impact direct sur le chiffre d'affaires.</li>
        <li>Complexité moyenne : vérification métier, création de commande et gestion des états.</li>
      </ul>
    </div>

  </div>

</div>

<div class="us-card">

  <div class="us-card__header">
    US-C02 - Régler une commande via Stripe
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-customer">Client</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-8">8</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant que <span class="bold">client</span>,<br>
        je souhaite payer ma commande en ligne<br>
        afin de confirmer mon achat.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>Le paiement est réalisé via Stripe.</li>
        <li>Le montant transmis correspond au total de la commande.</li>
        <li>La commande n'est validée qu'après confirmation du paiement.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> que ma commande est prête,<br>
            <span class="bold">lorsque</span> j'effectue un paiement valide,<br>
            <span class="bold">alors</span> le paiement est accepté et la commande est confirmée.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> qu'une erreur survient,<br>
            <span class="bold">lorsque</span> le paiement échoue,<br>
            <span class="bold">alors</span> la commande n'est pas validée.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Fonction indispensable à la vente en ligne.</li>
        <li>Permet l'encaissement des paiements.</li>
        <li>Impact direct sur la rentabilité du projet.</li>
        <li>Complexité élevée : intégration Stripe, sécurisation des échanges et gestion des erreurs de paiement.</li>
      </ul>
    </div>

  </div>

</div>

<div class="us-card">

  <div class="us-card__header">
    US-C04 - Se connecter à son compte
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-customer">Client</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-5">5</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant que <span class="bold">client</span>,<br>
        je souhaite me connecter à mon compte<br>
        afin d'accéder à mon espace personnel et à mes commandes.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>L'authentification nécessite une adresse email et un mot de passe.</li>
        <li>Les identifiants doivent être valides.</li>
        <li>Un utilisateur connecté accède à son espace client.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> que je possède un compte,<br>
            <span class="bold">lorsque</span> je saisis des identifiants valides,<br>
            <span class="bold">alors</span> je suis connecté à mon espace client.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> que je saisis des identifiants incorrects,<br>
            <span class="bold">lorsque</span> je tente de me connecter,<br>
            <span class="bold">alors</span> un message d'erreur explicite est affiché.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Permet l'accès aux fonctionnalités réservées aux clients.</li>
        <li>Fonction indispensable à la gestion du compte et des commandes.</li>
        <li>Fonction indispensable au processus d'achat afin de valider une commande.</li>
        <li>Complexité faible à moyenne : authentification, gestion des sessions et contrôle des accès.</li>
      </ul>
    </div>

  </div>

</div>

<div class="us-card">

  <div class="us-card__header">
    US-S01 - Ajouter un produit
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-sales">Commercial</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-3">3</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant que <span class="bold">commercial</span>,<br>
        je souhaite ajouter un nouveau produit au catalogue<br>
        afin de proposer de nouveaux articles à la vente.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>La création de produits est réservée aux commerciaux et aux administrateurs.</li>
        <li>Un produit possède au minimum un nom, une description, un prix, une catégorie et une image principale.</li>
        <li>Le produit est visible dans le catalogue après enregistrement.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> que je suis connecté en tant que commercial,<br>
            <span class="bold">lorsque</span> je crée un produit avec des données valides,<br>
            <span class="bold">alors</span> le produit est enregistré et apparaît dans le catalogue.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> que les champs obligatoires ne sont pas respectés,<br>
            <span class="bold">lorsque</span> je valide la création du produit,<br>
            <span class="bold">alors</span> un message d'erreur explicite est affiché.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Fonction essentielle à l'alimentation du catalogue.</li>
        <li>Permet de mettre de nouveaux produits à disposition des clients.</li>
        <li>Impact direct sur l'offre commerciale.</li>
        <li>Complexité moyenne : formulaire d'administration, validation des données et gestion des images.</li>
      </ul>
    </div>

  </div>

</div>

<div class="us-card">

  <div class="us-card__header">
    US-S02 - Modifier un produit
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-sales">Commercial</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-5">5</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant que <span class="bold">commercial</span>,<br>
        je souhaite modifier un produit existant<br>
        afin de maintenir le catalogue à jour.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>L'édition des produits est réservée aux commerciaux et aux administrateurs.</li>
        <li>Un produit possède au minimum un nom, une description, un prix, une catégorie et une image principale.</li>
        <li>Le produit modifié est visible dans le catalogue après enregistrement.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> que je suis connecté en tant que commercial,<br>
            <span class="bold">lorsque</span> je modifie un produit avec des données valides,<br>
            <span class="bold">alors</span> le produit est enregistré et mis à jour dans le catalogue.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> que les champs obligatoires ne sont pas respectés,<br>
            <span class="bold">lorsque</span> j'enregistre les modifications,<br>
            <span class="bold">alors</span> un message d'erreur explicite est affiché.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Permet de maintenir les informations produits à jour.</li>
        <li>Garantit la cohérence du catalogue.</li>
        <li>Évite la diffusion d'informations obsolètes.</li>
        <li>Complexité moyenne : chargement des données existantes, validation des modifications et mise à jour des informations.</li>
      </ul>
    </div>

  </div>

</div>

<div class="us-card">

  <div class="us-card__header">
    US-S06 - Modifier le statut d'une commande
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-sales">Commercial</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-3">3</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant que <span class="bold">commercial</span>,<br>
        je souhaite modifier le statut d'une commande<br>
        afin de suivre son traitement et informer le client.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>L'édition des commandes est réservée aux commerciaux et aux administrateurs.</li>
        <li>Une commande possède obligatoirement un statut.</li>
        <li>Seuls les utilisateurs autorisés peuvent modifier le statut d'une commande.</li>
        <li>Les statuts disponibles sont définis par l'entreprise.</li>
        <li>Chaque modification est enregistrée.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> qu'une commande existe,<br>
            <span class="bold">lorsque</span> je modifie son statut,<br>
            <span class="bold">alors</span> le nouveau statut est enregistré.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> qu'un client consulte son compte,<br>
            <span class="bold">lorsque</span> le statut a été modifié,<br>
            <span class="bold">alors</span> il visualise la nouvelle information.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Fonction essentielle au suivi logistique.</li>
        <li>Permet d'informer les clients de l'avancement de leur commande.</li>
        <li>Améliore la traçabilité des commandes.</li>
        <li>Complexité moyenne : gestion des états, historisation et mise à jour des informations client.</li>
      </ul>
    </div>

  </div>

</div>

<div class="us-card">

  <div class="us-card__header">
    US-F02 - Générer une facture
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-accounting">Comptable</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-3">3</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant que <span class="bold">comptable</span>,<br>
        je souhaite générer une facture<br>
        afin de disposer d'un document comptable associé à une commande validée.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>L'édition de factures est réservée aux comptables et aux administrateurs.</li>
        <li>Une facture est liée à une commande.</li>
        <li>Chaque facture possède une référence unique.</li>
        <li>Les informations de facturation sont conservées.</li>
        <li>Les mentions légales obligatoires sont présentes sur chaque facture.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> qu'une commande a été validée,<br>
            <span class="bold">lorsque</span> je génère une facture,<br>
            <span class="bold">alors</span> une facture est créée et enregistrée.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> qu'une erreur survient,<br>
            <span class="bold">lorsque</span> la création de la facture est effectuée,<br>
            <span class="bold">alors</span> un message d'erreur explicite est affiché.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Fonction indispensable à la gestion comptable.</li>
        <li>Permet de produire un document officiel associé à une commande validée.</li>
        <li>Facilite le suivi administratif et la traçabilité des ventes.</li>
        <li>Complexité moyenne : génération du document, association avec une commande et gestion des références uniques.</li>
      </ul>
    </div>

  </div>

</div>

<div class="us-card">

  <div class="us-card__header">
    US-A08 - Paramétrer les catégories de produits
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-admin">Administrateur</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-3">3</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant qu'<span class="bold">administrateur</span>,<br>
        je souhaite paramétrer les catégories de produits<br>
        afin d'organiser efficacement le catalogue.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>La gestion des catégories est réservée aux administrateurs.</li>
        <li>Une catégorie possède un nom unique.</li>
        <li>Une catégorie peut contenir plusieurs produits.</li>
        <li>Une catégorie peut être créée, modifiée ou désactivée.</li>
        <li>Les produits peuvent être associés aux catégories lors de leur création.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> que je suis connecté en tant qu'administrateur,<br>
            <span class="bold">lorsque</span> je crée ou modifie une catégorie,<br>
            <span class="bold">alors</span> celle-ci est enregistrée et disponible dans le catalogue.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> qu'une catégorie possède déjà le même nom,<br>
            <span class="bold">lorsque</span> je tente de la créer,<br>
            <span class="bold">alors</span> un message d'erreur explicite est affiché.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Fonction essentielle pour organiser le catalogue.</li>
        <li>Facilite la navigation des visiteurs.</li>
        <li>Permet aux équipes internes de structurer l'offre commerciale.</li>
        <li>Complexité moyenne : gestion CRUD des catégories, association avec les produits et contrôle des doublons.</li>
      </ul>
    </div>

  </div>

</div>

<div class="us-card">

  <div class="us-card__header">
    US-A09 - Paramétrer les modes de livraison
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-admin">Administrateur</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-5">5</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant qu'<span class="bold">administrateur</span>,<br>
        je souhaite paramétrer les modes de livraison<br>
        afin de proposer différentes solutions d'expédition.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>La gestion des modes de livraison est réservée aux administrateurs.</li>
        <li>Chaque mode possède un nom et un coût.</li>
        <li>Un mode peut être créé, modifié ou désactivé.</li>
        <li>Les modes actifs sont proposés lors de la validation d'une commande.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> que je suis connecté en tant qu'administrateur,<br>
            <span class="bold">lorsque</span> je crée ou modifie un mode de livraison,<br>
            <span class="bold">alors</span> celui-ci devient disponible pour les futures commandes.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> qu'une donnée est invalide,<br>
            <span class="bold">lorsque</span> j'enregistre le mode de livraison,<br>
            <span class="bold">alors</span> un message d'erreur explicite est affiché.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Fonction indispensable au processus de commande.</li>
        <li>Permet de proposer plusieurs solutions d'expédition.</li>
        <li>Impact direct sur le traitement des commandes.</li>
        <li>Complexité moyenne à élevée : gestion des coûts, activation des modes et intégration au tunnel de commande.</li>
      </ul>
    </div>

  </div>

</div>

<div class="us-card">

  <div class="us-card__header">
    US-A10 - Accéder aux paramètres techniques du site
  </div>

  <div class="us-card__meta">
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Acteur</div>
      <span class="badge badge--role-admin">Administrateur</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Effort</div>
      <span class="badge badge--number badge--effort-3">3</span>
    </div>
    <div class="us-card__meta-item">
      <div class="us-card__meta-label">Valeur</div>
      <span class="badge badge--number badge--value-5">5</span>
    </div>
  </div>

  <div class="us-card__body">
    <div class="us-section">
      <h3 class="us-section__title">Description</h3>
      <p>
        En tant qu'<span class="bold">administrateur</span>,<br>
        je souhaite accéder aux paramètres techniques du site<br>
        afin d'assurer son bon fonctionnement.
      </p>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Règles métier</h3>
      <ul class="custom-list">
        <li>Les paramètres techniques sont réservés aux administrateurs.</li>
        <li>Seuls les administrateurs peuvent accéder à cette fonctionnalité.</li>
        <li>Les paramètres sont centralisés dans un espace dédié.</li>
        <li>Toute modification est enregistrée.</li>
        <li>Les modifications sont traçables.</li>
      </ul>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Critères d'acceptation</h3>
      <div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario principal</div>
          <p>
            <span class="bold">Étant donné</span> que je suis connecté en tant qu'administrateur,<br>
            <span class="bold">lorsque</span> j'accède aux paramètres techniques,<br>
            <span class="bold">alors</span> je peux consulter et modifier les paramètres autorisés.
          </p>
        </div>
        <div class="us-scenario">
          <div class="us-scenario__title">Scénario secondaire</div>
          <p>
            <span class="bold">Étant donné</span> qu'un utilisateur non autorisé tente d'accéder à cette fonctionnalité,<br>
            <span class="bold">lorsque</span> il consulte l'URL correspondante,<br>
            <span class="bold">alors</span> l'accès lui est refusé.
          </p>
        </div>
      </div>
    </div>
    <div class="us-section">
      <h3 class="us-section__title">Justification</h3>
      <ul class="custom-list">
        <li>Fonction importante pour l'administration avancée du site.</li>
        <li>Permet de centraliser les paramètres nécessaires au bon fonctionnement de la plateforme.</li>
        <li>Réservée aux administrateurs afin de sécuriser les réglages sensibles.</li>
        <li>Complexité moyenne : gestion des droits d'accès, centralisation des paramètres et traçabilité des modifications.</li>
      </ul>
    </div>

  </div>

</div>

<div class="page-break"></div>

### 3.6. USE CASES

Les cas d'utilisation (Use Cases) décrivent les intéractions entre les différents acteurs et le système d'information de La Socketterie.

Ils permettent de représenter les principales fonctionnalités offertes par l'application en précisant les actions réalisées par chaque utilisateur ainsi que les réponses attendues du système.

Complémentaires aux User Stories, les Use Cases apportent une vision plus fonctionnelle du comportement de l'application et constituent un support de référence pour la conception, le développement et les phases de tests.

#### 3.6.1. Diagrammes des cas d'utilisation

![Diagrammes des cas d'utilisation](./docs/images/Diagramme_Use_Cases.png)

#### 3.6.2. Description des cas d'utilisation

<div class="layout-grid layout-grid--3">
  <div class="use-case">
    <div class="use-case__header">
      <div>UC-01</div>
      <div>Consulter le catalogue</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-V01</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-visitor">Visiteur</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le site est accessible.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le visiteur accède au catalogue.</li>
          <li>Le système récupère les produits du catalogue.</li>
          <li>Le catalogue est affiché.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le visiteur peut consulter les produits du catalogue.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-02</div>
      <div>Rechercher un produit</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-V02</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-visitor">Visiteur</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le catalogue est disponible.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le visiteur accède au catalogue.</li>
          <li>Le visiteur saisit un mot-clé dans le champ de recherche.</li>
          <li>Le système affiche les résultats trouvés.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le visiteur visualise les produits correspondant à sa recherche.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-03</div>
      <div>Consulter une fiche produit</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-V04</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-visitor">Visiteur</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le catalogue est accessible.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le visiteur consulet le catalogue.</li>
          <li>Le visiteur sélectionne un produit.</li>
          <li>Le système affiche la liste détaillée du produit.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le visiteur consulte les informations détaillées du produit.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-04</div>
      <div>Ajouter un produit au panier</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-V08</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-visitor">Visiteur</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>La fiche du produit est affichée et le produit est disponible.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le visiteur sélectionne les options du produit.</li>
          <li>Le visiteur clique sur "Ajouter au panier".</li>
          <li>Le système ajoute le produit au panier.</li>
          <li>Le panier est mis à jour.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le produit est présent dans le panier.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-05</div>
      <div>Consulter le panier</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-V11</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-visitor">Visiteur</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Au moins un produit a été ajouté au panier.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le visiteur ouvre le panier.</li>
          <li>Le système affiche les produits sélectionnés.</li>
          <li>Le système calcule le montant total.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le visiteur visualise le contenu de son panier.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-06</div>
      <div>Contacter l'entreprise</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-V12</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-visitor">Visiteur</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le formulaire de contact est accessible.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le visiteur ouvre la page de contact.</li>
          <li>Le visiteur renseigne les champs du formulaire.</li>
          <li>Le visiteur envoie son message.</li>
          <li>Le système confirme l'envoi du message.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>L'entreprise reçoit la demande du visiteur.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-07</div>
      <div>Créer un compte</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-V16</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-visitor">Visiteur</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le visiteur ne possède pas de compte (id unique via email).</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le visiteur accède au formulaire d'inscription.</li>
          <li>Il renseigne les informations demandées.</li>
          <li>Le système vérifie les données.</li>
          <li>Le compte est créé.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le visiteur possède un compte client.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-08</div>
      <div>Valider une commande</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-C01</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-customer">Client</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le client est connecté et son panier contient au moins un produit.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le client ouvre son panier.</li>
          <li>Le client vérifie le récapitulatif.</li>
          <li>Le client confirme la commande.</li>
          <li>Le système crée la commande.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>La commande est enregistrée et prête à être payée.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-09</div>
      <div>Payer une commande</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-C02</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-customer">Client</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le client est connecté et une commande est en attente de paiement.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le client choisit le paiement par Stripe.</li>
          <li>Le client saisit ses informations de paiement.</li>
          <li>Stripe valide le paiement.</li>
          <li>Le système confirme la commande.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>La commande est payée et confirmée.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-10</div>
      <div>Se connecter</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-C04</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-customer">Client</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le client possède un compte.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le client ouvre la page de connexion.</li>
          <li>Le client saisit son adresse e-mail et son mot de passe.</li>
          <li>Le système vérifie les identifiants.</li>
          <li>Le client est authentifié.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le client est redirigé sur la dernière page ouverte avant connexion et les informations utilisateur sont affichées dans la barre de navigation.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-11</div>
      <div>Consulter son espace personnel</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-C05 / US-C06</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-customer">Client</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le client est connecté.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le client accède à son espace personnel via la barre de navigation.</li>
          <li>Le système affiche les informations du compte.</li>
          <li>Le client consulte ses informations et son historique.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le client accède à l'ensemble des informations de son compte.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-12</div>
      <div>Modifier ses informations</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-C05</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-customer">Client</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le client est connecté.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le client accède à son espace personnel via la barre de navigation.</li>
          <li>Le système affiche les informations du compte.</li>
          <li>Le client modifie ses informations et les enregistre.</li>
          <li>Le système met à jour les informations du compte.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Les informations personnelles du client sont mises à jour.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-13</div>
      <div>Consulter son historique de commande</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-C06</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-customer">Client</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le client est connecté.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le client accède à son espace personnel via la barre de navigation.</li>
          <li>Le client ouvre son historique de commandes.</li>
          <li>Le système affiche les commandes et leur statut.</li>
          <li>Le système met à jour les informations du compte.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le client consulte l'intégralité de ses commandes.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-14</div>
      <div>Ajouter un produit</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-S01</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-sales">Commercial</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le commercial est authentifié et dispose des droits de gestion du catalogue.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le commercial ouvre le formulaire de création d'un produit.</li>
          <li>Le commercial renseigne les information du produit et valide le formulaire.</li>
          <li>Le système enregistre le nouveau produit.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le produit est ajouté au catalogue.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-15</div>
      <div>Modifier un produit</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-S02</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-sales">Commercial</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le commercial est authentifié et le produit existe.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le commercial sélectionne un produit.</li>
          <li>Le commercial modifie les informations souhaitées.</li>
          <li>Le commercial enregistre les modifications.</li>
          <li>Le système met à jour le produit.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Les informations du produit sont mises à jour.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-16</div>
      <div>Supprimer un produit</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-S03</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-sales">Commercial</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le commercial est authentifié et le produit existe.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le commercial sélectionne un produit.</li>
          <li>Le commercial lance la suppression.</li>
          <li>Le système demande une confirmation.</li>
          <li>Le système supprime le produit du catalogue.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le produit n'est plus disponible dans le catalogue.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-17</div>
      <div>Organiser le catalogue</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-S04</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-sales">Commercial</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le commercial est authentifié.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le commercial accède à la gestion du catalogue.</li>
          <li>Le commercial organise les produits par catégorie.</li>
          <li>Le commercial enregistre les modifications.</li>
          <li>Le système met à jour l'organisation du catalogue.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le catalogue est structuré par catégories.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-18</div>
      <div>Consulter les commandes</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-S05</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-sales">Commercial</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le commercial est authentifié.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le commercial accède à la liste des commandes.</li>
          <li>Le système affiche les commandes enregistrées.</li>
          <li>Le commercial consulte les informations d'une commande.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le commercial visualise les commandes clients.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-19</div>
      <div>Modifier le statut d'une commande</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-S06</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-sales">Commercial</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le commercial est authentifié et la commande existe.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le commercial sélectionne une commande.</li>
          <li>Le commercial choisit un nouveau statut.</li>
          <li>Le commercial valide la modification.</li>
          <li>Le système met à jour le statut de la commande.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le nouveau statut est enregistré et est visible par le client.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-20</div>
      <div>Consulter les commandes validées</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-F01</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-accounting">Comptable</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le comptable est authentifié.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le comptable accède aux commandes validées.</li>
          <li>Le système affiche la liste des commandes concernées.</li>
          <li>Le comptable consulte une commande.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Les commandes prêtes à être facturées sont consultables.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-21</div>
      <div>Générer une facture</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-F02</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-accounting">Comptable</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le comptable est authentifié et une commande valide existe.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le comptable sélectionne une commande validée.</li>
          <li>Le comptable lance la génération de la facture.</li>
          <li>Le système crée la facture.</li>
          <li>Le facture est enregistrée et affiliée à la commande de référence.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Une facture est générée pour la commande.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-22</div>
      <div>Exporter les données comptables</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-F03</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-accounting">Comptable</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>Le comptable est authentifié.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>Le comptable accède aux données comptables.</li>
          <li>Le comptable sélectionne les données à exporter.</li>
          <li>Le comptable lance l'export.</li>
          <li>Le système génère le fichier d'export et le télécharge automatiquement.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Les données comptables sont exportées.</p>
      </div>
    </div>
  </div>


  <div class="use-case">
    <div class="use-case__header">
      <div>UC-23</div>
      <div>Gérer le contenu statique</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-A04</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-admin">Administrateur</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>L'administrateur est authentifié.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>L'administrateur accède à la gestion du contenu.</li>
          <li>L'administrateur crée ou sélectionne une page statique.</li>
          <li>L'administrateur crée ou modifie le contenu puis enregistre.</li>
          <li>Le système enregistre les modifications.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le contenu statique du site est crée ou mis à jour.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-24</div>
      <div>Créer un compte interne</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-A05</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-admin">Administrateur</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>L'administrateur est authentifié.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>L'administrateur ouvre le formulaire de création.</li>
          <li>L'administrateur renseigne les informations du collaborateur et valide le formulaire.</li>
          <li>Le système crée le compte.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le nouveau compte interne est disponible.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-25</div>
      <div>Modifier un compte interne</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-A06</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-admin">Administrateur</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>L'administrateur est authentifié et le compte interne existe.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>L'administrateur sélectionne un compte.</li>
          <li>L'administrateur modifie les informations souhaitées et les enregistre.</li>
          <li>Le système met à jour le compte.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Les informations du compte sont mises à jour.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-26</div>
      <div>Désactiver un compte interne</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-A07</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-admin">Administrateur</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>L'administrateur est authentifié et le compte interne existe.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>L'administrateur sélectionne un compte.</li>
          <li>L'administrateur lance la désactivation.</li>
          <li>Le système désactive le compte.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Le compte ne peut plus accéder au système.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-27</div>
      <div>Paramétrer les catégories de produits</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-A08</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-admin">Administrateur</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>L'administrateur est authentifié.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>L'administrateur accède à la gestion des catégories.</li>
          <li>L'administrateur crée, modifie ou désactive une catégorie et enregistre les modifications.</li>
          <li>Le système met à jour le catalogue.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Les catégories de produits sont mises à jour.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-28</div>
      <div>Paramétrer les modes de livraison</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-A09</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-admin">Administrateur</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>L'administrateur est authentifié.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>L'administrateur accède à la gestion des modes de livraison.</li>
          <li>L'administrateur crée, modifie ou désactive un mode de livraison et enregistre les modifications.</li>
          <li>Le système met à jour les modes de livraison.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Les modes de livraison sont disponibles pour les futures commandes.</p>
      </div>
    </div>
  </div>

  <div class="use-case">
    <div class="use-case__header">
      <div>UC-29</div>
      <div>Accéder aux paramètres techniques</div>
    </div>
    <div class="use-case__body">
      <div class="use-case__section">
        <div class="use-case__label">User Story</div>
        <p class="bold">US-A10</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Acteur</div>
        <span class="badge badge--role-admin">Administrateur</span>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Précondition</div>
        <p>L'administrateur est authentifié et dispose des droits nécessaires.</p>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Scénario nominal</div>
        <ol class="use-case__steps">
          <li>L'administrateur ouvre l'espace des paramètres techniques.</li>
          <li>L'administrateur consulte ou modifie les paramètres autorisés et enregistre les modifications.</li>
          <li>Le système applique les nouveaux paramètres.</li>
        </ol>
      </div>
      <div class="use-case__section">
        <div class="use-case__label">Résultat</div>
        <p>Les paramètres techniques et la plateforme sont mis à jour.</p>
      </div>
    </div>
  </div>
</div>

---

## 4. Sprint Backlog prévisionnel

Les User Stories ont été regroupées dans des sprints en suivant une démarche Agile Scrum.

L'ordre de réalisation respecte la logique d'un Produit Minimum Viable (MVP) :
Les fonctionnalités indispensables à la consultation du catalogue, à la préparation d'une commande et au paiement sont développées en priorité, tandis que les fonctionnalités d'administration et les contenus complémentaires sont planifiés dans les derniers sprint.

![Logique du sprint backlog](./docs/images/roadmap-developpement-agile-scrum.png)

<div class="layout-grid layout-grid--2">

  <div class="sprint-card">
    <div class="sprint-card__header">Sprint 1 - Découverte du catalogue et du site</div>
    <div class="sprint-card__body">
      <div class="sprint-card__section">
        <div class="sprint-card__label">Objectif</div>
        <p>Permettre au visiteur de découvrir l'entreprise et les produits.</p>
      </div>
      <div class="sprint-card__section">
        <div class="sprint-card__label">User Stories</div>
        <ul class="sprint-card__list">
          <li>US-V01 — Consulter le catalogue</li>
          <li>US-V02 — Rechercher un produit</li>
          <li>US-V03 — Filtrer les produits</li>
          <li>US-V04 — Consulter une fiche produit</li>
          <li>US-V05 — Visualiser plusieurs photos</li>
          <li>US-V06 — Consulter la présentation de l'entreprise</li>
          <li>US-V07 — Consulter les actualités</li>
        </ul>
      </div>
    </div>
    <div class="sprint-card__footer">7 US • 23 points d'effort</div>
  </div>

  <div class="sprint-card">
    <div class="sprint-card__header">Sprint 2 - Préparer une commande</div>
    <div class="sprint-card__body">
      <div class="sprint-card__section">
        <div class="sprint-card__label">Objectif</div>
        <p>Permettre au visiteur de sélectionner les produits et de préparer une commande.</p>
      </div>
      <div class="sprint-card__section">
        <div class="sprint-card__label">User Stories</div>
        <ul class="sprint-card__list">
          <li>US-V08 — Ajouter un produit au panier</li>
          <li>US-V09 — Modifier la quantité</li>
          <li>US-V10 — Supprimer un produit du panier</li>
          <li>US-V11 — Consulter le panier</li>
        </ul>
      </div>
    </div>
    <div class="sprint-card__footer">4 US • 8 points d'effort</div>
  </div>

  <div class="sprint-card">
    <div class="sprint-card__header">Sprint 3 - Compte client</div>
    <div class="sprint-card__body">
      <div class="sprint-card__section">
        <div class="sprint-card__label">Objectif</div>
        <p>Permettre au visiteur de devenir client.</p>
      </div>
      <div class="sprint-card__section">
        <div class="sprint-card__label">User Stories</div>
        <ul class="sprint-card__list">
          <li>US-V16 — Créer un compte</li>
          <li>US-C04 — Se connecter</li>
          <li>US-C05 — Modifier ses informations</li>
          <li>US-C06 — Consulter l'historique des commandes</li>
        </ul>
      </div>
    </div>
    <div class="sprint-card__footer">4 US • 16 points d'effort</div>
  </div>

  <div class="sprint-card">
    <div class="sprint-card__header">Sprint 4 - Commande et paiement</div>
    <div class="sprint-card__body">
      <div class="sprint-card__section">
        <div class="sprint-card__label">Objectif</div>
        <p>Permettre au client de finaliserso achat.</p>
      </div>
      <div class="sprint-card__section">
        <div class="sprint-card__label">User Stories</div>
        <ul class="sprint-card__list">
          <li>US-C01 — Valider une commande</li>
          <li>US-C02 — Régler une commande</li>
          <li>US-C03 — Recevoir une confirmation</li>
        </ul>
      </div>
    </div>
    <div class="sprint-card__footer">3 US • 16 points d'effort</div>
  </div>

  <div class="sprint-card">
    <div class="sprint-card__header">Sprint 5 - Gestion commerciale</div>
    <div class="sprint-card__body">
      <div class="sprint-card__section">
        <div class="sprint-card__label">Objectif</div>
        <p>Permettre au commercial de gérer le catalogue et les commandes.</p>
      </div>
      <div class="sprint-card__section">
        <div class="sprint-card__label">User Stories</div>
        <ul class="sprint-card__list">
          <li>US-S01 — Ajouter un produit</li>
          <li>US-S02 — Modifier un produit</li>
          <li>US-S03 — Supprimer un produit</li>
          <li>US-S04 — Organiser le catalogue</li>
          <li>US-S05 — Consulter les commandes</li>
          <li>US-S06 — Modifier le statut d'une commande</li>
        </ul>
      </div>
    </div>
    <div class="sprint-card__footer">6 US • 15 points d'effort</div>
  </div>

  <div class="sprint-card">
    <div class="sprint-card__header">Sprint 6 - Gestion comptable</div>
    <div class="sprint-card__body">
      <div class="sprint-card__section">
        <div class="sprint-card__label">Objectif</div>
        <p>Permettre au comptable de gérer les opérations de facturation.</p>
      </div>
      <div class="sprint-card__section">
        <div class="sprint-card__label">User Stories</div>
        <ul class="sprint-card__list">
          <li>US-F01 — Consulter les commandes validées</li>
          <li>US-F02 — Générer une facture</li>
          <li>US-F03 — Exporter les données comptables</li>
        </ul>
      </div>
    </div>
    <div class="sprint-card__footer">3 US • 10 points d'effort</div>
  </div>

  <div class="sprint-card">
    <div class="sprint-card__header">Sprint 7 - Administration interne</div>
    <div class="sprint-card__body">
      <div class="sprint-card__section">
        <div class="sprint-card__label">Objectif</div>
        <p>Permettre à l'administrateur de gérer les paramètres essentiels à la gestion du site.</p>
      </div>
      <div class="sprint-card__section">
        <div class="sprint-card__label">User Stories</div>
        <ul class="sprint-card__list">
          <li>US-A05 — Créer un compte interne</li>
          <li>US-A06 — Modifier un compte interne</li>
          <li>US-A07 — Désactiver un compte interne</li>
          <li>US-A08 — Paramétrer les catégories</li>
          <li>US-A09 — Paramétrer les modes de livraison</li>
          <li>US-A10 — Accéder aux paramètres techniques</li>
        </ul>
      </div>
    </div>
    <div class="sprint-card__footer">6 US • 19 points d'effort</div>
  </div>
  
  <div class="sprint-card">
    <div class="sprint-card__header">Sprint 8 - Gestion du contenu</div>
    <div class="sprint-card__body">
      <div class="sprint-card__section">
        <div class="sprint-card__label">Objectif</div>
        <p>Permettre à l'administrateur de gérer le contenu.</p>
      </div>
      <div class="sprint-card__section">
        <div class="sprint-card__label">User Stories</div>
        <ul class="sprint-card__list">
          <li>US-A01 — Créer une actualité</li>
          <li>US-A02 — Modifier une actualité</li>
          <li>US-A03 — Supprimer une actualité</li>
          <li>US-A04 — Gérer le contenu statique</li>
        </ul>
      </div>
    </div>
    <div class="sprint-card__footer">4 US • 9 points d'effort</div>
  </div>

  <div class="sprint-card">
    <div class="sprint-card__header">Sprint 9 - Finalisation</div>
    <div class="sprint-card__body">
      <div class="sprint-card__section">
        <div class="sprint-card__label">Objectif</div>
        <p>Finaliser la plateforme.</p>
      </div>
      <div class="sprint-card__section">
        <div class="sprint-card__label">User Stories</div>
        <ul class="sprint-card__list">
          <li>US-V12 — Contacter l'entreprise</li>
          <li>US-V13 — Consulter les mentions légales</li>
          <li>US-V14 — Consulter les Conditions Générales de Ventes</li>
          <li>US-V15 — Consulter la politique de confidentialité</li>
        </ul>
      </div>
    </div>
    <div class="sprint-card__footer">4 US • 6 points d'effort</div>
  </div>

</div>

---

## 5. Architecture technique

### 5.1. Architecture générale

| Couche | Rôle |
|--------|------|
| Front-end | Afficher l'interface utilisateur et permettre les interactions |
| Back-end | Gérér la logique métier, les règles de sécurité et l'API |
| Base de données | Stockage des données : utilisateurs, produits, commandes et factures |
| Services tiers | Gérer les fonctionnalités externes comme le paiement |

### 5.2. Technologies retenues

| Couche | Technologie | Justification |
|--------|-------------|---------------|
| Front-end | React + Vite | Interface dynamique adaptée à un site e-commerce |
| Back-end | Node.js + Express | Création d'une API REST légère et maintenable |
| ORM | Sequelize | Communication strcuturée avec la base MySQL |
| Base de données | MySQL | Données relationnelles adaptées aux produits, clients et commandes |
| Paiement | Stripe | Solution de paiement en ligne sécurisée |

![Technologies principales utilisées](./docs/images/technologies.png)

### 5.3. Structure des données

| Entité | Description |
|--------|-------------|
| Utilisateur | Compte client |
| Produit | Article vendu sur la boutique |
| Catégorie | Classement des produits |
| Commande | Achat réalisé par un client |
| DétailCommande | Détail des produits achetés par un client |
| Facture | Document lié à une commande validée |

<div class="page-break"></div>

### 5.4. Flux de données

Le schéma ci-dessous représente le flux de données entre les composants du système e-commerce.

![Représentation du flux de données](./docs/images/flux-de-donnees.png)

<div class="note">
Le front-end envoie des requêtes à l’API REST via HTTP/HTTPS.
L’API traite la logique métier, interagit avec la base de données pour enregistrer ou récupérer les informations et communique avec Stripe pour gérer les paiements. Stripe renvoie ensuite la confirmation de paiement à l’API qui renvoie la réponse au front-end.
</div>

<div class="page-break"></div>

### 5.5. Schéma d'architecture

Le schéma ci-dessous représente l'architecture technique générale du système e-commerce.

![Schéma d'architecture](./docs/images/schema-architecture.png)

---

<div class="page-break"></div>

## 6. Hébergements et services tiers

### 6.1. Besoins d'hébergement identifiés

Le brief ne précise pas le volume exact de produits, de visiteurs ou de clients attendus.
Les choix d'hébergement sont donc réalisés sur la base d'un besoin évolutif, adapté à un site e-commerce professionnel de taille intermédiaire, avec possibilité de montée en charge si le trafic augmente après le reportage télévisé.

| Couche | Besoin identifié |
|--------|------------------|
| Front-end | Hébergement rapide, HTTPS, CDN, déploiement automatisé depuis GitHub |
| Back-end | Exécution d'une API Node.js/Express | variables d'environnement, logs, évolutivité |
| Base de données | Stockage relationnel persistant, sauvegardes, sécurité, montée en capacité possible |
| Paiement | Paiement sécurisé, conformité, gestion des confirmations de paiement |
| Maintenance | Supervision, mises à jour, possibilité dévolution selon le trafic réel |

### 6.2. Comparaison des solutions

<table>
  <colgroup>
    <col style="width: 100px">
    <col style="width: auto">
    <col style="width: 100px">
    <col style="width: auto">
    <col style="width: auto">
  </colgroup>
  <thead>
    <tr>
      <th>Solution</th>
      <th>Description</th>
      <th>Couche concernée</th>
      <th>Avantages</th>
      <th>Inconvénient</th>
    <tr>
  </thead>

  <tbody>
    <tr>
      <td>Netlify</td>
      <td>Hébergement d'applications front-end statiques et SPA</td>
      <td>
        <span class="badge badge--small badge--layer-frontend">Front-end</span>
      </td>
      <td>Déploiement GitHub automatique, CDN mondial, SSL intégré | Peu adapté à l'exécution de services back-end</td>
      <td>Peu adapté à l'exécution de services back-end</td>
    </tr>
    <tr>
      <td>Vercel</td>
      <td>Plateforme cloud optimisée pour les applications web modernes</td>
      <td>
        <span class="badge badge--small badge--layer-frontend">Front-end</span>
      </td>
      <td>Très bonnes performances, intégration React/Next.js</td>
      <td>Coût pouvant augmenter avec le trafic</td>
    </tr>
    <tr>
      <td>Render</td>
      <td>Hébergement de services Node.js et APIs</td>
      <td>
        <span class="badge badge--small badge--layer-backend">Back-end</span>
      </td>
      <td>Déploiement simple, gestion des variables d'environnement</td>
      <td>Mise en veille sur certaines offres</td>
    </tr>
    <tr>
      <td>Railway</td>
      <td>Hébergement d'applications et bases de données managées</td>
      <td>
        <div class="stack-cell">
          <span class="badge badge--small badge--layer-backend">Backend</span>
          <span class="badge badge--small badge--layer-database">DataBase</span>
        </div>
      </td>
      <td>Mise en place rapide, interface intuitive</td>
      <td>Ressources limitées selon le plan</td>
    </tr>
    <tr>
      <td>Amazon EC2</td>
      <td>Serveur virtuel cloud</td>
      <td>
        <span class="badge badge--small badge--layer-backend">Back-end</span>
      </td>
      <td>Contrôle total de l'infrastructure</td>
      <td>Administration plus complexe</td>
    </tr>
    <tr>
      <td>Planet Scale</td>
      <td>Base de données MySQL managée</td>
      <td>
        <span class="badge badge--small badge--layer-database">DataBase</span>
      </td>
      <td>Très haute disponibilité</td>
      <td>Plus complexe pour un projet de taille moyenne |</td>
    </tr>
    <tr>
      <td>Amazon RDS</td>
      <td>Base de données relationnelle managée</td>
      <td>
        <span class="badge badge--small badge--layer-database">DataBase</span>
      </td>
      <td>Sauvegarde et haute disponibilité</td>
      <td>Coût plus élevé</td>
    </tr>
    <tr>
      <td>Stripe</td>
      <td>Solution de paiement en ligne</td>
      <td>
        <span class="badge badge--small badge--layer-payment">Tiers</span>
      </td>
      <td>Sécurisé, documentation complète, leader du marché</td>
      <td>Commission sur les transactions</td>
    </tr>
  </tbody>
</table>

### 6.3. Choix retenus

<table>
  <colgroup>
    <col style="width: 150px">
    <col style="width: 80px">
    <col style="width: auto">
  </colgroup>
  <thead>
    <tr>
      <th>Besoin</th>
      <th>Solution</th>
      <th>Justification</th>
    <tr>
  </thead>

  <tbody>
    <tr>
      <td>Front-end</td>
      <td>
        <span class="badge badge--small badge--layer-frontend">Netlify</span>
      </td>
      <td>Déploiement automatisé, CDN mondial et excellente compatiilité React</td>
    </tr>
    <tr>
      <td>Back-end</td>
      <td>
        <span class="badge badge--small badge--layer-backend">Render</span>
      </td>
      <td>Compatible Node.js/Express et administration simplifiée</td>
    </tr>
    <tr>
      <td>Base de données</td>
      <td>
        <span class="badge badge--small badge--layer-database">Railway</span>
      </td>
      <td>Hébergement MySQL managé simple à maintenir</td>
    </tr>
    <tr>
      <td>Paiement en ligne</td>
      <td>
        <span class="badge badge--small badge--layer-payment">Stripe</span>
      </td>
      <td>Solution sécurisée et adaptée à un site e-commerce professionnel</td>
    </tr>
  </tbody>
</table>

![Hébergement des couches](./docs/images/hebergements.png)

---

## 7. Organisation du projet

### 7.1. Kanban



### 7.2. Workflow Git



---

## 8 Diagramme de Gantt



---

## 9. Estimation des coûts



---

## 10. Conclusion