README - Hébergement (GitHub Pages / Netlify)

Fichiers inclus:
- index.html
- style.css

Instructions rapides pour héberger:

1) GitHub Pages:
   - Crée un dépôt GitHub (public).
   - Pousse les fichiers (index.html et style.css) à la branche 'main' ou 'gh-pages'.
   - Dans les paramètres du dépôt -> Pages -> Source: 'main' (root) ou 'gh-pages'.
   - GitHub fournira une URL du type: https://<ton-pseudo>.github.io/<nom-du-depot>/
   - Une fois la page en ligne, le QR code intégré pointera automatiquement vers l'URL de la page.

2) Netlify:
   - Crée un compte sur https://www.netlify.com .
   - Drag & drop: Glisse le dossier contenant index.html et style.css sur Netlify (site -> new site -> deploy).
   - Netlify te donnera une URL du type: https://your-site-name.netlify.app
   - Le QR code intégré pointera vers cette URL automatiquement.

QR code:
- Le QR code est généré côté client et encode l'URL actuelle (location.href). Après hébergement, il pointera vers l'URL publique.

Personnalisation:
- Modifie le contenu (textes, liens, photo) dans index.html.
- Pour ajouter une photo de profil, remplace la balise SVG de l'avatar par: <img src="ton-image.jpg" alt="Huna Homai" style="width:120px;height:120px;border-radius:12px;">

Besoin d'aide:
- Si tu veux que je te fournisse le dépôt prêt (avec commit), ou que je te guide étape par étape pour GitHub Pages ou Netlify, dis-le et je t'aide.
