# ATHENA - Spécifications V1

## 1. Présentation

ATHENA est un assistant de trading basé sur l'analyse technique et la lecture intelligente du marché.

Son objectif est d'identifier les configurations présentant la meilleure probabilité de réussite selon un ensemble de règles quantitatives.

ATHENA privilégie la qualité des décisions plutôt que la quantité de trades.

---

# 2. Marchés analysés

Version initiale :

- OR (XAU/USD)
- Bitcoin (BTC/USD)
- EUR/USD

---

# 3. Analyse Multi-Timeframe

ATHENA utilise plusieurs unités de temps :

- 4H : analyse de la structure principale du marché
- 1H : confirmation de la tendance et des zones importantes
- 15M : recherche des opportunités d'entrée

---

# 4. Philosophie décisionnelle

ATHENA ne choisit pas une stratégie fixe.

Elle analyse :

"Le marché présente telle structure et telles caractéristiques ; selon les règles définies, cette configuration est valide."

---

# 5. Score de validation

Chaque opportunité reçoit un score de confiance.

Une position peut être envisagée lorsque :

- structure de marché valide
- tendance confirmée
- configuration technique cohérente
- risque maîtrisé
- score ATHENA supérieur ou égal à 75%

---

# 6. Gestion des positions

ATHENA doit être capable de :

- définir une direction probable (achat ou vente)
- proposer un point d'entrée
- calculer un stop loss logique
- définir un objectif
- surveiller les conditions de sortie

---

# 7. Analyse des chandeliers

ATHENA reconnaît plusieurs figures :

- Doji neutre
- Doji haussier
- Doji baissier
- Englobement haussier
- Englobement baissier
- Pin bar
- Rejet de zone

---

# 8. Philosophie fondamentale

ATHENA privilégie :

- moins de trades
- plus de qualité
- meilleure sélection des configurations

L'objectif n'est pas de trader constamment mais d'intervenir uniquement lorsque les conditions sont favorables.