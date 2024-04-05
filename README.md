# Mission-Realisez-un-traitement-dans-un-environnement-Big-Data-sur-le-Cloud
Certification OpenClassrooms - Parcours data scientist - Mission n°9- Realisez un traitement dans un environnement Big Data sur le Cloud


## Mission 
Je suis Data Scientist dans une très jeune start-up de l'AgriTech, nommée "Fruits!", qui cherche à proposer des solutions innovantes pour la récolte des fruits.
La volonté de l’entreprise est de préserver la biodiversité des fruits en permettant des traitements spécifiques pour chaque espèce de fruits en développant des robots cueilleurs intelligents.
Le start-up souhaite dans un premier temps se faire connaître en mettant à disposition du grand public une application mobile qui permettrait aux utilisateurs de prendre en photo un fruit et d'obtenir des informations sur ce fruit.
Pour la start-up, cette application permettrait de sensibiliser le grand public à la biodiversité des fruits et de mettre en place une première version du moteur de classification des images de fruits.
De plus, le développement de l’application mobile permettra de construire une première version de l'architecture Big Data nécessaire.
## Source :
[Les données](https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/Data_Scientist_P8/fruits.zip)

## Axes d'orientations: 
- Tenir compte dans les développements du fait que le volume de données va augmenter très rapidement après la livraison de ce projet.
- Développer des scripts en Pyspark et à utiliser le cloud AWS pour profiter d’une architecture Big Data (EMR, S3, IAM et possibilité de transférer les traitements dans un environnement Databricks)
- Faire une démonstration de la mise en place d’une instance EMR opérationnelle, ainsi qu’ expliquer pas à pas le script PySpark:  
  - Traitement de diffusion des poids du modèle Tensorflow sur les clusters (broadcast des “weights” du modèle).
  - S'appuyer sur l’article “Distributed model inference using TensorFlow Keras” disponible sur le web.
  - Effectuer une réduction de dimension de type PCA en PySpark 
- Respecterez les contraintes du RGPD : dans notre contexte, je dois veiller à paramétrer l'installation afin d’utiliser des serveurs situés sur le territoire européen 
- La mise en œuvre d’une architecture Big Data de type EMR engendrera des coûts. Veiller donc à ne maintenir l’instance EMR opérationnelle que pour les tests et les démos.

## Compétences 
- Utiliser les outils du cloud pour manipuler des données dans un environnement Big Data.
- Identifier les outils du cloud permettant de mettre en place un environnement Big Data (EMR, IAM, S3 ...)
- Paralléliser des opérations de calcul avec Pyspark.
- Mettre en place le cluster EMR pour distribuer les calculs dans le cloud et connectez un notebook Cloud pour réaliser la chaîne de traitement jusqu’à la réduction de dimensions.
