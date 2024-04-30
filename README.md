
# OuiOuiSNCF

OuiOuiSNCF est une application de réservation de billets de train développée avec Python et Flask. Elle permet aux utilisateurs de rechercher des trajets, consulter les horaires des trains, et réserver des billets en ligne.

## Fonctionnalités

- Recherche de trajets en spécifiant la gare de départ et d'arrivée, ainsi que la date de voyage.
- Affichage des horaires des trains disponibles pour le trajet spécifié.
- Réservation de billets en ligne en spécifiant le nombre de passagers et les informations de paiement.
- Génération de billets électroniques avec un code QR pour accès facile lors du voyage.

## Installation

1. Clonez ce dépôt sur votre machine locale en utilisant la commande suivante :

   ```
   git clone https://github.com/Paul-FranckDencausse/OuiOuiSNCF.git
   ```

2. Accédez au répertoire du projet :

   ```
   cd OuiOuiSNCF
   ```

3. Créez un environnement virtuel Python :

   ```
   python -m venv venv
   ```

4. Activez l'environnement virtuel :

   - Sur Windows :

     ```
     venv\Scripts\activate
     ```

   - Sur macOS et Linux :

     ```
     source venv/bin/activate
     ```

5. Installez les dépendances Python requises :

   ```
   pip install -r requirements.txt
   ```

## Utilisation

1. Lancez l'application en exécutant le fichier `app.py` :

   ```
   python app.py
   ```

2. Accédez à l'application dans votre navigateur web en ouvrant l'URL suivante :

   ```
   http://localhost:5000
   ```

3. Utilisez l'interface de l'application pour rechercher des trajets, consulter les horaires des trains et réserver des billets en ligne.

## Contribution

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue pour signaler des bogues ou à proposer des améliorations. Si vous souhaitez contribuer au code, veuillez suivre les bonnes pratiques de développement et ouvrir une pull request avec vos modifications.

## Licence

Ce projet est sous licence MIT. Pour plus d'informations, consultez le fichier [LICENSE](LICENSE).

---

N'oubliez pas de personnaliser ce README en fonction des spécificités de votre application et de fournir toutes les informations nécessaires pour que les utilisateurs puissent l'utiliser et le comprendre facilement.
