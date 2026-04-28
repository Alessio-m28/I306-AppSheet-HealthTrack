docs/modele-donnees.md
# Modèle de données

## Consigne
Vous devez définir VOUS-MEMES la structure des données.

## Tables

### Sport
| Colonne | Type | Description |
|------------------|------------|-------------|
|   _RowNumber     |   Number   |             |
|--------------|----------|-------------|
|    Row ID    |   Text   |             |
|-------------|----------|-------------|
|    Title    |   Text   |             |
|------------|----------|-------------|
|    Date    |   Date   |             |
|-----------------|----------|-------------|
|    TypeSport    |   Enum   |             |
|-----------------|------------|-------------|
|    Intensite    |   Number   |             |
|--------------------|--------------|-------------|
|    tempActivite    |   Duration   |             |

### Journal bien être
| Colonne | Type | Description |
|------------------|------------|-------------|
|   _RowNumber     |   Number   |             |
|--------------|----------|-------------|
|    Row ID    |   Text   |             |
|-------------|----------|-------------|
|    Title    |   Text   |             |
|-------------------|----------|-------------|
|    Commentaire    |   Text   |             |
|---------------------|------------|-------------|
|    Heure_Sommeil    |   Number   |             |
|-----------------------|------------|-------------|
|    Nb_Verres_d_eau    |   Number   |             |
|--------------|------------|-------------|
|    Humeure    |   Number   |             |
|------------|----------|-------------|
|     Date   |   Date   |             |

## Questions à vous poser
- Quelles données sont nécessaires ? Tout
- Quelles contraintes doivent être respectées ? Humeur et intensité c'est de 1 à 5, Heure de sommeil min0 max24, Nb_Verres_d_eau pas de limite. 
- Comment éviter les erreurs de saisie ? -> on fait attention a comment on tape sur le clavier.


| Colonne         | Type   | Description                             |
| --------------- | ------ | --------------------------------------- |
| _RowNumber      | Number |                                         |
| Row ID          | Text   | Identifiant unique de l’entrée          |
| Title           | Text   | Titre de l’entrée                       |
| ContenueRepas   | Text   | 					     |
| MomentRepas     |EnumList|         				     |
| Catégorie       |EnumList|     				     |
| Commentaire     | text   |  					     |
| Date            | Date   |                       		     |
