# Hub Digital Site 🚀

**Hub Digital Site** est la vitrine numérique d'un projet innovant, pensé pour connecter créativité et technologie. Il incarne une identité moderne, adaptée au marché Africain, et met en avant branding, storytelling et solutions digitales accessibles pour une audience locale et internationale.

## 🌍 Site multilingue

Le site est disponible en **3 langues** :

| Langue   | Code | Sens |
|----------|------|------|
| Français 🇫🇷 | `fr` | LTR |
| English 🇬🇧 | `en` | LTR |
| العربية 🇸🇳 | `ar` | RTL |

- **Détection automatique** de la langue du navigateur
- **Sélecteur de langue** dans la barre de navigation
- **Préférence mémorisée** dans le navigateur (localStorage)
- Support complet du **RTL** (sens de lecture droite → gauche) pour l'arabe

## ✨ Fonctionnalités

- Page vitrine professionnelle complète : hero, services, à propos, processus, projets, témoignages, FAQ, contact, CTA
- Design responsive (mobile / tablette / desktop)
- Menu mobile avec animation
- Animations d'apparition au scroll (`IntersectionObserver`)
- Compteurs de statistiques animés
- FAQ en accordéon
- Formulaire de contact (ouvre le client e-mail)
- Bouton « retour en haut »
- Aucune dépendance externe (HTML + CSS + JS pur)

## 📁 Structure du projet

```
hub-digital-site/
├── index.html              # Page d'accueil
├── assets/
│   ├── css/
│   │   └── style.css       # Styles (design system + responsive + RTL)
│   └── js/
│       ├── i18n.js         # Traductions FR / EN / AR
│       └── main.js         # Logique du site
```

## 🚀 Déploiement sur GitHub Pages

Le site est un site statique : il se déploie directement depuis la branche `main`.

### Adresse du site

```
https://sadibouba938-cloud.github.io/hub-digital-site/
```

### Activation (1 minute)

1. Sur GitHub : **Settings → Pages**
2. **Source** : sélectionnez **Deploy from a branch**
3. **Branch** : `main` / **Folder** : `/ (root)**
4. Cliquez sur **Save**

Le site est alors publié en quelques minutes à l'adresse ci-dessus.

## ✏️ Personnalisation

- **E-mail de contact** : remplacez `contact@hubdigital.com` dans `index.html` et `assets/js/i18n.js`
- **Couleurs** : modifiez les variables CSS en haut de `assets/css/style.css` (`--primary`, `--accent`, …)
- **Contenus** : les textes se trouvent dans `assets/js/i18n.js`
- **Statistiques** : valeurs dans `index.html` (attributs `data-count`)

## 🛠️ Test en local

```bash
python3 -m http.server 8080
# ouvre http://localhost:8080
```

---

© Hub Digital — Tous droits réservés.
