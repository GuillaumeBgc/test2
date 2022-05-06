---
title: 'Chapitre 1 : ACP avec FactoMineR'
description:
  "Ce chapitre présente l'analyse en composantes principales illustrée à l'aide du package FactoMineR 
  ATTENTION : chapitre en cours de développement, les intitulés ne correspondent pas au contenu pour le moment. "
prev: null
next: /chapter2
type: chapter
id: 1
---

<exercise id="1" title="Préparation des données" type="slides">

<slides source="chapter1_01_introduction">
</slides>

</exercise>

<exercise id="2" title="Choix des variables et individus">

### Importation des données 
Première chose, on importe la librairie contenant les jeux de données nécéssaires.

<codeblock id="01_02_01"></codeblock>
jeux de données inclus :

  * decathlon
  * tea
  * wine
  * lipsticks
  * sensochoc
  * perfumes\_qda\_experts

Ici, nous chargeons le jeu de données 'decathlon' portant sur la perfomance d'athlètes lors d'un decathlon en solution, mais vous pouvez charger le jeu de donnée que vous souhaitez. 

<codeblock id="01_02_02"></codeblock>


Nous pouvons également lancer le package FactoMineR

<codeblock id="01_02_03" ></codeblock>
### Visualiser les données

Avant de réaliser une ACP il est important de connaître les données sur lequelles l'étude va être réalisée et la problématique de l'étude. Ici, nous avons des données concernant des performances à un decathlon, l'objectif sera d'étudier le profil des participants en fonctions de leur performance.

Dans un premier temps, la fonction `head`permet de visualiser les premières lignes du jeu de données.


</exercise>

<exercise id="3" title="Individus et variables actifs">

This is a code exercise. The content can be formatted in simple Markdown – so
you can have **bold text**, `code` or [links](https://spacy.io) or lists, like
the one for the instructions below.

- These are instructions and they can have bullet points.
- The code block below will look for the files `exc_01_03`, `solution_01_03` and
  `test_01_03` in `/exercises`.

<codeblock id="01_03">

This is a hint.

</codeblock>

</exercise>

<exercise id="4" title="Pratique">

video de statquest sur l'ACP: 

<html><center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/FgakZw6K1QQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>
<br></html>

<center>
<h1 style="color: blue; text-align:center;font-family:Arial; font-size: xx-large;">QUIZZ</h1>
</center>

![](https://github.com/GuillaumeBgc/test2/blob/binder/static/Graph_quiz1.png?raw=true)

A quoi correspond l'ordonnée?

<choice id=1>
<opt text="Population française">
Presque!
</opt>

<opt text="pourcentage de variance expliquée" correct="true">
Good job!
</opt>

<opt text="aucun des trois">
This is not correct.
</opt>
</choice>

résoudre l'equation : 
<img src="https://render.githubusercontent.com/render/math?math=-x^{2}-1=0">


<choice id=2>
<opt text="x=i" correct="true">

</opt>

<opt text="x=-i" correct="true">
</opt>

<opt text="Pas de solutions réelles" correct="true">
</opt>
</choice>

Note : pas de possibilité de mettre plusieurs choix pour le moment, à voir.
</exercise>

