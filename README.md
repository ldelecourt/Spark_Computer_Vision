# Spark_Computer_Vision

Projet de computer vision couplant calcul distribué avec Spark et deep learning, le tout en streaming.

### Le solution développée est découpé en deux parties distinctes représentant 2 streams (2 notebooks).
- Le 1er notebook va récupérer les photos à traiter en temps réel, localiser les visages à l'aide du modèle Haarcascade et les extraire dans un dossier intermédiaire.
- Le 2nd notebook prend la suite du traitement. Il récupère les visages extrait, détecte si ces derniers portent un masque ou pas à l'aide du modèle VGG19 fine-tuné. Enfin, il dessine les labels associés avec un rectangle (vert ou rouge) autour des visages sur les photos d'origines.

![alt text](https://github.com/ldelecourt/Spark_Computer_Vision/blob/main/image.png?raw=true)
