# Projet_de_Fin_D-Etude


## Résumé du projet



Ce projet vise à lutter contre la circulation de produits contrefaits, en proposant une application mobile et web permettant aux utilisateurs de vérifier l’authenticité et la traçabilité des médicaments grâce à des QR codes sécurisés. e.

L’application repose sur une interface web développée avec Flutter et une API backend Django connectée à une base de données PostgreSQL.
Le système détecte efficacement les anomalies (scans suspects, doublons de QR code, transferts non validés) et permet le signalement d’alertes. Cette solution renforce la confiance dans la chaîne pharmaceutique et constitue un outil concret de lutte contre la contrefaçon.

## Installation

 **Prérequis**  
   - [Flutter](https://flutter.dev/docs/get-started/install) (pour l’interface mobile/web)
   - [Python 3.13.3](https://www.python.org/downloads/) et [Django](https://www.djangoproject.com/)
   - [PostgreSQL 15](https://www.postgresql.org/download/)


 **Configuration**
   Renseigner les paramètres de connexion à la base de données dans le backend.
Adapter l’URL de l’API dans la configuration Flutter.
  


## Fonctionnalités principales
- Génération et gestion de QR codes uniques pour chaque unité de médicament
- Suivi complet du médicament à chaque étape de la chaîne
- Interface web et mobile conviviale (Flutter)
- Détection automatique des anomalies (scans, doublons, transferts)
- Signalement d’alertes et traçabilité renforcée



   
Pour toute question ou suggestion, contactez l’équipe.

## Licence
Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.



