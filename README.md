# Algorithme-Evolutionnaire
Création d'un algorithme évolutionnaire pour le partionnement d'un ensemble en deux sous emsembles de même somme.

On adapte un algorithme génétique simple à un problème assez complexe tel que le MaxOne, c'est à dire, le problème de la partition, qui est un problème NP-Complet.

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#problem">Problem</a></li>
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
Ce problème a été démontré être NP-complet, même si il peut être résolu en temps pseudopolynomial par programmation dynamique.
Nous essayons donc par cet algorithme de trouver une solution qui sur de grands ensembles s'avère plus performant. 

### Problem

* Le problème de la partition, en tant que problème de décision, peut être énoncé comme suit : étant donné un ensemble fini A et une taille t(a) appartenant à N \ 0 pour chaque a de A, existe-t-il un sous-ensemble A' issu de A tel que :

![Screenshot](partition.JPG)

