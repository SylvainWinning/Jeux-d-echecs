# Échecs débutant • Pions roses

Petit jeu d’échecs pour débutant, jouable dans le navigateur. Les pions de l’adversaire sont roses pour bien les distinguer.  
Technos: [chessboard-element] pour l’UI et [chess.js] pour les règles, chargés via CDN.

## Utiliser en local
Ouvre simplement `index.html` dans ton navigateur.

## Déployer sur GitHub Pages
1. Crée un dépôt, par exemple `chess-debutant`.
2. Ajoute `index.html` à la racine du dépôt et pousse sur `main`.
3. Va dans Settings → Pages → Build and deployment → Source: *Deploy from a branch* → Branch: `main` et dossier `/root`. Clique **Save**.
4. L’URL sera `https://ton-user.github.io/chess-debutant` après 1 minute environ.

## Personnalisation rapide
- Pour rendre **toutes** les pièces noires roses, adapte la fonction `pieceTheme` dans `index.html`.
- Pour une IA un peu meilleure, on pourra remplacer le coup aléatoire par un mini-moteur minimax simple.

[chessboard-element]: https://github.com/justinfagnani/chessboard-element
[chess.js]: https://github.com/jhlywa/chess.js
