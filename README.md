# Dashboard interactif – FC Barcelona

## Présentation du projet

**Dasboard_Bar-a** est un projet de **visualisation interactive de données sportives** consacré au **FC Barcelona**.

L'objectif du projet est de concevoir un tableau de bord web permettant de transformer des données sportives stockées dans un fichier Excel en une interface visuelle et interactive.

À travers différents éléments de visualisation, le dashboard permet d'explorer les données du club et d'en faciliter la lecture et l'interprétation.

Ce projet s'inscrit dans une démarche de développement de compétences en **data visualisation**, **développement web** et **analyse de données**.

---

## Objectifs

Le projet a pour principaux objectifs de :

* 📊 transformer des données brutes en visualisations interactives ;
* ⚽ proposer une interface dédiée à l'analyse de données du FC Barcelona ;
* 🔎 faciliter l'exploration et la compréhension des données sportives ;
* 💻 expérimenter la création d'un dashboard entièrement accessible depuis un navigateur web ;
* 🎨 travailler sur la conception d'une interface utilisateur claire et intuitive ;
* 📈 mettre en pratique des techniques de visualisation et de présentation de données.

---

## Aperçu du dashboard

Le dashboard est conçu comme une interface web interactive permettant de présenter et d'explorer les données relatives au FC Barcelona.

L'application s'appuie sur plusieurs composants :

* une structure HTML pour organiser l'interface ;
* des styles CSS pour la mise en forme et l'expérience utilisateur ;
* du JavaScript pour la logique et l'interactivité ;
* un fichier Excel contenant les données utilisées par le projet ;
* un dossier `assets` regroupant les ressources nécessaires à l'interface.

---

## 🛠️ Technologies utilisées

| Technologie       | Utilisation                             |
| ----------------- | --------------------------------------- |
| **HTML5**         | Structure de l'interface web            |
| **CSS3**          | Mise en forme et design du dashboard    |
| **JavaScript**    | Logique, traitement et interactivité    |
| **Excel (.xlsx)** | Source de données du projet             |
| **Git / GitHub**  | Gestion du code source et versionnement |

---

## Structure du projet

```text
Dasboard_Bar-a/
│
├── assets/
│   └── Ressources utilisées par le dashboard
│
├── Barca.xlsx
│   └── Jeu de données utilisé pour alimenter les visualisations
│
├── barca.css
│   └── Feuille de styles du dashboard
│
├── barca.js
│   └── Logique JavaScript et fonctionnalités interactives
│
├── index.html
│   └── Page principale du dashboard
│
└── README.md
    └── Documentation du projet
```

---

## Installation et utilisation

### 1. Cloner le dépôt

```bash
git clone https://github.com/AnicetYAO225/Dasboard_Bar-a.git
```

### 2. Accéder au dossier

```bash
cd Dasboard_Bar-a
```

### 3. Lancer le dashboard

Le projet étant une application web côté client, il peut être consulté en ouvrant le fichier :

```text
index.html
```

dans un navigateur web.

Pour une utilisation optimale, il est recommandé de lancer le projet à l'aide d'un serveur local.

Par exemple, avec Python :

```bash
python -m http.server 8000
```

Puis accéder à :

```text
http://localhost:8000
```

---

## Données

Les données utilisées dans le projet sont regroupées dans le fichier :

```text
Barca.xlsx
```

Ce fichier constitue la source de données utilisée pour alimenter les éléments du dashboard.

Le choix du format Excel permet de conserver une source de données facilement modifiable et exploitable dans le cadre d'expérimentations de visualisation.

Pour une utilisation dans un contexte de production, il serait possible de faire évoluer l'architecture vers :

* une base de données ;
* une API ;
* un fichier CSV ;
* des données récupérées automatiquement depuis une source externe.

---

## Approche de visualisation

Le projet repose sur le principe de **Data Visualization**, qui consiste à transformer des données structurées en représentations visuelles permettant d'identifier plus facilement :

* les tendances ;
* les évolutions ;
* les différences entre catégories ;
* les indicateurs clés ;
* les éventuelles relations entre différentes variables.

L'utilisation d'un dashboard interactif permet ainsi de passer d'une simple consultation de données à une **exploration dynamique de l'information**.

---

## Perspectives d'amélioration

Plusieurs évolutions pourraient être envisagées afin d'enrichir le projet :

* 📅 ajouter un filtre temporel ;
* 🔍 permettre la sélection de différentes catégories de données ;
* 📈 intégrer davantage de visualisations ;
* ⚽ ajouter des indicateurs de performance supplémentaires ;
* 🔄 automatiser la mise à jour des données ;
* 🌐 connecter le dashboard à une API de données sportives ;
* 📱 améliorer l'affichage sur mobile et tablette ;
* 🎨 optimiser l'ergonomie et le design de l'interface ;
* 📊 ajouter des graphiques permettant des comparaisons historiques ;
* 🗃️ remplacer progressivement le fichier Excel par une source de données automatisée.

---

## Compétences mobilisées

Ce projet permet de mettre en pratique plusieurs compétences :

* **Data Visualisation**
* **Analyse de données**
* **Développement web**
* **JavaScript**
* **HTML / CSS**
* **Gestion de données Excel**
* **Conception d'interfaces interactives**
* **Gestion de projet avec Git et GitHub**

---

## Statut du projet

 **Projet expérimental / en cours de développement**

Le dashboard constitue une base de travail destinée à être enrichie progressivement par de nouvelles fonctionnalités, de nouvelles visualisations et éventuellement par l'intégration de données actualisées.

---

## Auteur

**Anicet YAO**

Projet personnel de développement et de visualisation interactive de données.

GitHub : **AnicetYAO225**

---

## Dépôt GitHub

Le code source du projet est disponible sur GitHub :

**Dasboard_Bar-a**

https://github.com/AnicetYAO225/Dasboard_Bar-a

---

## Licence

Sauf indication contraire, le code source de ce projet est mis à disposition à des fins d'apprentissage, d'expérimentation et de portfolio.

Les données utilisées dans le fichier `Barca.xlsx` peuvent être soumises à leurs propres conditions d'utilisation et droits de diffusion.
