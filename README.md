# Shiny-Chronocapture
Application Shiny destinée aux analyses automatisées des données de Chronocapture. Développé par Flavia APE. 

Mots clé : Analyses, protocoles Chronocaptures, Shiny, GeoNature, écologie, lépidoptères. 


Usage
-----

Cette application Shiny (R) a pour objectif d'analyser de manière automatisée les données issues des protocoles "Chronocapture". Elle repose sur les formats de données exportés par les modules "Chronocapture" de GeoNature partagés par Flavia APE. 

Les Chronocaptures
------------------

Le "Chronocapture" est une méthodologie qui repose sur la capture au filet et le dénombrement d'individus de papillons diurnes sans remise des individus dans le milieu pendant la durée du relevé. Cette méthode permet de capturer, dénombrer précisément et déterminer de manière fiable (en main) les individus observés pendant une durée standardisée. Cette durée - dépendante du milieu considéré et de sa diversité - est déterminée lors d'une phase de calage rigoureusement décrite.

Cette méthodologie permet d'évaluer finement la structure du cortège d'espèces sur un ou des sites en suivant un plan d'échantillonnage prédéfini, en analysant notamment la diversité d'espèces et les abondances relatives des différentes espèces constituant le cortège. 

Plusieurs protocoles - nécessitant chacun différents paramètres et s'appuyant chacun sur un ensemble d'analyses pré-établies - sont déclinés à partir de cette méthodologie d'acquisition des données sur le terrain. 

- Protocole 1 : Chronocapture de calage permettant de définir la durée de relevés à effectuer sur un site ou réseau de sites ciblés. À défaut, indiquer des durées conseillées. 
- Protocole 2 : Chronocapture permettant le suivi dans le temps d'un même site constitué de plusieurs points d'échantillonnages
- Protocole 3 : Chronocapture permettant de comparer entre eux deux sites d'un même milieu (évaluation des effets de gestion par exemple)



Installation
------------

Le code source de l'application est disponible dans ce dépôt. Il se compose essentiellement de deux fichiers : 

- ui.R : code de l'interface utilisateur
- server.R : code des fonctions et calculs opérés sur les données

Ce code peut être déployé sur Shinyapps.io en se reportant à la documentation officielle. 


Utilisation
-----------

- Déployer l'application
- Ouvrir l'onglet correspondant à sa déclinaison du protocole
- Déposer le fichier d'export au format "Analyse" généré par le module de saisie de GeoNature
