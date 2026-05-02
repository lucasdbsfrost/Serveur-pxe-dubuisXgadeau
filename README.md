# SRSEV2 - Service Réseau Saint Eloi Version 2

## 📝 Présentation du projet
Ce projet consiste en la modernisation complète de l'infrastructure réseau de la salle **SUD07** du Lycée polyvalent Saint Eloi (Aix-en-Provence). L'objectif principal est de fournir un environnement polyvalent et facile à administrer pour les étudiants du BTS CIEL.

## 🚀 Fonctionnalités clés
* **Dual Boot automatisé** : Déploiement système permettant de choisir entre Windows (Production) et Kali Linux (Audit/Cyber) au démarrage.
* **Gestion centralisée** : Mise en place d'un contrôleur de domaine Active Directory pour la gestion des sessions étudiants.
* **Infrastructure PXE/FOG** : Industrialisation du déploiement via un serveur **FOG** pour masteriser et restaurer l'ensemble de la salle en quelques minutes.
* **Services Réseau** : Configuration complète des rôles DNS et DHCP pour l'adressage et la résolution de noms.
* **Sensibilisation Cyber** : Simulation de campagnes de phishing via **Gophish** pour évaluer et former les utilisateurs.

## 🛠️ Stack Technique
* **Serveur** : Dell PowerEdge R300.
* **OS Serveur** : Windows Server 2019.
* **Réseau** : Switch HP J8164A.
* **Logiciels** : FOG Project, VirtualBox, Gophish, Wireshark, Veyon, VS Code.

## 👥 Équipe du projet
* **Lucas DUBUIS** : Conception technique, stratégie de partitionnement, **configuration et mise en production du serveur FOG**, industrialisation du déploiement et conformité RGPD.
* **Axel GADEAU** : Installation de l'infrastructure Windows Server, AD DS, DNS, DHCP et support technique FOG.
* **Alexandre BILLION** : Tests d'intrusion (Pentesting) et déploiement des campagnes de sensibilisation phishing.

## 📅 Historique du projet
* **Jan 26, 2025** : Création initiale du rapport de projet.
* **May 20, 2025** : Premier oral de présentation et retour sur les objectifs.
* **May 26, 2025** : Finalisation du système Dual Boot Kali/Windows opérationnel.
* **Jun 12, 2025** : Mise à jour finale de la présentation des travaux personnels.

## ⚠️ Difficultés résolues
* **Limitations matérielles** : Absence de support SLAT sur le R300, imposant l'utilisation de VirtualBox au lieu d'Hyper-V
