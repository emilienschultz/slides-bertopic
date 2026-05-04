# slides-bertopic

1. Prise de contact (10 min)
    - est ce que les gens connaissent python?
    - expérience avec des données textuelles
    - expérience avec le machine learning? 
    - Experience avec le NLP 
    - experience avec le topic model
2. Intro topic model (30 min)
    - Histoire
    - outils
    - applications dans la recherche
    - Rupture: arriver des modèles de langue -> Mise à jour des outils 
    - BERTopic:
        - un papier
        - un dépot 
        - une documentation
        - des outils de formation
3. Moment pratico-pratique (15 min):
    - Organisation de l'espace de travail (onyxia, google colab, local)
    - installation des requirements
    - Présentation du jeu de données
    - Mentionner que le jeu de données a été retravaillé etc et justifier rapidement
4. Lancer la config Vanilla (15-30 min):
    - Lancer la config out of the box sur 1000 éléments
    - présenter les résultats (tableau + graphe 2D + top keywords + hiérarchique)
    - présenter la fusion de thèmes
    - Identifier les problèmes
5. Reprendre la trame de BERTopic et ajuster les paramètres uns à uns (total ~1h)
    - Les données d'entrée (5 min)-> pas tout expliquer mais simplement le mentionner
    - modèle de plongement (30 min)
        - Faire un point modèle de plongement
        - Faire un tour sur huggingface 
        - mentionner les problèmes de temps etc
        - Passer à la version avec embeddings pré-entraînés
    - UMAP
    - HDBSCAN
    - CountVectorizer
    - cTFIDF
    - commencer à mentionner 
6. Reproductibilité (15 min)
    - Mentionner la seed
    - mentionner l'enregistrement du modèle
    - revenir sur l'enregistrement des embeddings
7. Conclusion et ouverture (20 min)
    - Résumé étapes clefs 
    - Ouverture sur l'évaluation des modèles
    - Dire que la bibliothèque propose plus de choses encore
    - Dans quel cadre est ce que c'est interessant ?
    - Ouverture vers le tuto anglais

Total à la louche: 3h