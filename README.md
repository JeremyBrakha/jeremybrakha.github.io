# jeremybrakha.github.io

Site statique au service de l’app Android personnelle « Finances ».

- `enable-banking/callback.html` : adresse de retour déclarée chez Enable Banking. Android la confie directement à l’app (App Link) ; sinon, la page transmet la réponse de la banque à l’app.
- `.well-known/assetlinks.json` : autorise l’app, signée par la clé indiquée, à ouvrir les liens de ce site.
- `.nojekyll` : sans lui, GitHub Pages ne publie pas `.well-known/`.
