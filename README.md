# Workshop-Migration
## Objectif:
L'objectif de ce Lab , c'est d'effectuer un assessment à partir d'un fichier CSV importé<br>
Documentations: https://learn.microsoft.com/fr-fr/azure/migrate/migrate-services-overview
## Pré-requis
Avoir un abonnement Azure avec un utilisateur ayant les droits Contributeur ou Propriétaire dans l’abonnement pour créer un projet.
## Etapes du Lab
- Import du fichier CSV
- Création d'un groupe d'une application
- Création d'un assessment
- Modification de l'assessment avec de nouveaux critères
- Export de l'assessment dans un fichier Excel
### Création d'un projet
Il y deux possibilités pour créer un projet<br>
- l'abonnement n'a pas de projet de migration existant
- l'abonnement a déjà un ou des projets de migration(s)

-> l'abonnement n'a pas de projet de migration existant (option1)<br><br>
<img width='800' src='./images/assessment/image_00.png'/><br>
<img width='800' src='./images/assessment/image_01.png'/><br>
<img width='800' src='./images/assessment/image_02.png'/><br>
<img width='800' src='./images/assessment/image_03.png'/><br>
<img width='800' src='./images/assessment/image_04.png'/><br>
-> l'abonnement a déjà un ou des projets de migration(s) (option2)<br><br>
<img width='800' src='./images/assessment/image_00.png'/><br>
<img width='800' src='./images/assessment/image_01.png'/><br>
<img width='800' src='./images/assessment/image_05.png'/><br>
<img width='800' src='./images/assessment/image_06.png'/><br>
<img width='800' src='./images/assessment/image_07.png'/><br><br>
Pour naviguer entre projets<br>
<img width='800' src='./images/assessment/image_08.png'/><br><br>

### Découverte avec l'import d'un fichier CSV.
Récupérez le fichier CSV:<br>
https://storworkshops.blob.core.windows.net/workshopmigrate/Azure_Migrate_import_template.csv<br>
Dans votre projet:<br>
<img width='800' src='./images/assessment/image_09.png'/><br>
<img width='800' src='./images/assessment/image_10.png'/><br>
<img width='800' src='./images/assessment/image_11.png'/><br>
<img width='800' src='./images/assessment/image_12.png'/><br>
<img width='800' src='./images/assessment/image_13.png'/><br><br>

### Création d'un groupe.
Un assessment se fait uniquement depuis un groupe<br>
Revenir à la racime du projet<br>
<img width='800' src='./images/assessment/image_14.png'/><br>
<img width='800' src='./images/assessment/image_15.png'/><br>
<img width='800' src='./images/assessment/image_16.png'/><br>
<img width='800' src='./images/assessment/image_17.png'/><br>
<img width='800' src='./images/assessment/image_18.png'/><br>
<img width='800' src='./images/assessment/image_19.png'/><br>
<img width='800' src='./images/assessment/image_20.png'/><br>
<img width='800' src='./images/assessment/image_21.png'/><br>
<img width='800' src='./images/assessment/image_22.png'/><br><br>

### Création d'un assessment.
<img width='800' src='./images/assessment/image_23.png'/><br>
<img width='800' src='./images/assessment/image_24.png'/><br>
<img width='800' src='./images/assessment/image_25_0.png'/><br>
<img width='800' src='./images/assessment/image_26.png'/><br>
<img width='800' src='./images/assessment/image_27.png'/><br>
<img width='800' src='./images/assessment/image_28.png'/><br>
<img width='800' src='./images/assessment/image_29.png'/><br>
<img width='800' src='./images/assessment/image_30.png'/><br>
<img width='800' src='./images/assessment/image_31.png'/><br>
<img width='800' src='./images/assessment/image_32.png'/><br>
<img width='800' src='./images/assessment/image_33.png'/><br>
<img width='800' src='./images/assessment/image_34.png'/><br>
<img width='800' src='./images/assessment/image_35_0.png'/><br>
<img width='800' src='./images/assessment/image_36.png'/><br>
<img width='800' src='./images/assessment/image_37.png'/><br><br>

### Modification et reconfiguration de l'assessment
<img width='800' src='./images/assessment/image_38.png'/><br>
<img width='800' src='./images/assessment/image_39.png'/><br>
<img width='800' src='./images/assessment/image_40.png'/><br>
<img width='800' src='./images/assessment/image_41.png'/><br><br>

### Exportation de l'assessment
<img width='800' src='./images/assessment/image_42.png'/><br>
<img width='800' src='./images/assessment/image_43.png'/><br>
<img width='800' src='./images/assessment/image_44.png'/><br>