
# Cahier des charges initial — Aether AI

## Objectif principal

Construire une application qui permet à un utilisateur
d'interroger ses documents et d'obtenir des réponses appuyées
sur des passages pertinents et identifiables.

## Utilisateur cible initial

Un développeur ou un étudiant en informatique qui consulte
régulièrement de la documentation technique.

## Fonctionnalités attendues du MVP

1. Importation d'un document PDF.
2. Extraction du texte.
3. Indexation du contenu.
4. Recherche de passages pertinents.
5. Génération d'une réponse à une question.
6. Présentation des sources utilisées.
7. Gestion des erreurs et des documents invalides.

## Exigences de qualité

- Ne pas présenter une réponse comme certaine sans éléments suffisants.
- Ne pas inventer de références documentaires.
- Isoler les données de chaque utilisateur si plusieurs comptes sont ajoutés.
- Ne jamais exposer les clés API ou les identifiants AWS.
- Tester le fonctionnement des principales fonctionnalités.

## Hors périmètre initial

- Agent exécutant des actions sur AWS.
- Déploiement automatique d'infrastructure.
- Application multi-entreprise complète.
- Entraînement d'un grand modèle de langage depuis zéro.

## Critères de réussite du MVP

- Un document valide peut être importé.
- Son contenu peut être recherché.
- Une question pertinente obtient une réponse fondée sur le document.
- Les sources affichées correspondent au contenu réellement récupéré.
- Une question sans réponse dans les documents est traitée correctement.
- Les principaux cas d'erreur sont couverts par des tests.

## Contraintes

- Privilégier les solutions gratuites ou locales au démarrage.
- Contrôler toute dépense AWS.
- Utiliser Git pour suivre les modifications.
- Documenter les choix techniques importants.

## Décisions à confirmer

- Modèle d'IA retenu.
- Solution de recherche vectorielle.
- Services AWS définitifs.
- Format et taille maximale des documents.
- Stratégie d'authentification.


## Séance du 16/10/2026 : 
Durant cette séance j'ai crée : 

- Le plan de réalisation du projet 
- fait le choix de mon MVP
- créer le dossier du projet 
- crée la structure de base du projet (mais vraiment la base des bases quoi)
- fait la première rédaction de README.md 
- fait le premier Commit 
- En gros tout est initiliasié 
- Je me rassure de la disponibillité de toute la stack .
- ...