Partie 1 — Préparation de l’environnement:

.Quelle est la commande permettant d’installer une bibliothèque avec pip ?

    pip install nom_de_la_bibliothèque 
    !pip install nom_de_la_bibliothèque

    
.Quelle est la différence entre nltk et spaCy selon vous ?: NLTK est une bibliothèque principalement utilisée pour l'apprentissage et le traitement de texte avec de nombreux outils. spaCy est une bibliothèque plus moderne et rapide, adaptée aux applications de traitement automatique du langage naturel.

Partie 2 — Nettoyage du texte:

.Pourquoi est-il important de mettre le texte en minuscules ?: Pour considérer les mêmes mots écrits avec des majuscules ou des minuscules comme un seul et même mot.

.Donnez un exemple de résultat avant et après nettoyage: 

  Avant : Bonjour ! J'aime beaucoup le NLP...
  Après : bonjour jaime beaucoup le nlp

  Partie 3 — Tokenisation et Stopwords:

  .Que représentent les stopwords ?: Les stopwords sont des mots très fréquents qui apportent généralement peu d'information pour l'analyse.
  
  .Quelle proportion du texte original est supprimée après leur retrait ?
  
    proportion = (len(tokens) - len(tokens_filtrés)) / len(tokens) * 100
    print(proportion, "%")

Partie 4 — Lemmatisation:

.Quelle est la différence entre stemming et lemmatisation ?: e stemming coupe les mots pour obtenir une racine, tandis que la lemmatisation utilise l'analyse linguistique pour obtenir la forme de base correcte du mot.


.Pourquoi cette étape est-elle importante avant l’analyse sémantique ?: Elle permet de regrouper les différentes formes d'un même mot et de réduire la complexité du texte, ce qui facilite son analyse.
