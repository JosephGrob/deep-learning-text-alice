# Deep Learning pour l'Analyse de Texte – Alice in Wonderland

> **Cours** : Machine Learning (Lettres) – UNIL  
> **Auteur** : Joseph Grob  
> **Professeur** : Guillaume Guex  
> **Rendu 2** – Automne 2024

---

## Description du Projet

Ce projet explore des techniques de **traitement du langage naturel (NLP)** et de **deep learning** appliquées au texte complet d’_Alice's Adventures in Wonderland_ (Lewis Carroll, 1865).

Le fichier texte a été pré-traité (suppression des paratextes) avant d’être découpé, analysé, et modélisé à l’aide de réseaux de neurones.

---

## Objectifs pédagogiques

- Appliquer un pipeline complet de **prétraitement de texte** (segmentation, lemmatisation, nettoyage)
- Créer des représentations vectorielles (TF-IDF, Word2Vec)
- Réduire la dimensionnalité (t-SNE, analyse factorielle)
- Entraîner un modèle **LSTM** pour générer du texte
- Utiliser un modèle **BERT** fine-tuné pour l’analyse de sentiment

---

## Code fourni

Le fichier principal est : RENDU2_ML_LETTRES.ipynb


*(Renommé depuis `RENDU2_ML_LETTRES(1)_(2)(2)(1)` pour simplifier)*

Le code couvre :
- Extraction des chapitres du `.txt`
- Prétraitement linguistique (via spaCy)
- Statistiques textuelles (lemmes, POS, entités)
- Visualisation 2D des embeddings
- LDA et génération de texte avec LSTM
- Analyse de sentiment avec modèle BERT pré-entraîné

---

## Données utilisées

- Livre complet : **Alice's Adventures in Wonderland**  
  🔗 [https://www.gutenberg.org/ebooks/11](https://www.gutenberg.org/ebooks/11)

- Modèle BERT pré-entraîné (fourni via Moodle par le professeur)  
  🔗 [Lien Google Drive TP12 – sur Moodle]

---

## Librairies nécessaires

Tu peux installer les dépendances via :


pip install -r requirements.txt

Ou à la main :

pandas, numpy, matplotlib, seaborn

scikit-learn, spacy, gensim, tqdm

torch, transformers

## Remarques

Le projet a été exécuté uniquement en mode CPU.

Il est nécessaire de télécharger le modèle BERT depuis le lien Moodle pour exécuter la partie sentiment analysis.

## Contact

Pour toute question :

✉️ grob.j1890@gmail.com
