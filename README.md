# 🎰 CroupierMental v5

Application d'entraînement au **calcul mental pour croupiers** — un seul fichier HTML, zéro dépendance, fonctionne hors-ligne.

👉 Ouvrir **`index.html`** dans n'importe quel navigateur (mobile ou desktop).

## Jeux

| Jeu | Contenu |
|---|---|
| 🎡 Roulette | Paiements (plein 35, cheval 17…), mises comprises, **annonces en pièces**, tiers/orphelins/voisins |
| 🃏 Blackjack | 3:2, assurance (coût & paiement 2:1), comptage de mains, multi-boxes, **Perfect Pairs** |
| 🀄 Baccarat | Joueur 1:1, **commission banque 5%**, égalité 8:1, paires 11:1 |
| ♠️ Texas Hold'em | Pots, side pots, **rake 5%** |
| 👑 Ultimate | Ante/Blind/Play, barème **Trips** et **Blind**, gains complets |
| 🪙 Jetons | Stacks, change, échanges, rendus |
| ✖️ Tables | Multiplications ciblées croupier (5 · 8 · 11 · 17 · 35) |
| 🎰 Mix | Tout mélangé |

## Modes

- **Libre** — sans chrono, à son rythme
- **Chrono** — 60 secondes pour scorer (records par difficulté)
- **Survie** — 3 vies, le temps de réponse se réduit au fil des bonnes réponses
- **Défis du jour** — 4 objectifs quotidiens (+40 XP chacun)
- **Révision** — rejoue automatiquement tes erreurs passées

## Progression

- 5 difficultés (Facile → Expert) avec multiplicateur d'XP (×1 → ×2.5)
- Niveaux + 8 grades de carrière (Stagiaire → Directeur de Casino)
- Combos (×2, ×3), bonus de vitesse, records personnels
- Statistiques : précision par jeu, temps moyen de réponse, activité 7 jours, historique de sessions
- Sons (WebAudio) et vibrations désactivables · données 100% locales (localStorage)
- Migration automatique de la progression depuis la v4.3

## Historique

- `index.html` — **v5.0** : réécriture complète en vanilla JS (sans React/CDN)
- `croupier-mental-v4.3.html` — ancienne version (React + Babel via CDN)
