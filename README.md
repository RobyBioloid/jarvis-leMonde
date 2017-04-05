## Dependance
- python 3
- module lxml
- module Requests

## Description
Permet de r�cup�rer les actualit�s du site 'Le Monde.fr' et de les faire dire par Jarvis

Il y a deux modes de lecture des actualit�s
 -1) Mode g�n�ral
La lecture se fera en fonction des rubriques qui ont �t� activ�es dans le fichier config.sh

 -2) Mode rubrique
Seul la rubrique demand� sera lu par Jarvis


Le fichier config.sh permet �gamelement de configurer Jarvis afin qu'il lise les description ou non des actualit�
(Le fait de lire les descriptif peut �tre assez lourd et long)

## Usage
```
You: Quels sont les actualit�s du jour ?
Jarvis: Les actualit�s pour aujourd'hui sont :
Jarvis: Rubrique sciences
Jarvis: Jarvis, l'assistant vocal open source qu'il vous faut pour votre domotique
Jarvis:
Jarvis: Rubrique politique
Jarvis: on nous aurait menti!
You: Donne moi la liste des rubriques
Jarvis: il y a 12 rubriques : internationale, etc ...
You: quels sont les actualit� de la rubrique science
Jarvis: Les actualit�s de la rubrique science sont :
Jarvis: ********

```

## Author
[RobyBioloid](https://github.com/RobyBioloid/jarvis-leMonde)
