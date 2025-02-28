# EducInfo 
Ancinnement : Espace d'information pour le Lycée Couffignal à Strasbourg

<h4>⚠️ Ce projet est en cours de reprise. Il peut avoir des dysfonctionnements dans ses premières versions

## Quel est le but de ce projet ?
Proposer une solution pour afficher des informations comme les absences, le menu de cantine, etc ... aux élèves facilement

## Fonctionnalités

- **Absences** : Affichage hebdomadaire des absences, géré via un tableau de bord admin.
- **Widgets dynamiques** :
  - Météo
  - Menu Cantine
  - Événements à venir
- **Interface Admin Sécurisée** :
  - Authentification via Flask-Login (sessions)
  - Formulaires WTForms pour gérer absences, config widgets, et événements
- **Design Moderne** : Intégration de Tailwind via un CDN pour un style épuré.

## Installation

1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/Doalou/EducInfo.git
   cd EducInfo

2. **Installer les dépendances** :

    pip install -r requirements.txt

3. **Initialiser la base de données** :

    Lors du premier lancement, l’appli créera le fichier educinfo.db et un utilisateur admin par défaut (admin@educinfo.com / admin123).
    Vous pouvez modifier ce comportement dans app.py (fonction create_tables).

4. **Lancer l'application** :

    python app.py
