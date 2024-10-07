# Marketplace e-commerce

L'entreprise "Place de marché” souhaite lancer une marketplace e-commerce.
Sur la place de marché, des vendeurs proposent des articles à des acheteurs en postant une photo et une description.

Pour l'instant, l'attribution de la catégorie d'un article est effectuée manuellement par les vendeurs, et est donc peu fiable. De plus, le volume des articles est pour l’instant très petit.

Pour rendre l’expérience utilisateur des vendeurs (faciliter la mise en ligne de nouveaux articles) et des acheteurs (faciliter la recherche de produits) la plus fluide possible, et dans l'optique d'un passage à l'échelle, il devient nécessaire d'automatiser cette tâche.

Dans le projet, il est necessaire d'étudier la faisabilité d'un moteur de classification des articles en différentes catégories, avec un niveau de précision suffisant.

### Objectifs:
* Afin d’extraire les features texte, il sera nécessaire de mettre en œuvre :
  * deux approches de type “bag-of-words”, comptage simple de mots et Tf-idf ;
  * une approche de type word/sentence embedding classique avec Word2Vec (ou Glove ou FastText) ;
  * une approche de type word/sentence embedding avec BERT ;
  * une approche de type word/sentence embedding avec USE (Universal Sentence Encoder).
* Afin d’extraire les features image, il sera nécessaire de mettre en œuvre :
  * un algorithme de type SIFT;
  * un algorithme de type CNN Transfer Learning.
 



