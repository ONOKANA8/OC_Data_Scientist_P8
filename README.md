![logo-fruits](https://github.com/ONOKANA8/OC_Data_Scientist_P8/blob/main/logo-fruits.png?raw=true)

# **OC_Data_Scientist_P8 - Projet 8 : Déploiement d'un modèle dans le cloud**

## Contexte

Une start-up de l'AgriTech, nommée **"Fruits!"** cherche à proposer des solutions innovantes pour la récolte des fruits.
La volonté de l’entreprise est de préserver la biodiversité des fruits en permettant des traitements spécifiques pour chaque espèce de fruits en développant des robots cueilleurs intelligents.

La jeune start-up souhaite dans un premier temps se faire connaître en mettant à disposition du grand public une application mobile qui permettrait aux utilisateurs de prendre en photo un fruit et d'obtenir des informations sur ce fruit.

Pour elle, cette application permettrait de sensibiliser le grand public à la biodiversité des fruits et de mettre en place une première version du moteur de classification des images de fruits.

De plus, le développement de l’application mobile permettra de construire une première version de l'architecture Big Data nécessaire.


## Mission
* Développer dans un environnement Big Data une première chaîne de traitement des données
  * Preprocessing
  * Etape de réduction de dimension


## Sources de données
|Sources|Liens sources|
|--|--|
|Données Kaggle|https://www.kaggle.com/moltean/fruits|


## Livrables
|Noms de fichiers et de dossier|Descriptions|
|--|--|
|Konan_Koffi_2_images_82022|Dossier contenant les sous-dossiers *Training_1* et *sortie_de_reduction_de_dimension_dimage_via_pca.parquet* renfermant respectivement des images stockées dans un bucket d'aws S3 et de features de ces images stockées dans un autre bucket d'aws S3. Pour obtenir ce dossier il faudra télécharger le dossier au format ".zip" *P8_Déployez_un_modèle_dans_le_cloud_Konan_Koffi.zip* et l'extraire ensuite.|
|Konan_Koffi_1_notebook_82022.ipynb|Notebook du travail de parallélisation de calculs réalisé avec SPARK via Pyspark dans le cloud|
|Konan_Koffi_3_presentation_082022.pdf|Support de présentation|

NB : Les livrables ***Konan_Koffi_1_notebook_82022.ipynb*** et ***Konan_Koffi_3_presentation_082022.pdf*** sont directement disponible dans le dossier nommé **P8_Déployez_un_modèle_dans_le_cloud_Konan_Koffi**