# 🎰 CroupierMental v6

Application d'entraînement au **calcul mental et à la mémoire du croupier** — un seul fichier HTML, zéro dépendance, fonctionne hors-ligne, pensée pour le téléphone.

👉 Ouvrir **`index.html`** dans n'importe quel navigateur, ou l'installer sur l'écran d'accueil de l'iPhone (Safari → Partager → « Sur l'écran d'accueil »).

## Jeux

| Jeu | Contenu |
|---|---|
| 💰 Paiements | Calcul de paiement avec **choix des paris travaillés** : plein, cheval, transversale, carré, sixain, douzaine, chance simple |
| 🧮 Combinaisons | **Picture bets** : additions de pleins, chevaux, carrés, transversales, sixains — avec décomposition visuelle et conversion pièces → espèces |
| 🧭 Voisins | **Cite un numéro et ses voisins** : les cases se remplissent une par une, centre donné, roue révélée à la fin |
| 🧠 Remplir le cylindre | Reconstituer la roue de tête — 5 cases en Facile jusqu'aux **37 cases du cylindre entier** en Expert |
| 🎯 Calculs cylindre | Voisin de droite/gauche, n-ième voisin, numéro opposé, mise totale, paiement, gain net |
| 🎡 Roulette complète | Tout le jeu mélangé |
| 📣 Annonces | **Voisins du zéro (9 pièces), Tiers du cylindre (6), Orphelins (5), Jeu zéro (4)**, finales en plein — appartenance, mise, paiement, gain net |
| 🃏 Blackjack | Paiement **3:2 (×1,5) à tous les niveaux**, assurance (coût & 2:1), comptage, multi-boxes, Perfect Pairs |
| 🀄 Baccarat | Joueur 1:1, commission banque 5%, égalité 8:1, paires 11:1 |
| ♠️ Texas Hold'em | Pots, **pots extérieurs (all-in : principal + side pots, double all-in)**, rake 5% |
| 👑 Ultimate | Ante, Play, Blind, barème Trips |
| 🪙 Change & jetons | **Euros ↔ jetons avec les valeurs de ton choix** (1, 2, 5, 10, 20, 25, 50, 100, 500) : conversion dans les deux sens, échange entre valeurs, change mixte, rendu client, décomposition au minimum de jetons — piles colorées à l'écran |
| ✖️ Tables | **Toutes les tables de 1 à 20 + la table de 1,5** (paiement Blackjack), multiplicateurs ×1 à ×20 parcourus sans trou |
| 🎰 Mix | Tous les jeux mélangés |

## 📚 Fiches de révision

Une section « Apprendre » sans chrono, pour mémoriser avant de s'entraîner :

- **Cylindre** — la roue européenne dessinée à l'échelle, sélection d'un numéro et du nombre de voisins (1 à 5), avec voisins gauche/droite, numéro opposé, mise et paiement
- **Annonces** — chaque annonce avec ses numéros couverts et sa **décomposition réelle en pièces sur le tapis** (ex. Voisins du zéro = 2 sur la transversale 0/2/3, 1 sur le cheval 4/7, 2 sur le carré 25/26/28/29…), plus les finales en plein
- **Paiements** — barèmes roulette, blackjack, baccarat, Ultimate
- **Figures** — figures classiques mémorisées (Plein+cheval 52, Numéro et les chevaux 103, Complet 135…) et contraintes du tapis

## Réglages par exercice

- **Paiements** : active ou désactive chaque type de pari pour ne travailler que ce que tu veux
- **Change** : choisis les valeurs de jetons en circulation (raccourcis « 5·10·20·50·100 », « Françaises », « Toutes »)
- **Tables** : coche les tables voulues (raccourcis Essentielles / Toutes / Aucune)
- Les réglages sont mémorisés d'une session à l'autre

## Modes

- **Libre** — sans chrono · **Chrono** — 60 secondes · **Survie** — 3 vies, le temps se resserre
- **Défis du jour** — 4 objectifs quotidiens (+40 XP chacun)
- **Révision** — rejoue automatiquement tes erreurs passées

## Progression

- 5 difficultés (Facile → Expert), multiplicateur d'XP ×1 → ×2,5
- Niveaux + 8 grades (Stagiaire → Directeur de Casino), combos, bonus de vitesse, records
- Statistiques : précision par jeu, temps moyen, activité 7 jours, historique
- Sons et vibrations désactivables · données 100% locales · migration automatique depuis la v4.3

## Qualité

Le contenu est vérifié automatiquement à chaque modification :

- **350 000 questions générées, 295 000 vérifications indépendantes** — chaque réponse est recalculée séparément de l'énoncé affiché
- Les **réglages sont vérifiés** : avec « sixain » seul, aucun autre ratio ne sort ; avec le jeton 20 seul, aucune autre valeur n'est citée
- Les **séquences** (voisins, remplissage) sont contrôlées case par case contre l'ordre réel de la roue
- L'**ordre du cylindre** est contrôlé face à une référence ressaisie à la main ; voisins, opposés et zones vérifiés pour les 37 numéros
- Les **annonces** sont validées structurellement : type de pari ↔ nombre de numéros ↔ ratio ↔ adjacence réelle sur le tapis, et la partition Voisins/Tiers/Orphelins = 37 numéros sans chevauchement
- **Couverture ×1 à ×20 sans trou** vérifiée pour chaque difficulté
- **68 vues contrôlées sur 4 tailles d'iPhone** (SE 320px → 15 Pro Max) : aucun débordement, **aucune cible tactile sous 44px** (recommandation Apple), aucune erreur JS

## Historique

- `index.html` — **v6** : exercice Voisins, remplissage du cylindre, paiements et change configurables, ergonomie mobile 44px
- v5.1 : cylindre, annonces, combinaisons, fiches de révision, tables 1→20 + 1,5
- `croupier-mental-v4.3.html` — ancienne version (React + Babel via CDN)
