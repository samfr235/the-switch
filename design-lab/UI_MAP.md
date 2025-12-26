# UI Map — The Switch (V1)

## Principe général
The Switch repose sur **une seule vue centrale** (Dashboard),
décomposée en **3 blocs verticaux**, visibles simultanément.

Aucune navigation complexe.
Aucun menu profond.
Tout doit être compréhensible en moins de 30 secondes.

---

## Écran unique : Dashboard

### Bloc A — Configuration (Le moteur)
Objectif : définir la réalité de l’utilisateur.

Champs :
- Salaire net mensuel
- Heures travaillées par mois (travail + trajets)

Calcul automatique :
- Taux horaire réel (temps de vie)

Contraintes UX :
- Peu de champs
- Calcul en temps réel
- Résultat mis en valeur visuellement

---

### Bloc B — Le Passé (Analyse)
Objectif : relier les dépenses au temps de vie.

Entrées :
- Import CSV (relevé bancaire)
- Catégorisation simple (abonnements, charges, loisirs…)

Sorties :
- Graphique circulaire des dépenses récurrentes
- Interaction clé :
  - Survol d’une dépense → affichage :
    “Cette dépense = X heures de ta vie”

Contraintes UX :
- Graphique lisible
- Message choc, mais non culpabilisant

---

### Bloc C — Le Futur (Projection)
Objectif : montrer l’impact d’un changement.

Entrée :
- Nom de l’habitude à arrêter
- Coût mensuel associé

Simulation :
- Scénario 1 : dépense continue
- Scénario 2 : placement équivalent (hypothèse 7%)

Sorties :
- Courbe comparative (temps)
- Message de synthèse :
  “En changeant X, tu récupères Y € et Z heures de vie”

---

## Écrans secondaires (plus tard)
- Aide / pédagogie
- Paramètres
- Mentions légales

⚠️ Non prioritaires pour V1
