
### ⚡S1 27.10 - 18.11

- Squelette de l’architecture globale & navigation
    
    Structure de navigation entre les différents modules de l'application,
    différentes pour chaque rôles
    Navigation inter-modules
  
- Internationalisation

    Disponible en plusieurs langues (EN/FR)

- Pages d'accueil : Login, selections & Home Pages
    Dashboard acceuil

- Schéma de DB et API REST
  
    Implémentation du schéma de DB (database)
    Mise en place d'une API sécurisée avec authentification *CC 3.8.2*
    Documentation technique format OpenAPI/Swagger
    
- Gestion des rôles & Mapping Accred 🟠
    
    Sécurité d'accès (groupes, permissions)
    *CC 3.8.3* 
    Définition et attribution des différents niveaux d'accès utilisateurs
    Intégration avec le système de gestion des accès EPFL
    Protection des données sensibles selon les droits utilisateurs (groupes, permissions)
    
- Gestions utilisateuri.ces

  Utilisateurice principal/standard
  différents rôles
  accès différents
  

[Specs] Déplacement pro

[Specs] Résultat

### ⚡S2  19.11 - 02.12

- Interfaces admins (IT/métier)
      
    Selon *CC 3.7.8*
    Gestion des 5 rôles 
    User flow Gestionnaire IT
    User flow Gestionnaire Métier complet/restreint
    
    
- Déplacements pro
    
    Selon *Annexe 6 3.3.4* 
    Import data en csv (manuel)
    Saisie déplacements, km, moyen de transport, etc..
    Calcul Co2 en temps réel avec l’aide des facteurs
    Intégrations facteurs d’émissions
    
    Messages d’erreurs et validations
    
    Sauvegarde et historiques
    
    visualisation des data rentrées, avec filtres et graphiques
    
    implémentation des datas dans la DB
    
    gestion des accès/visualisations par utilisateurs
    
    Affichage de message si dépasse un certains seuils
    
- Améliorations UX
    
    Améliorations des pages d'accueil minimalistes
    Ergonomie améliorée (accessibilité)
    

[Specs] Mon labo

[Specs] Achat

### ⚡S3 03.12 - 18.12 

- Résultats (MVP 1/2)
    Visualisation : Graphiques, filtres interactifs pour mieux analyser les données
    Calculs
    Comparaison temporelle
    export des résultats CSV/PDF
    
- Mon labo 
    
    Selon *Annexe 6 3.3.3*
    
    Saisie EPT, surfaces, infos de base
    
    import data en csv
    
    Messages d’erreurs et validations
    
    Sauvegarde et historiques
    
    visualisation des data rentrées, avec filtres et graphiques
    
    implémentation des datas dans la DB
    
    gestion des accès/visualisations par utilisateurs
    

[Specs] Infrastructure



### ⚡S4 31.12 - 19.01

- Achats (MVP 1/2)
    
    *Annexe 6 3.3.7.1*  
    
    construction avec sous modules
    
    Import data en csv
    
    Saisie achats (NACRES, IT, consommables)
    
    calcul du CO2-eq
    
    Intégration des facteurs d'émission liés aux achats
    
    fichier contenant les codes NACRES et facteurs import et export possible depuis Métier
    
    fichier correspondance UNSCP ↔ NACRES import et export depuis Métier
    
    Messages d’erreurs et validations
    
    Sauvegarde et historiques
    
    visualisation des data rentrées, avec filtres et graphiques
    
    implémentation des datas dans la DB
    
    gestion des accès/visualisations par utilisateurs
    
    Affichage de message si dépasse un certains seuils
    
    intégrer des explication sur les calculs
    
    Transport des achats (optionnel) 🟡
    
    Empreinte carbone alternative (optionnel)
    
    outil IA EPFL (optionnel)
    
- Documentation utilisateur.ices
    
    mkDocs setup
    Formation mkDocs+Github "as a CMS" pour documentation.
    
    Interface documentation : Testing of additional UI layers for doc editiing (Decap) depending on admins' needs. 
    
    
    3 pages; explication durabilité, info et liens ress externe, info et liens ress intern

- Refactor intermédiaire   

[Specs] Services interne

### ⚡S5 20.01 - 10.02

