---
theme : "white"
transition: "slide"
highlightTheme: "monokai"
logoImg: "./img/logoClaveille.png"
mouseWheel : true
slideNumber: false
zoom: true
touch: true
title: "SI - Liaisons cinématiques -"
height: '1024'
width: '1280'
margin: '0.04'
minScale: '0.2'
maxScale: '2.0'
---

<img height='400' data-src='./img/logoSI.png'>

## Liaisons cinématiques

---

### 1- Liaisons entre solides
- Une liaison entre deux solides 1 et 2 est créée par le contact d'une surface du solide 1 sur une surface du solide 2
- Il existe 6 déplacements élémentaires indépendants (6 degrés de liberté.) ➔ Tx, Ty, Tz et Rx, Ry, Rz

<img height='300' data-src='./img/degresLiberte.png'>

--

### 2- Liaisons cinématiques normalisées
Il existe 10 liaisons élémentaires. Les trois suivantes sont à connaître parcoeur.

--

<img width='900' data-src='./img/pivot.png'>

--

<img width='900' data-src='./img/glissiere.png'>

--

<img width='900' data-src='./img/pivotGlissant.png'>

---

### 3- Classe d’équivalence cinématique.
- Une **classe d’équivalence** cinématique (aussi appelé **groupe cinématique**) est un ensemble de solides qui n’ont aucun mouvement relatif.
- Dans un mécanisme, on commence par définir les classes d’équivalence puis, on recherche les liaisons entre ces classes d’équivalence.

---

### 4- Graphe de liaison
Un graphe des liaisons énumère l'ensemble des classes d'équivalence d'un mécanisme et ses liaisons.

--

- Classe d'équivalences sont représentées par des cercles 
- Les liaisons cinématiques sont représentées par des traits entre deux cercles.

--

#### Chaine ouverte

<img height='300' data-src='./img/chaineOuverte.png'>

--

#### Chaîne fermée

<img height='300' data-src='./img/chaineFermée.png'>

--

#### Chaîne complexe

<img height='300' data-src='./img/chaineComplexe.png'>

---

### 5- Représentation schématique des mécanismes
- Le schéma cinématique d’un mécanisme est un modèle filaire du mécanisme utilisant les symboles normalisés des liaisons.
- Les groupes cinématiques sont représentés très schématiquement (souvent un simple trait).
- Ce modèle est utile tant au niveau de la conception que de l’analyse (cinématique, statique, trajectoire,....)

--

#### Exemple : Moteur d'aéromodélisme

<img height='300' data-src='./img/moteur.png'>

--

#### Exemple : Graphe des liaisons

<img height='300' data-src='./img/moteurGrapheL.png'>

--

#### Schéma cinématique en 2D

<img height='500' data-src='./img/moteurSchema2D.png'>

--

#### Schéma cinématique en 3D

<img height='500' data-src='./img/moteurSchema3D.png'>

---

### 6- Fermeture géométrique des mécanismes à chaînes fermés.

- Dans un système en chaîne fermée, il existe une relation vectorielle liant les
points caractéristiques de chaque solide : 

<img height='150' data-src='./img/fermetureGeo.png'>