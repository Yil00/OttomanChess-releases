# OttomanChess — Téléchargements & mises à jour

**OttomanChess** est un assistant d'analyse d'échecs pour macOS : un overlay s'affiche
directement sur vos parties **lichess.org** et **chess.com** et montre les meilleurs coups
calculés **localement** par un moteur d'échecs — rien ne quitte votre Mac.

➡️ **[Télécharger la dernière version](https://github.com/Yil00/OttomanChess-releases/releases/latest)** · [Site de présentation](https://yil00.github.io/OttomanChess-releases/)

## Fonctionnalités

- Analyse en direct de la position pendant vos parties (lichess & chess.com), aussi bien avec les blancs qu'avec les noirs
- Jusqu'à **5 meilleurs coups** affichés, couleurs et opacité personnalisables
- **Lignes complètes du moteur (PV)** au survol d'une flèche
- **Historique d'analyse + export PGN annoté** (`[%eval …]`, importable dans lichess / chess.com)
- **Choix du moteur** : Stockfish 19, Reckless, PlentyChess — bascule en pleine partie
- Profondeur réglable, barre d'évaluation, bloqueur de pubs (chess.com)
- Sessions persistantes par site, **profils de connexion en un clic** (Trousseau macOS)
- Raccourcis clavier, **mises à jour automatiques** (Sparkle, signature EdDSA)
- App **signée Developer ID et notariée par Apple**

## Installation

1. Téléchargez le `.dmg` de la [dernière release](../../releases/latest)
2. Ouvrez-le et glissez **OttomanChess** dans **Applications**
3. Lancez l'app — aucun avertissement Gatekeeper (app notariée)

**Configuration requise** : Mac Apple silicon, macOS 26.5 ou ultérieur.

## Confidentialité

- Les moteurs d'analyse tournent **100 % en local** — aucune position n'est envoyée en ligne
- Aucun compte, aucune analytique, aucun traqueur
- Les identifiants (optionnels) restent dans le **Trousseau macOS**
- Ce dépôt ne contient que les DMG publiés et le flux de mises à jour : le code source est privé

## Ce dépôt

- **Releases** : DMG notariés de chaque version (onglet [Releases](../../releases))
- **`appcast.xml`** : flux de mises à jour automatiques Sparkle
- **`index.html`** : page de présentation ([GitHub Pages](https://yil00.github.io/OttomanChess-releases/))
- Un bug ou une idée ? Ouvrez une [issue](../../issues)

## Licences

Code source d'OttomanChess : privé, tous droits réservés.
Moteurs tiers inclus sous leurs licences respectives : Stockfish (GPLv3), Reckless (AGPLv3), PlentyChess (GPL).
