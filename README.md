# Les fondements du text mining

## Méthodes basiques

- len : Déterminer  la langueur du texte.
- split : Fractionner un texte.
- istitle :  Sélectionner les mots en majuscules.
- startswith :  Sélectionner les mots commençant par une lettre à votre choix.
- endswith :  Sélectionner les mots terminant par une lettre à votre choix.
- lower : Convertir le texte en minuscule.
- isupper : Vérifier si le mot est en majuscule.
- islower : Vérifier si le mot est en minuscule.
- isdigit: Vérifier si le mot est composé de chiffres.
- strip : Supprimer les espaces, les tabulations et les lettres.
- find : Trouver une position d'une lettre particulière (sens direct).
- rfind : Trouver une position d'une lettre particulière (sens inverse).
- replace : Remplacer une lettre par une autre
- list : Trouver chaque lettre et la stocher dans une liste.
- split & strip : nous utilisons les deux fonctions pour nettoyer un texte.

## Natural Language Process (NLP)

Le NLP est un domaine à l’intersection du Machine Learning et de la linguistique. Il a pour but d’extraire des informations et une signification d’un contenu textuel.

Le Traitement Automatique du Langage naturel trouve de nombreuses applications :

- traduction de texte
- correcteur orthographique
- résumé automatique d’un contenu
- synthèse vocale
- classification de texte
- analyse d’opinion/sentiment


## Normalisation du texte

La normalisation du texte  est utilisée pour fractionner le texte et rendre les mots en minuscule


## Les méthodes de vectorisation

### Racinisation (Stemming)

La racinisation est une méthode qui permet d'extraire la racine du mot.

### Lemmatisation

La lemmatisation  est une racinisation qui permet de transformer les mots dans une forme neutre.

### Distance de Levenshtein

La distance de Levenshtein est métrique permet d’estimer la similarité de deux valeurs d’une chaîne de caractères (mot, forme de mot, composition de mots), en comparant le nombre minimum d’opérations pour convertir une valeur en une autre.
Cette technique est souvent utilisée dans la correction automatique de l’orthographe ou la quantification de séquences ADN similaires exprimées en lettres.

### Simmilarité cosinus

- Bag of words : La technique BOW consiste à attribuer à chaque mot un index entier unique pour construire un dictionnaire de mots et à compter le nombre d’occurrences de chaque mot et faire correspondre cette valeur à l’index correspondant.

- Algorithmes TF-IDF :
  TF : calcule le nombre d’occurrences d’un terme en comparaison avec le nombre total de mots dans un texte. Comme nous avons vu auparavnt dans la section Basic Methods, plus précisement l'exemple de kaggale.
  IDF : mesure l’importance d’un terme dans un texte ou une collection de texte.
  Il est calculé comme un logarithme du nombre de documents divisé par le nombre de documents contenant ce terme.


## Tokenisation

La tokenisation du texte est une technique visant à diviser le texte en unités plus petites, généralement des mots. On peut réaliser la tokenisation à l'aide de fonctions telles que "split" en Python ou en utilisant des outils comme "nlp.word_tokenize()".

## Text Classification

Plusieurs modèles de machine learning sont couramment utilisés, tels que les SVM (Support Vector Machines), les classificateurs bayésiens naïfs, les réseaux de neurones récurrents (RNN) et XGBoost.

## LDA (Latent Dirichlet Allocation) : A nalyse des sujets des textes

LDA est un modèle probabiliste qui attribue des sujets à des documents et des mots à des sujets, permettant ainsi d'identifier les thèmes sous-jacents dans un ensemble de documents.

## Régression des textes

L'utilisation de modèles de régression pour prédire une variable continue basée sur des données textuelles.
