# 4. Limites et vérification

Ce parcours décrit l’implémentation Lightning orientée conformité BOLT, canaux et extensibilité par plugins à partir de la version publique du dépôt.
Il ne constitue ni un audit de sécurité ni une garantie sur un déploiement particulier.
Les paramètres réseau, clés d’administration et dépendances externes restent hors de ce résumé.
Les interfaces montrent les contrats attendus, mais chaque appelant doit encore gérer les erreurs et reprises.
Les performances et coûts dépendent des données, de la plateforme et de la configuration réellement utilisées.
Les changements de version peuvent déplacer des modules ou modifier une convention exposée aux clients.
Une revue doit relier chaque invariant décrit aux fichiers de production qui l’appliquent.
Pour vérifier le comportement, consulter la suite de tests et les scénarios fournis dans le dépôt.
Aucune nouvelle installation, compilation ou exécution de test n’a été réalisée pour ce parcours documentaire.
