# 🌤️ Weather App

Une application météorologique moderne qui fournit des informations en temps réel sur le climat d'une ville donnée.

![Weather App Interface](images/search.png)

## 🚀 Fonctionnalités

- **Recherche par ville** : Obtenez la météo de n'importe quelle ville dans le monde.
- **Recherche rapide** : Appuyez sur la touche `Entrée` pour lancer la recherche.
- **Informations détaillées** :
  - Température actuelle (en °C).
  - Taux d'humidité.
  - Vitesse du vent.
- **Icônes Dynamiques** : L'icône météo change automatiquement en fonction des conditions :
  - ☀️ Clair
  - ☁️ Nuageux
  - 🌧️ Pluie
  - 🌦️ Bruine
  - 🌫️ Brume
- **Gestion d'erreurs** : Affiche un message "Ville invalide" si la ville recherchée n'est pas trouvée.

## 🛠️ Technologies utilisées

- **HTML5 / CSS3** : Interface utilisateur et design responsive.
- **JavaScript (Async/Await)** : Gestion des appels API asynchrones.
- **OpenWeatherMap API** : Source des données météorologiques.

## 📦 Installation

1. Clonez le dépôt ou téléchargez les fichiers.
2. Ouvrez le fichier `index.html` dans votre navigateur.

## ⚙️ Configuration technique

L'application utilise l'API `fetch` pour interroger l'endpoint d'OpenWeatherMap :
`https://api.openweathermap.org/data/2.5/weather?units=metric&q={city}&appid={apiKey}`

La logique JavaScript traite la réponse JSON pour mettre à jour dynamiquement le DOM avec les données reçues.

## 🖼️ Aperçu des icônes météo

| Condition | Icône |
|-----------|-------|
| Clair | ![Clair](images/clear.png) |
| Nuageux | ![Nuageux](images/clouds.png) |
| Pluie | ![Pluie](images/rain.png) |
| Bruine | ![Bruine](images/drizzle.png) |
| Brume | ![Brume](images/mist.png) |
| Humidité | ![Humidité](images/humidity.png) |
| Vent | ![Vent](images/wind.png) |
