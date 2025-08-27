# Compétition de Drone Laser Tag 🚁

## Fiche d'Identité

*   **Type de projet :** Projet Club
*   **Team Lead :** Anthony Lavertu
*   **Partenaire Académique/Industriel :** Philippe Giguère
*   **Effectif recherché :** 5 membres
*   **Profils recherchés :** Génie physique (optique), Génie électrique, Génie informatique (embarqué), Génie mécanique, Génie logiciel

## Description du Projet

L'idée est de faire une compétition inter universitées de conduite de drone automatique. Ça va être comme les jeux de lazer tag, mais avec des drones piloté par un IA. L'objectif de la session est de consevoir le système de lasers de manière à ce qu'il puissent s'ajouter sur des drones et qu'ils soient indépendant afin d'éviter la triche. Le système devra:
- Envoyer des lasers
- Avoir un capteur 180° qui recoit les rayons lasers.
- Avoir un processeur on board (et le programme) qui process l'info
- Avoir un émetteur qui envoit les hits à un ordinateur central qui pourra faire un leaderboard. (Nombre de lazer envoyé, nombre de laser reçu)
- Le système doit être production ready, donc avec un support standard pour le fixer sur les drones et un PCB custom (Pas un arduino ou autre)
- Avoir un receveur connecté à l'ordinateur centrale qui permet de recevoir les stats
- Un programme dans l'ordinateur centrale qui garde l'états de la partie pour éviter la triche et peut montrer le leaderboard.
- Si on a le temps, peut être mettre un système pour déterminer la hauteur du drone et pénaliser si trop haut
- Si on a le temps, faire un kill switch controlable par le game master (L'arbitre) en cas de problèmes.

## Objectifs & Livrables

*   **Objectif Principal :** Développer un système laser production ready pouvant être installé sur n'importe quel drone de compétition.
*   **Livrables attendus :**
    *   Système laser avec capteurs 180° fonctionnel
    *   PCB custom et programme embarqué
    *   Logiciel central de gestion de parties et leaderboard
    * Supports mécaniques et boîtier professionnel

## Timeline Prévisionnelle de la Session


| Date         | objectif | 
| :----------: | :------: |
| Semaine 1-2  |   Embauche, Exploration du projet, achats des premières pièces, séparation des tâches   |
| Semaine 3-4  |   Assemblage du drone, du système laser-récepteur (et test des hémisphères), conception du programme embarqué. Le tout sur un bread board. Achat de nouvelles pièces pour autre tentatives  |
| Semaine 5-6  |   Finaliser les essaies du système, design du PCB, intégration du programme avec le récepteur et receveur et le flight controller du drone. Amorcer le design du case |
| Semaine 7-8  |   Préparation à la semaine de lecture, donc rien de planifié, voir rattrapage   |
| Semaine 9-10 |   Finaliser le design du case, faire le programme sur l'ordinateur centrale (leaderboard), tester le case   |
| Semaine 11-12|   Améliorer le case, notre méthode de produire le système et le tester. Si on a le temps, faire les features optionelles  |
| Semaine 13-14|   Préparation de la fin de session, sinon rattrapage   |
|  ...         |  ...     |

## Technologies & Compétences Visées

*   **Matériels :** Drone FPV, composants laser IR, microcontrôleurs, PCB custom
*   **Compétences :** Conception optique, électronique embarquée, programmation bas niveau, design mécanique, prototypage rapide

## Pourquoi rejoindre ce projet ?

Tu vas aimer ce projet si :
*   Tu veux participer à la création d'une compétition technologique unique entre universités
*   Tu aimes travailler sur un projet concret alliant hardware et software
*   Tu veux développer des compétences en prototypage et conception de systèmes complexes
