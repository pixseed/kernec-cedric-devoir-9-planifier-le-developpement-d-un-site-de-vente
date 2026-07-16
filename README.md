# La Socketterie — Planification d'un site e-commerce

![Projet](https://img.shields.io/badge/Projet-Planification-4e816d)
![Formation](https://img.shields.io/badge/Formation-DWWM-77b099)
![Planification](https://img.shields.io/badge/Planification-WBS%20%7C%20Kanban%20%7C%20Gantt-f5895d)
![Version](https://img.shields.io/badge/Version-1.0-f6a447)

Planification du développement du futur site e-commerce de **La Socketterie**, réalisée dans le cadre de la formation **Développeur Web et Web Mobile**.

Le projet couvre l'analyse des besoins, la définition de la solution technique, la formalisation du Product Backlog et l'organisation prévisionnelle du développement.

## Contexte

**La Socketterie** est une entreprise créée en 2019 et spécialisée dans la vente de chaussettes dépareillées.

L'entreprise dispose d'une boutique physique à Nice et souhaite développer sa visibilité grâce à un site web intégrant une boutique en ligne.

Le projet doit répondre à une contrainte temporelle majeure : un reportage télévisé consacré à l'entreprise doit être tourné trois mois après le lancement du projet puis diffusé un mois plus tard.

Une première version présentable doit donc être disponible pour le tournage et le site complet doit être fonctionnel avant la diffusion du reportage.

## Objectifs du projet

Le projet vise à planifier le développement d'une solution permettant :

- de présenter l'entreprise et ses contenus publics ;
- de consulter et rechercher les produits ;
- de gérer un panier et de passer une commande en ligne ;
- de suivre les commandes et les factures ;
- de gérer les produits et le catalogue ;
- d'administrer les comptes internes.

La mission porte sur la **conception technique et la planification du développement**. L'application n'est pas développée dans ce dépôt.

## Contraintes du projet

La planification prend notamment en compte :

- le tournage du reportage trois mois après le lancement du projet ;
- la diffusion du reportage un mois après le tournage ;
- la mise à disposition d'un MVP fonctionnel pour le tournage ;
- la disponibilité à 80 % des développeurs Front-end et Back-end ;
- une intervention maximale de cinq jours par développeur freelance (2 freelances) ;
- le respect des réglementations applicables ;
- une démarche d'écoconception ;
- une utilisation responsive sur différents types de médias.

Le projet est planifié du **13 juillet 2026 au 16 octobre 2026**.

## Solution technique retenue

L'architecture retenue repose sur une séparation entre le Front-end, l'API Back-end et la base de données relationnelle.

| Couche | Technologies retenues |
| --- | --- |
| Front-end | React, Vite, React Router |
| Back-end | Node.js, Express |
| Accès aux données | Sequelize |
| Base de données | MySQL |
| Paiement | Stripe |
| Hébergement Front-end | Netlify |
| Hébergement Back-end | Render |
| Base de données | Railway |

L'application est organisée selon une architecture en couches afin de séparer la présentation, la logique applicative, l'accès aux données et le stockage.

## Organisation et planification

Le projet est organisé à partir d'une **Work Breakdown Structure (WBS)** permettant de décomposer les travaux en tâches planifiables.

Le suivi prévisionnel repose sur :

- un Product Backlog structuré en Epics et User Stories ;
- une estimation de la valeur métier et de l'effort ;
- un Sprint Backlog prévisionnel ;
- une matrice de traçabilité fonctionnelle ;
- un Kanban de suivi des tâches ;
- un diagramme de Gantt ;
- une répartition des responsabilités entre les collaborateurs.

Le développement est organisé selon une logique de **Minimum Viable Product (MVP)** afin de prioriser les fonctionnalités nécessaires à la présentation et au parcours d'achat avant le tournage du reportage.

## Livrables

Le dossier de planification comprend notamment :

- l'analyse des acteurs et des besoins ;
- le Product Backlog ;
- les User Stories ;
- les Use Cases ;
- le Sprint Backlog prévisionnel ;
- la matrice de traçabilité fonctionnelle ;
- la description de l'architecture technique ;
- la comparaison des solutions d'hébergement ;
- la Work Breakdown Structure ;
- le Kanban ;
- le diagramme de Gantt ;
- l'estimation des coûts ;
- le dossier final au format PDF.

## Structure du dépôt

```
.
├── .github/
│   ├── ISSUE_TEMPLATE/
│   └── pull_request_template.md
├── assets/
│   ├── brief/
│   └── logos/
├── docs/
│   ├── images/
│   └── sources/
├── styles/
├── project.md
├── project.pdf
└── README.md
````

- `project.md` : source principale du dossier de planification ;
- `project.pdf` : livrable final exporté au format PDF ;
- `markdown-pdf.css` : styles utilisés pour la génération du document ;
- `docs/images/` : captures et ressources visuelles intégrées au dossier ;
- `docs/sources/` : documents sources et tableurs utilisés pour la planification ;
- `.github` : modèles utiisés pour le suivi du projet sur GitHub ;
- `assets/brief/` : consignes et brief du projet à réaliser ;
- `assets/logos/` : logos du client.

## Liens utiles

- [GitHub Project : Backlog, Kanban et diagramme de Gantt.](https://github.com/users/pixseed/projects/3/views/1)

## Informations

| Éléments | Valeur |
|----------|--------|
| Version | ![Version](https://img.shields.io/badge/1.0.0-2E549E) |
| Auteur | ![Pseudo GitHub](https://img.shields.io/badge/Github-Pixseed-1C1C1C?logo=github) ![Auteur](https://img.shields.io/badge/Cédric%20Kernec-1C1C1C) |
| Formation | ![Formation](https://img.shields.io/badge/DWWM-Développeur%20Web%20&%20Web%20Mobile-21B07F) |