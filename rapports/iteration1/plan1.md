# Plan d'itération 1


## Étapes jalons


| Étape jalon          | Date       |
| :------------------- | :--------- |
| Début de l'itération | 2022/02/01 |
| Démo (séance 5)      | 2022/02/15 |
| Fin de l'itération   | 2022/02/15 |

## Objectifs clés


- Présenter une démonstration technique de CU01a avec tests (1 points).
- Présenter une démonstration technique de CU01b avec tests (2 points).


## Affectations d'éléments de travail


Les éléments de travail suivants seront abordés dans cette itération:

| Nom / Description                | Priorité | [Taille estimée (points)](#commentEstimer "Comment estimer?") | Assigné à (nom) | Documents de référence |
| -------------------------------- | -------: | --------------------------: | --------------- | ---------------------- |
| CU01                             | 1        | 3 (total)                           | (tous)          | Exigences pour le lab  |
|   CU01a - conception                |          |                1             | Félix Morin    |                        |
|   CU01b - conception    |          |               2              | Félix Fortier          |                        |
|   CU01a - test |          |              1               | Cédric Audy          |                        |
| CU01b - test                             |         |      2                      | Félix Morin         | |
| CU01a - implémentation                |          |      1                       | Hugo Beaulieu         |                        |
| CU01b - implémentation     |          |      2                       | Félix Fortier          |                        

## Problèmes



| Problème                                                                                             | Notes |
| ---------------------------------------------------------------------------------------------------- | ----- |
|                                    |       |
|                                   |       |
|  |
|  |       |

## Critères d'évaluation



- 100% des cas de test passent.
- Démonstration des fonctionnalités CU01a et CU01b pas à pas avec l’auxiliaire d'enseignement a reçu une réponse favorable.

## Évaluation


<!-- GitHub ne supporte pas les tables sans en-tête: https://stackoverflow.com/a/17543474/1168342 -->
| Résumé | |
| ------------------------------------- | ------------------------------------------------------------------------ |
| Cible d'évaluation                    | Itération 1<!-- *Cela pourrait être toute l'itération ou simplement un composant spécifique* -->                            |
| Date d'évaluation  |   2022/02/15 |
| Participants       | **Coéquipiers** : Félix Fortier, Félix Morin, Cédric Audy, Hugo Beaulieu<br> **auxiliaire d'enseignement** : Nicolas Beaulieu |
| État du projet     | 🔴 <!-- 🔴🟠🟢 *Rouge, Orange, ou Vert.* --> |

### Questions d'évaluation
Regardez votre diagramme TPLANT et répondez aux questions suivantes?
1. Est-ce qu’il y a un décalage de représentation?
  - Est-ce que tous les noms de classe ont un rapport avec le domaine?
2. Est-ce que l’architecture en couche est respectée?
   - Est-ce que les contrôleurs GRASP sont bien identifiés?
   - Est-ce que les paramètres des opérations système sont tous de type primitif ou sont des objets de paramètres de type primitif?
   - Est-ce que vous avez un fichier de route par contrôleur?
3. Évaluer votre conception par rapport aux GRASP "forte cohésion" et "faible couplage"
   - Avez-vous des classes qui sont couplées avec "beaucoup" d'autres classes?
   - Avez-vous des classes qui ont beaucoup de responsabilités (d'opérations)?
     - Faite surtout attention aux responsabilités que vous avez données à vos contrôleurs.
4. Y a-t-il des problèmes de Code smell à identifier avec l'aide de TPLANT
   1. Mysterious name relié au décalage des représentations ou pas
      1. Identifier le renommage (réusinage) éventuel de classe et/ou méthodes
   2. Large class (cohésion)
      1. Proposer d'appliquer le réusinage Extract class / GRAPS fabrication pure 
   3. Trop de paramètres (4+)
      1. Proposer d'appliquer le réusinage Objet de paramètre
   
### Évaluation par rapport aux objectifs



- Présenter une démonstration technique de CU01a avec tests (1 points).
- Présenter une démonstration technique de CU01b avec tests (2 points).


### Éléments de travail: prévus vs réalisés


#####Éléments prévus :
- CU01a et CU01b - conception, test, implémentation réalisés à 100%

#####Éléments réalisés :
- À déterminer
 
### Évaluation par rapport aux résultats selon les critères d'évaluation



## Autres préoccupations et écarts


Nous avons discuté en équipe de nos forces et faiblesses et avons de décider de s'entraider dans nos tâches si nécessaire.

## Évaluation du travail d'équipe


### Retrait d'un membre de l'équipe pour contribution non significative

N/A


---

<a name="commentPlanifier">Comment planifier une itération selon le
    processus unifié :</a>
    <https://docs.google.com/a/etsmtl.net/document/d/1xeCCdR4-sTznTPaSKYIl4l_bQi-gE5stPWSA5VArRlY/edit?usp=sharing>

<a name="commentEstimer">Comment estimer la taille :</a>
    <https://docs.google.com/a/etsmtl.net/document/d/1bDy0chpWQbK9bZ82zdsBweuAgNYni3T2k79xihr6CuU/edit?usp=sharing>
