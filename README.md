# ComptaIA v2.1 — Déploiement Netlify

## 🚀 Déploiement en 3 minutes

### Option A — Glisser-déposer (le plus simple)

1. Allez sur **netlify.com** → Créez un compte gratuit
2. Sur le Dashboard, cliquez sur **"Add new site"** → **"Deploy manually"**
3. Glissez-déposez le **dossier `comptaia-web`** entier dans la zone indiquée
4. Netlify génère automatiquement une URL comme `https://amazing-name-123.netlify.app`
5. Optionnel : dans Site settings → Domain → renommez en `comptaia-votrenom.netlify.app`

### Option B — Via GitHub (mises à jour automatiques)

1. Créez un dépôt GitHub (github.com) → uploadez le dossier
2. Sur Netlify → "Import from Git" → choisissez votre repo
3. Build settings : laissez tout vide → Deploy
4. Chaque mise à jour GitHub → redéploiement automatique

## 🔑 Configuration après déploiement

1. Ouvrez votre URL Netlify
2. Allez dans **⚙ Paramètres**
3. Entrez votre clé API Anthropic (console.anthropic.com)
4. Entrez votre token Dropbox (dropbox.com/developers)
5. C'est prêt !

## 📱 Accès multi-postes

- **Ordinateur** : ouvrez l'URL dans Chrome/Firefox/Edge
- **Smartphone** : tapez l'URL dans Chrome/Safari → Ajouter à l'écran d'accueil
- **Tous les appareils** partagent les données via Dropbox

## 🔄 Mise à jour du logiciel

1. Exportez vos données : ⚙ Paramètres → Exporter JSON (précaution)
2. Remplacez `index.html` par la nouvelle version
3. Redéployez sur Netlify (glisser-déposer ou push GitHub)
4. Vos données sont préservées automatiquement (migration intégrée)

## 🏠 Utilisation hors-ligne (alternative)

Double-cliquez sur `index.html` dans votre dossier Dropbox → s'ouvre dans Chrome.
