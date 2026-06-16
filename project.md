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
  - [3. User Stories](#3-user-stories)
  - [4. Architecture technique](#4-architecture-technique)
  - [5. Hébergements et services tiers](#5-hébergements-et-services-tiers)
  - [6. Organisation du projet](#6-organisation-du-projet)
    - [6.1. Kanban](#61-kanban)
    - [6.2. Workflow Git](#62-workflow-git)
  - [7 Diagramme de Gantt](#7-diagramme-de-gantt)
  - [8. Estimation des coûts](#8-estimation-des-coûts)
  - [9. Conclusion](#9-conclusion)

---
<div class="page-break"></div>

## 1. Présentation du projet

### 1.1. Contexte du projet

**La Socketterie** est une entreprise française créée en 2019 et **spécialisée dans la vente de chaussettes dépareillées tricotées**.

L'entreprise dispose actuellement d'une boutique physique située à Nice et **souhaite développer sa présence numérique afin d'augmenter sa visibilité et de commercialiser ses produits en ligne**.

Cette demande intervient dans un contexte particulier puisque l'entreprise participera prochainement à un reprotage télévisé. **Le tournage est prévu dans un délai de trois mois et la diffusion un mois plus tard**.

<div class="card card--danger">
  Le site internet devra donc être suffisament avancé pour être présenté lors du tournage et totalement opérationnel avant la diffusion du reportage afin de tirer profit de cette visibilité médiatique.
</div>

L'entreprise **cible principalement une population jeune agée de 20 à 35 ans**. Le futur site devra donc proposer une expérience moderne, intuitive et adaptée aux usages actuels du commerce en ligne.

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

  </tbody>
    <tr>
      <td>Visiteurs</td>
      <td>
        <span class="badge badge--critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Clients</td>
      <td>
        <span class="badge badge--critical">Critique</span>
      </td>
    </tr>
    <tr>
      <td>Administrateur</td>
      <td>
        <span class="badge badge--high">Haute</span>
      </td>
    </tr>
    <tr>
      <td>Commerciaux</td>
      <td>
        <span class="badge badge--medium">Moyenne</span>
      </td>
    </tr>
    <tr>
      <td>Comptables</td>
      <td>
        <span class="badge badge--medium">Moyenne</span>
      </td>
    </tr>
  </tbody>
</table>

---

## 3. User Stories



---

## 4. Architecture technique



---

## 5. Hébergements et services tiers



---

## 6. Organisation du projet

### 6.1. Kanban



### 6.2. Workflow Git



---

## 7 Diagramme de Gantt



---

## 8. Estimation des coûts



---

## 9. Conclusion