# Novalitix - Site Web Statique

Site web moderne et responsive pour Novalitix, spécialisé en ingénierie agentique (agents IA et systèmes multi-agents).

## 📋 Structure du Projet

```
NOVALITIX/
├── index.html                      # Page d'accueil
├── assets/
│   ├── css/
│   │   └── styles.css              # Styles globaux
│   ├── js/
│   │   └── main.js                 # JavaScript vanilla
│   └── images/                     # Images et médias
├── fr/                             # Pages en français
│   ├── solutions/
│   │   ├── index.html              # Hub Solutions
│   │   ├── systemes-multi-agents.html
│   │   ├── agents-conversationnels.html (à créer)
│   │   └── agents-operationnels.html (à créer)
│   ├── integration.html            # (à créer)
│   ├── methodologie.html           # Méthode en 6 étapes
│   ├── ressources.html             # (à créer)
│   ├── a-propos.html               # À propos
│   ├── contact.html                # Formulaire de contact
│   └── securite-rgpd.html          # (à créer)
└── README.md                       # Documentation
```

## 🚀 Installation & Utilisation

### Méthode 1 : Ouvrir directement
1. Ouvrez `index.html` dans votre navigateur
2. Naviguez dans le site

### Méthode 2 : Serveur local (recommandé pour le développement)

**Avec Python 3:**
```bash
cd d:\dev\projets\NOVALITIX
python -m http.server 8000
```
Ouvrez http://localhost:8000

**Avec Node.js (live-server):**
```bash
npx live-server
```

**Avec PHP:**
```bash
php -S localhost:8000
```

## 🎨 Design

Le site s'inspire du template Linkify avec :
- **Palette de couleurs** : Tons sombres avec accents gradient (bleu/violet)
- **Typographie** : Inter (système) - claire et moderne
- **Style** : SaaS/Startup, cartes glassmorphism, animations fluides
- **Responsive** : Mobile-first, adaptatif sur tous écrans

### Variables CSS principales
Les variables sont définies dans `assets/css/styles.css` :
- `--primary-color: #6366f1` (violet)
- `--secondary-color: #10b981` (vert)
- `--bg-darker: #020617` (fond principal)
- `--text-primary: #f1f5f9` (texte principal)

## 📱 Responsive Design

- **Mobile** : < 768px (menu hamburger, grille 1 colonne)
- **Tablette** : 768px - 1024px (grille adaptative)
- **Desktop** : > 1024px (layout complet)

## ✨ Fonctionnalités

### Navigation
- Menu responsive avec hamburger sur mobile
- Navigation sticky avec effet de transparence au scroll
- Liens smooth scroll pour ancres

### Animations
- Cartes avec hover effects
- Floating cards sur le hero
- Fade-in au scroll (IntersectionObserver)
- Transitions fluides

### Formulaire de contact
- Validation côté client
- Messages d'erreur/succès
- Champs requis marqués

## 🛠️ Technologies Utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Flexbox, Grid, Variables CSS, Animations
- **JavaScript Vanilla** : Pas de dépendances
  - Menu mobile
  - Scroll animations
  - Validation de formulaire
  - IntersectionObserver

## 📄 Pages Créées

### ✅ Pages complètes
- [x] **index.html** - Page d'accueil
- [x] **fr/solutions/index.html** - Hub solutions
- [x] **fr/solutions/systemes-multi-agents.html** - Systèmes multi-agents
- [x] **fr/methodologie.html** - Processus en 6 étapes
- [x] **fr/contact.html** - Formulaire de contact
- [x] **fr/a-propos.html** - À propos

### 📝 Pages à créer
- [ ] **fr/solutions/agents-conversationnels.html**
- [ ] **fr/solutions/agents-operationnels.html**
- [ ] **fr/integration.html**
- [ ] **fr/ressources.html** (+ blog)
- [ ] **fr/securite-rgpd.html**
- [ ] Mentions légales
- [ ] Politique de confidentialité

## 📝 Contenu

Le contenu est basé sur le document PDF fourni :
- Pas de démo ni de ROI garanti
- Focus sur la crédibilité (méthode, livrables, expertise)
- Approche "B2B digital-first"
- Transparence et sobriété

## 🎯 SEO & Accessibilité

- Meta descriptions sur toutes les pages
- Balises sémantiques (header, nav, main, section, footer)
- Alt text pour les images (à ajouter)
- Liens accessibles au clavier
- Contrastes WCAG AA
- Aria labels sur boutons

## 🔧 Personnalisation

### Modifier les couleurs
Éditez les variables CSS dans `assets/css/styles.css` :
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #10b981;
    /* ... */
}
```

### Modifier le contenu
Éditez directement les fichiers HTML correspondants.

### Ajouter des images
1. Placez les images dans `assets/images/`
2. Référencez-les : `<img src="assets/images/nom-image.jpg" alt="Description">`

## 📦 Déploiement

### Netlify / Vercel
1. Connectez votre repo Git
2. Déployez automatiquement

### GitHub Pages
1. Pushez sur GitHub
2. Activez GitHub Pages dans Settings
3. Sélectionnez la branche `main`

### Serveur traditionnel
1. Uploadez tous les fichiers via FTP
2. Pointez le domaine vers le dossier

## 🌐 Navigation du Site

```
Accueil (/)
├── Solutions (/fr/solutions/)
│   ├── Agents conversationnels
│   ├── Agents opérationnels
│   └── Systèmes multi-agents
├── Expertise (section #expertise)
├── Intégration (/fr/integration.html)
├── Méthodologie (/fr/methodologie.html)
├── Ressources (/fr/ressources.html)
├── À propos (/fr/a-propos.html)
└── Contact (/fr/contact.html)
```

## 📧 Support

Pour toute question, contactez Novalitix via le formulaire de contact du site.

## 📜 Licence

© 2026 Novalitix. Tous droits réservés.

---

**Dernière mise à jour** : Janvier 2026
**Version** : 1.0.0
