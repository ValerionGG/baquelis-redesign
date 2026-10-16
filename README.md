# Baquelis — 10 propositions de refonte

Refonte complète du site de **Baquelis** (anciennement M3 Games, Nice) : partenaire technologique — équipes dédiées et flexibles, intelligence artificielle (modèles affinés, agents autonomes), expertise jeux vidéo & Web3, formules mensuelles Intégration / Flex / Performance. Contenu repris de m3.games et enrichi (méthode, simulateur d'économies, comparatif, FAQ, démo de l'agent ATOM).

**Site en ligne :** https://valeriongg.github.io/baquelis-redesign/

| # | Direction | Esprit |
|---|---|---|
| 1 | Noyau | Précision d'ingénierie, noir profond et lueur cyan |
| 2 | Agent | Le site devient une conversation avec ATOM |
| 3 | Monolithe | Conseil de prestige : noir, ivoire, grande sérif |
| 4 | Réseau | Le temps réel rendu visible : nœuds, flux, tableaux de bord |
| 5 | Arcade | L'ADN jeu vidéo, rétro-futuriste et haut de gamme |
| 6 | Holo | Luxe Web3 : holographie, verre et chrome |
| 7 | Système | L'artisanat de l'ingénierie : schémas et fiches techniques |
| 8 | Performance | Énergie e-sport : vitesse, précision, typographie cinétique |
| 9 | Nocturne | Bande-annonce de studio : parallaxe et lumière ambrée |
| 10 | Clarté | Suisse et lumineux : la transparence radicale |

Chaque direction : Accueil, Expertises, IA & agents, Jeux & Web3, Offres, Contact — interactives. Les formulaires n'envoient rien ; les démonstrations (ATOM, tableaux de bord, simulateurs de latence) sont illustratives.

## Structure

- `a/project/`, `b/project/` — sources des deux canvas Design (propositions 1–5 et 6–10).
- `docs/` — site statique publié par GitHub Pages (`node build.mjs`).
- `docs/dc.js` — mini-runtime autonome pour le format `.dc.html`, rendu par Preact (`docs/vendor/preact.min.js`, MIT).
- `assets/` — photos d'illustration (Unsplash).
- `BRIEF.md` — brief commun (contenu réel, enrichissements, règles).

Les informations à compléter apparaissent en marqueurs visibles ([RAISON SOCIALE], [N° TVA], [contact@domaine-baquelis]…).
