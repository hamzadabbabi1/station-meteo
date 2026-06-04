# 🌦️ Station Météo IoT - Temps Réel

Une application web moderne pour afficher les données météorologiques en temps réel avec une interface élégante et réactive.

## 📋 Description

**Station Météo IoT** est un projet de station météorologique connectée qui affiche:
- **Température** actuelle et historique
- **Humidité** en temps réel
- **Vitesse du vent**
- **Pression atmosphérique**
- **Qualité de l'air (AQI)**
- **Graphiques historiques** avec Chart.js

Les données sont synchronisées en temps réel via Firebase Realtime Database.

## 🎨 Caractéristiques

✅ Interface moderne avec design glassmorphism  
✅ Responsive design (mobile, tablet, desktop)  
✅ Animations fluides et blobs de fond  
✅ Graphiques interactifs avec Chart.js  
✅ Intégration Firebase pour les données temps réel  
✅ Affichage de plusieurs capteurs simultanément  
✅ Sombre et clair (prêt pour l'implémentation)  

## 🛠️ Technologies Utilisées

- **HTML5** - Structure
- **CSS3** - Styling (Glassmorphism, Animations)
- **JavaScript** - Interactivité
- **Chart.js** - Graphiques
- **Firebase Realtime Database** - Base de données temps réel

## 📦 Installation

```bash
# Cloner le repository
git clone https://github.com/hamzadabbabi1/station-meteo.git

# Accéder au dossier
cd station-meteo

# Ouvrir dans un navigateur
# Ouvrir simplement le fichier index.html ou utiliser un serveur local
```

### Serveur Local (Optional)

```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js (http-server)
npm install -g http-server
http-server
```

Puis accédez à `http://localhost:8000`

## ⚙️ Configuration Firebase

1. Créer un projet Firebase sur [firebase.google.com](https://firebase.google.com)
2. Créer une Realtime Database
3. Ajouter les données de configuration Firebase dans `index.html`
4. Configurer les règles de sécurité Firebase pour votre base de données

## 📁 Structure du Projet

```
station-meteo/
│
├── index.html          # Fichier principal
├── README.md           # Documentation
└── LICENSE             # Licence MIT
```

## 📊 Format des Données Firebase

```json
{
  "sensors": {
    "temperature": 22.5,
    "humidity": 65,
    "wind_speed": 12.3,
    "pressure": 1013.25,
    "aqi": 45,
    "timestamp": 1685894400000
  }
}
```

## 🤝 Contribution

Les contributions sont les bienvenues! Pour contribuer:

1. Fork le projet
2. Créer une branche (`git checkout -b feature/AmazingFeature`)
3. Commit les changements (`git commit -m 'Add AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

## 📄 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 👨‍💻 Auteur

**Hamza Dabbabi**  
GitHub: [@hamzadabbabi1](https://github.com/hamzadabbabi1)

## 📞 Support

Pour les questions ou problèmes, veuillez ouvrir une [Issue](https://github.com/hamzadabbabi1/station-meteo/issues) sur GitHub.

## 🔐 Sécurité

**Important:** Ne mettez jamais vos clés Firebase ou credentials sensibles directement dans le code source. Utilisez des variables d'environnement ou des fichiers de configuration sécurisés.

## 🎯 Roadmap Futures

- [ ] Mode sombre/clair
- [ ] Alertes météorologiques
- [ ] Export des données en CSV/JSON
- [ ] Dashboard avec plusieurs stations
- [ ] API REST personnalisée
- [ ] Support mobile PWA

---

**Profitez de votre station météo!** 🌡️⛅
