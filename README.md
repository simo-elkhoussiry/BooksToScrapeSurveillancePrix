# BooksToScrapeSurveillancePrix

Ce projet représente une version bêta d'un système de surveillance des prix pour le site Books to Scrape. Il utilise un scraper Python pour extraire les informations tarifaires du site et stocke les données localement.

## Récupération du Projet depuis GitHub

Pour récupérer le projet sur votre machine, suivez ces étapes :

1. **Cloner le Répertoire :**
   - Ouvrez un terminal dans le répertoire où vous souhaitez cloner le projet.
   - Utilisez la commande suivante pour cloner le répertoire sur votre machine :
     
     "" git clone https://github.com/simo-elkhoussiry/BooksToScrapeSurveillancePrix.git ""
     
   
2. **Accéder au Répertoire :**
   - Utilisez la commande suivante pour accéder au répertoire cloné :
     
     "" cd BooksToScrapeSurveillancePrix ""
     

## Configuration de l'Environnement Virtuel

Il est fortement recommandé d'utiliser un environnement virtuel pour exécuter ce projet et isoler ses dépendances.

### Étapes pour créer et activer l'environnement virtuel :

""
# Créer un environnement virtuel
python3 -m venv venv

# Activer l'environnement virtuel
source venv/bin/activate  # Sur Linux/Mac
venv\Scripts\activate    # Sur Windows 
                                            ""

Installation des Dépendances

Avant d'exécuter le projet, installez les dépendances nécessaires à l'aide de la commande suivante :

"" pip install -r requirements.txt ""

Exécution du Projet

Maintenant que l'environnement virtuel est activé et les dépendances sont installées, vous pouvez exécuter le projet avec la commande suivante :

"" python Scraper_books.py ""

N'oubliez pas de désactiver l'environnement virtuel après avoir terminé en utilisant la commande :

"" deactivate ""
Structure du Projet

Scraper_books.py : Le script principal pour extraire les informations tarifaires.

requirements.txt : La liste des dépendances du projet.

Remarques Importantes

Assurez-vous que l'environnement virtuel est activé avant d'exécuter le projet.
Les données extraites seront stockées localement dans le dossier data.

Contribuer

Toute contribution est la bienvenue ! Si vous avez des suggestions d'amélioration, des rapports de bogues, ou si vous souhaitez ajouter des fonctionnalités, veuillez ouvrir une issue ou une pull request.

Merci de contribuer à rendre ce projet encore meilleur !