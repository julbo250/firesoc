# Éditeur de places.sqlite

<img width="1408" height="615" alt="Capture d’écran 2026-02-07 à 09 19 02" src="https://github.com/user-attachments/assets/c94279b4-3933-4b88-9e49-7712f06b54ef" />


## Description

Cette application permet d’**éditer et d’analyser le fichier `places.sqlite`** situé dans le répertoire du **profil utilisateur** (notamment utilisé par les navigateurs basés sur Firefox).

Elle facilite la **recherche et l’exploration des URLs consultées** ainsi que des **fichiers téléchargés**, à partir des données stockées localement par le navigateur.

L’objectif principal est de fournir un outil simple pour :

* consulter l’historique de navigation
* rechercher des URLs spécifiques
* analyser les fichiers téléchargés
* explorer la base de données SQLite associée au profil utilisateur

---

## Fonctionnalités

* 📂 Ouverture du fichier `places.sqlite`
* 🔍 Recherche par URL
* ⬇️ Recherche et consultation des fichiers téléchargés
* 🗃️ Lecture et modification des données SQLite
* 👤 Utilisation sur un profil utilisateur local

---

## Prérequis

* Accès au répertoire du **profil utilisateur**
* Le navigateur concerné doit être **fermé** avant toute modification du fichier `places.sqlite`
* Environnement compatible avec SQLite

---

## Utilisation

1. Localiser le répertoire du profil utilisateur
2. Faire une **copie de sauvegarde** du fichier `places.sqlite`
3. Ouvrir l’application
4. Charger le fichier `places.sqlite`
5. Effectuer vos recherches sur :

   * les URLs visitées
   * les fichiers téléchargés
6. Appliquer les modifications si nécessaire

⚠️ **Attention** : une modification incorrecte du fichier peut entraîner une perte de données ou un dysfonctionnement du navigateur.

---

## Sécurité et confidentialité

Cette application fonctionne **uniquement en local**.
Aucune donnée n’est envoyée vers un service externe.

Les informations contenues dans `places.sqlite` peuvent être sensibles (historique, téléchargements). Utilisez cet outil de manière responsable.

---

## Limitations

* Compatible uniquement avec les navigateurs utilisant `places.sqlite`
* Ne pas utiliser pendant que le navigateur est en cours d’exécution
* Aucune garantie de compatibilité avec toutes les versions de navigateurs

---

## Licence

Ce projet est distribué sous licence **MIT**.

Vous êtes libre de :

* utiliser le code
* le modifier
* le redistribuer

Sous réserve de conserver la licence et les mentions de copyright.

---

## Avertissement légal

Ce logiciel est fourni **« tel quel »**, sans aucune garantie.
L’auteur ne pourra être tenu responsable d’une perte de données, d’un usage abusif ou de tout dommage résultant de l’utilisation de cette application.

---

## Contribution

Les contributions sont les bienvenues :

* corrections
* améliorations
* nouvelles fonctionnalités

N’hésitez pas à ouvrir une *issue* ou une *pull request*.

---

## Auteur

Projet développé par **Julbo250**
