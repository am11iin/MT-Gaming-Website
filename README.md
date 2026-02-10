# MT Gaming - Site Web

Site web moderne pour centre de jeux gaming à Alger.

## 📁 Fichiers

- `index.html` - Page principale
- `style.css` - Styles
- `script.js` - Interactions

## 🚀 Installation

Placez les 3 fichiers dans le même dossier et ouvrez `index.html`.

## 🌐 Déploiement

**Netlify** (le plus simple) :
1. Allez sur [netlify.com](https://netlify.com)
2. Glissez-déposez le dossier
3. C'est en ligne !

**Vercel ou GitHub Pages** fonctionnent aussi.

## ✏️ Personnalisation

### Modifier le téléphone
Dans `index.html`, cherchez `+213 770 123 456` et remplacez.

### Modifier les tarifs
Dans `index.html`, section `#pricing`, changez les montants :
```html
<span class="amount">300</span>
```

### Modifier les couleurs
Dans `style.css`, début du fichier :
```css
--accent: #00ff88;  /* Couleur principale */
```

### Changer la carte Google Maps
1. Allez sur Google Maps
2. "Partager" → "Intégrer une carte"
3. Copiez le code iframe
4. Remplacez dans `index.html`

## 🌍 Langues

Le site supporte français et arabe. Pour ajouter du texte traduit :
```html
<h1 data-fr="Texte français" data-ar="النص العربي">
```

---

**Contact :** +213 770 123 456 | MT Gaming, Alger
