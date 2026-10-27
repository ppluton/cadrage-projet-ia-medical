# Audit des données

[Retour au dossier](../README.md) · Référence : rapport, page 5.

## Questions et preuves attendues

| Dimension | Contrôles | Livrable |
|---|---|---|
| Accès et intégration | Exports disponibles, formats et droits d’usage | Inventaire et contrat d’entrée/sortie |
| Qualité | Clés, doublons, dates, unités, valeurs absentes | Contrôles et synthèse d’anomalies |
| Représentativité | Formulations, négations, contradictions, historique | Grille de couverture revue par le médecin |
| Sécurité | Dossier autorisé, rétention, sous-traitants | Cartographie des flux et matrice d’accès |
| Valeur de la recherche | Résumé sourcé face à la consultation manuelle | Comparatif factuel et temps de vérification |

## Corpus d’essai envisagé

Dix dossiers synthétiques et vingt scénarios, avec dix cas réservés à la recette après réglage. Séparer les dossiers de réglage et de recette pour éviter de tester sur les seuls cas utilisés pour ajuster la solution. Synthea est une source candidate, pas un corpus déjà évalué ici.

Conserver dossier, rencontre, date et provenance ; documenter les transformations. Ne jamais inventer une donnée absente. Les reformulations doivent préserver les valeurs, unités et périodes.

L’ingénieur IA définit les règles de qualité et contrôle les résultats ; le développeur réalise les scripts. Une migration complexe ou plusieurs systèmes sources peuvent justifier un data engineer dédié, à chiffrer après l’audit.

Ce petit corpus permet de détecter des défauts et de vérifier le parcours, pas de conclure à une fiabilité clinique générale.
