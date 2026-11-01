# System Log Analysis Lab — Linux

- **Statut :** Personal Lab — In Progress.
- **Contexte et objectif :** analyser des événements de journaux Linux dans un scénario contrôlé et synthétique, puis rédiger une courte analyse avec limites et recommandations.
- **Ma contribution :** le dossier local contient un outil Python, plusieurs détecteurs, des règles, un jeu de données synthétique, une vérité terrain et des tests. Validation personnelle et rédaction d'apprentissages à compléter.
- **Technologies et outils :** Python, systemd/journalctl, pytest; données JSON Lines synthétiques.
- **Fonctionnalités présentes dans le dépôt :** parsing de journaux JSON, règles de détection, rapports Markdown/CSV et outil de sanitisation selon sa documentation.
- **Architecture :** export contrôlé de journaux → parseur → détecteurs → rapport; les exercices fournis s'appuient sur des données synthétiques.
- **Captures / preuves :** aucun journal réel n'est inclus dans ce portfolio; les résultats personnels et captures sont à ajouter après exécution.
- **Apprentissages :** à écrire par Analtino après exécution et interprétation des résultats.
- **Limites et suites :** exécuter les commandes, vérifier les résultats, écrire une analyse courte et documenter les faux positifs possibles. Les alertes ne prouvent pas à elles seules une compromission.

Ce projet ne représente pas une expérience professionnelle SOC, SIEM ou réponse à incident.