- Achats (2/2)
    
    *Annexe 6 3.3.7.1*
    
    construction avec sous modules
    
    Import data en csv
    
    Saisie achats (NACRES, IT, consommables)
    
    calcul du CO2-eq
    
    Intégration des facteurs d'émission liés aux achats
    
    fichier contenant les codes NACRES et facteurs import et export possible depuis Métier
    
    fichier correspondance UNSCP ↔ NACRES import et export depuis Métier
    
    Messages d’erreurs et validations
    
    Sauvegarde et historiques
    
    visualisation des data rentrées, avec filtres et graphiques
    
    implémentation des datas dans la DB
    
    gestion des accès/visualisations par utilisateurs
    
    Affichage de message si dépasse un certains seuils
    
    intégrer des explication sur les calculs
    
    sous module Transport des achats (optionnel)
    
    Empreinte carbone alternative (optionnel)
    
    outil IA EPFL (optionnel)
    
- Infrastucture
    
    *Annexe 6 3.3.5.1* 
    
    Import data en csv
    
    calcul du CO2-eq
    
    Messages d’erreurs et validations
    
    Sauvegarde et historiques
    
    visualisation des data rentrées, avec filtres et graphiques
    
    implémentation des datas dans la DB
    
    gestion des accès/visualisations par utilisateurs
    
    Affichage de message si dépasse un certains seuils
    
    intégrer des explication sur les calculs
    
    Saisie bâtiments, ventilation, chauffage, éclairage
    
    occupation des locaux et surface de pièces correspondant au nom du labo auto avec un fichier csv métier
    
    Intégration des facteurs d'émission liés à la consommation électrique
    
    calcul CO2 avec le coeff du bâtiment (qui est dans un csv Métier)
    

[Specs] Consommation électrique

[Specs] Impact des services cloud

### ⚡S6 11.02 - 02.03

- Consommation électrique équipements 
    
    *Annexe 6 3.3.6*
    
    Import data en csv
    
    Messages d’erreurs et validations
    
    Sauvegarde et historiques
    
    visualisation des data rentrées, avec filtres et graphiques
    
    implémentation des datas dans la DB
    
    gestion des accès/visualisations par utilisateurs
    
    Affichage de message si dépasse un certains seuils
    
    Saisie équipements + consommation électrique + usage (se base sur N-1)
    
    avec trois familles
    
    Ajout des facteurs d'émission spécifiques aux différents types d'équipements
    
    (optionel) modif cat. et sous cat depuis interface gestion métier
    
    Calcul CO2-eq par équipement

- Résultats (2/2)
    Visualisation : Graphiques, filtres interactifs pour mieux analyser les données
    Calculs
    Comparaison temporelle
    export des résultats CSV/PDF
    
- Services Internes 
    
    *Annexe 6 3.3.8* 
    
    Import data en csv
    
    Saisie services internes (plateformes, types)
    
    liste de centres et plateformes modif depuis Métier
    
- Déploiement version Alpha α

[Specs] Emissions directes

[Specs] Alimentation et pendularité

[Specs] Energie grise



### ⚡S7 03.03 - 23.03
- Refactor intermédiaire
- Impact Cloud externes
    
    *Annexe 6 3.3.9* 
    
    Intégration des facteurs d'émission liés aux services
    
    type de services et facteurs mis à jour dans Métier
    
- Emissions directes 
    
    Import data en csv
    
    Saisie des émissions directes du laboratoire
    
- Alimentation et pendularité 
    
    calcul  avec data fourni par Métier et module labo
    
- Energie grise 
    
    calcul avec data fourni par Métier

[Specs] Simulation de projet

[Specs] Déchets

### ⚡S8 23.03 - 13.04

- Gestion des bugs, intégration des retours
    
    Intégrations des retours
    
    corriger bugs et imprévus

- Déchets 
    
    calcul avec data fourni par Métier et module labo
    
### ⚡S9 14.04 - 04.05

- Simulation de projet 
- Refactor final

### ⚡S10 05.05 - 26.05

- Gestion des bugs, intégrations des retours
    
    Intégrations des retours
    
    corriger bugs et imprévus
    
- Déploiement version Beta β

