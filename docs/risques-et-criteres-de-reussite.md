# Risques, recette et décisions

[Retour au dossier](../README.md) · Référence : rapport, pages 17 à 20.

## Risques principaux

| Risque | Mesure proposée | Responsable |
|---|---|---|
| Fait inventé, omission, négation altérée | Références attendues, revue métier et suspension si défaut critique | Médecin et ingénieur IA |
| Mauvais dossier, date ou version | Autorisations serveur et tests négatifs | Développeur et QA |
| Données inadaptées | Audit, qualité et séparation réglage/recette | Ingénieur IA, fonction data |
| Dérive des délais ou coûts | Reste à faire par tâche, arbitrage de périmètre | Pierre et sponsor |
| Faible adoption | Gabarit coconstruit, observation et mesure du temps complet | Médecin référent |
| Conditions de traitement inadaptées | Qualification avant usage réel ; données synthétiques sinon | Conseil et DevOps |

## Cibles de recette proposées

- Gain net d’au moins deux minutes par compte rendu, correction et vérification comprises.
- Au moins 95 % des faits requis couverts et aucun défaut critique observé sur le jeu de recette.
- Sources reliées au dossier et datées ; information absente signalée.
- Réussite de tous les tests négatifs d’accès, de version et d’export.
- Performance cible : p95 inférieur ou égal à 90 secondes pour un audio de trois minutes et quatre traitements simultanés, à mesurer.
- Reprise cible : perte maximale de 24 heures et restauration en quatre heures ouvrées, à vérifier par un exercice.

Tester séparément le compte rendu et le résumé. Inclure panne fournisseur, contradiction, injection de prompt dans un document, conflit de version et dossier voisin. Une moyenne satisfaisante ne compense pas une erreur critique.

## Qualification et passage au réel

Faire qualifier finalité, rôles, bases légales, rétention, sous-traitance, transferts et éventuelle AIPD ou formalité. Examiner l’applicabilité et le périmètre HDS sur la chaîne concernée. Une région européenne, une certification d’hébergeur ou une installation locale ne démontrent pas à eux seuls la conformité du produit. Les sources institutionnelles sont listées dans [les références](sources-et-statut.md).

Le conseil initial d’un jour couvre une revue du périmètre, pas une procédure réglementaire complète. Toute exigence supplémentaire impose un nouveau chiffrage et peut décaler les quatre semaines.

Après recette et conditions d’usage acceptées, un pilote avec deux praticiens et trente comptes rendus éligibles fournit un premier bilan d’usage. Il ne constitue pas une validation clinique. Avant ouverture aux quatre praticiens : droits vérifiés, qualité acceptée, restauration réussie, support nommé, formation et accord du sponsor.
