# Programme d'informatique — CPGE scientifiques (Maroc)

> **Documents de référence transmis :** programmes et progressions de juillet 2022, Ministère de l'Éducation nationale, du Préscolaire et des Sports — Centre National de l'Innovation Pédagogique et de l'Expérimentation.
>
> Ce document est une **synthèse pédagogique** des quatre PDF fournis, et non une reproduction réglementaire. Pour les exigences détaillées, consulter les documents sources. Les appellations « programme officiel » (première année) et « progression 2022-2023 » (deuxième année) sont conservées telles qu'elles apparaissent dans les PDF.

## Navigation

- [Première année — MPSI, PCSI et TSI 1](#première-année--mpsi-pcsi-et-tsi-1)
- [Deuxième année — MP et PSI](#deuxième-année--mp-et-psi)
- [Deuxième année — TSI 2](#deuxième-année--tsi-2)
- [Points particuliers et limites](#points-particuliers-et-limites)
- [Progression par mois](progression-pedagogique.md)

## Première année — MPSI, PCSI et TSI 1

Les deux documents transmis pour **MPSI/PCSI** et **TSI première année** décrivent les mêmes grandes rubriques et le même ordre mensuel.

### 1. Représentation de l'information
- Entiers en bases 2 et 16 ; conversion entre bases.
- Entiers signés : binaire signé, complément à deux.
- Nombres réels : virgule fixe et flottante, simple et double précision.

### 2. Initiation à Python et algorithmique
- Programme, variables, types, affectation, commentaires.
- Entrées/sorties `input`, `print`, `eval` ; opérations arithmétiques.
- Conditions `if`, `elif`, `else`, opérateurs de comparaison et logiques ; indentation.
- Boucles `for`, `while`, boucles imbriquées ; `break`, `continue`.
- Fonctions, modules, `return`, portée des variables, assertions, récursivité simple.
- Terminaison et correction : variants, invariants, récurrence/induction structurelle.

### 3. Collections et algorithmique élémentaire
- Listes : création, parcours, copie, tranches, `append`, `pop`, `insert`.
- Recherche séquentielle et dichotomique.
- Tri par sélection, tri à bulles, tri par insertion, tri par comptage.
- Chaînes de caractères et distinction mutable / non mutable.
- Dictionnaires, tuples, ensembles ; piles et files, notamment `collections.deque`.

### 4. Fichiers et calcul scientifique
- Fichiers texte : ouverture, lecture, écriture.
- Bibliothèques `numpy`, `scipy` et `matplotlib.pyplot`.
- Images : affichage, inversion, niveaux de gris, transformations, histogramme, seuillage, flou, détection de contours (initiation).
- Méthodes numériques : dichotomie, Newton ; intégration par rectangles et trapèzes, méthodes composites ; Euler et équations différentielles ordinaires (EDO), y compris systèmes et équations d'ordre supérieur ramenés à un problème de Cauchy.

## Deuxième année — MP et PSI

### 1. Analyse d'algorithmes et tris
- Coûts temporels, notation `O`, ordre de grandeur, pire cas ; complexité récursive et introduction à la complexité spatiale.
- Révision des tris de première année ; tri fusion et tri rapide ; comparaison des coûts.

### 2. Arbres binaires
- Vocabulaire, représentation par listes, hauteur et profondeur.
- Parcours en largeur et profondeur (préfixe, infixe, suffixe).
- Tas min/max et arbres binaires de recherche : recherche, insertion, suppression.

### 3. Stratégies algorithmiques
- Algorithmes gloutons et contre-exemples à l'optimalité ; rendu de monnaie, affectation de salles, sélection d'activités, sac à dos.
- Programmation dynamique : approche ascendante (*bottom-up*), descendante (*top-down*) et mémoïsation ; comparaison avec l'approche gloutonne.
- Applications : ordonnancement, plus longue sous-chaîne commune, distance de Levenshtein, sac à dos.
- Notion d'heuristique et recuit simulé ; exemples de voyageur de commerce et de sac à dos.

### 4. Graphes
- Graphes orientés / non orientés, degrés, chemins, cycles, connexité, eulérien, hamiltonien.
- Listes et matrices d'adjacence ; parcours BFS/DFS, `collections.deque`.
- Graphes pondérés, Dijkstra (poids positifs).
- Applications mentionnées : cycles, connexité, A*, coloration et Floyd-Warshall.

### 5. Images, intelligence artificielle et calcul scientifique
- Traitement d'images élémentaire avec Matplotlib.
- Classification supervisée : *k*-plus proches voisins (kNN), matrice de confusion.
- Partitionnement non supervisé : *k*-moyennes (k-means).
- EDO et problème de Cauchy, influence du pas de résolution.

### 6. Bases de données relationnelles et SQL (SQLite)
- Tables, colonnes, lignes, domaines, schéma, entité-association, cardinalités, clés primaires/étrangères.
- Insertion, modification, suppression ; `SELECT`, `WHERE`, `AS`, `DISTINCT`, `LIMIT`, `OFFSET`, `ORDER BY`.
- Opérations ensemblistes `UNION`, `INTERSECT`, `EXCEPT` ; produit cartésien, jointures internes (équi-jointures).
- Agrégations `MIN`, `MAX`, `SUM`, `AVG`, `COUNT`, `GROUP BY`, `HAVING` ; requêtes imbriquées.
- Révision et préparation aux concours (CNC).

## Deuxième année — TSI 2

### 1. Analyse d'algorithmes, tris et arbres
- Complexité des algorithmes itératifs et récursifs, notation `O`, complexité spatiale élémentaire.
- Tri fusion et tri rapide ; comparaison avec les tris de première année.
- Arbres binaires, parcours, tas min/max, arbres binaires de recherche.

### 2. Graphes
- Représentations par listes ou matrices d'adjacence ; BFS et DFS.
- Graphes pondérés ; Dijkstra avec poids positifs.
- Applications : détection de cycles, connexité, A*, coloration, Floyd-Warshall.

### 3. Images et intelligence artificielle
- Manipulations élémentaires d'images (Matplotlib).
- Classification kNN et matrice de confusion ; partitionnement k-means.

### 4. Calcul scientifique
- Méthode de Gauss : systèmes linéaires inversibles, opérations élémentaires, pivot partiel, inverse et déterminant.
- EDO : équations d'ordre 1, réduction d'un système ou d'une équation d'ordre supérieur au problème de Cauchy ; influence du pas.
- Interpolation polynomiale de Lagrange, y compris par morceaux.

### 5. Bases de données relationnelles (SQLite)
- Modèle relationnel, clés, cardinalités et modèle entité-association.
- Manipulation de lignes, requêtes `SELECT`, filtres, tris, limites.
- Opérateurs `UNION`, `INTERSECT`, `EXCEPT` ; jointures internes et produit cartésien.
- Agrégations et requêtes imbriquées.
- Révision et préparation aux concours (CNC).

## Points particuliers et limites

- **MPSI/PCSI et TSI 1 :** les fichiers binaires sont indiqués *hors programme*.
- **MP/PSI et TSI 2 :** arbres n-aires et tri par tas sont indiqués *hors programme* ; cela n'exclut pas les tas comme structures de données.
- **MP/PSI et TSI 2 :** pour SQLite, création/modification/suppression des tables et récupération d'une requête SQL depuis Python sont indiquées *hors programme*.
- **MP/PSI :** glouton, programmation dynamique et recuit simulé sont prévus dans la progression transmise ; ils ne figurent pas dans le document TSI 2 transmis.
- **TSI 2 :** méthode de Gauss et interpolation de Lagrange sont explicitement programmées ; MP/PSI présente ces méthodes comme des thèmes possibles de révision en fin d'année, et non comme des séquences équivalentes dans sa progression mensuelle.
- **Compléments pédagogiques :** tout sujet ajouté ultérieurement (par exemple Bellman–Ford) doit être clairement identifié comme *approfondissement*, sauf mention explicite dans les documents de référence.

## Sources PDF à conserver dans le dépôt (si vous disposez du droit de diffusion)

1. `MPSI-PCSI.pdf` — *Programme officiel d'informatique*, juillet 2022.
2. `TSI 1.pdf` — *Programme officiel d'informatique*, juillet 2022.
3. `MP-PSI.pdf` — *Progression 2022-2023*, juillet 2022.
4. `TSI 2.pdf` — *Progression 2022-2023*, juillet 2022.

> **Note sur la diffusion :** ne pas republier les PDF sources sans vérifier les conditions de réutilisation. La licence de vos propres cours ne s'étend pas automatiquement aux documents ministériels.
