# NOMI-AI.NET — CHECK-UP COMPLET

## ✅ ÉTAT ACTUEL

| Élément | Statut |
|---------|--------|
| Pure HTML + CSS | ✅ (0 JS) |
| Images portrait 3:4 | ✅ Corrigé |
| Meta title/desc | ✅ |
| 13 sections | ✅ |
| 6 images persos | ✅ |
| 10 liens affiliation | ✅ |
| Responsive | ✅ |

## 📁 STRUCTURE DU SITE

```
nomi-ai.net/
├── index.html          ← Page principale (EN)
├── favicon.svg         ← Icône
├── _redirects          ← /go/nomi → affiliation
├── CNAME               ← nomi-ai.net
├── images/
│   ├── Mei-Selfie.webp
│   ├── alice-selfie.webp
│   ├── Clea-Selfie.webp
│   ├── Amber-Selfie.webp
│   ├── 1.28_Sakura.webp
│   └── Brooklyn-Selfie.webp
└── [LANGUES]/          ← À créer
    └── index.html
```

## 🌍 PRÊT POUR TRADUCTION

### Langues recommandées (18 total)
| Code | Langue | Priorité |
|------|--------|----------|
| fr | Français | 🔥 Haute |
| de | Allemand | 🔥 Haute |
| es | Espagnol | 🔥 Haute |
| it | Italien | 🔥 Haute |
| pt | Portugais | 🔥 Haute |
| nl | Néerlandais | ✅ Moyenne |
| pl | Polonais | ✅ Moyenne |
| tr | Turc | ✅ Moyenne |
| ru | Russe | ✅ Moyenne |
| ja | Japonais | ✅ Moyenne |
| ko | Coréen | ✅ Moyenne |
| sv | Suédois | ➕ Optionnel |
| da | Danois | ➕ Optionnel |
| no | Norvégien | ➕ Optionnel |
| fi | Finnois | ➕ Optionnel |
| cs | Tchèque | ➕ Optionnel |
| hu | Hongrois | ➕ Optionnel |
| ro | Roumain | ➕ Optionnel |

### Étapes pour traduire
1. Créer dossier `/xx/` (ex: `/fr/`)
2. Copier `index.html` dans `/xx/index.html`
3. Traduire tout le texte
4. Changer `<html lang="en">` → `<html lang="fr">`
5. Ajouter hreflang dans `<head>`
6. Répéter pour chaque langue

### Balises hreflang à ajouter dans `<head>`
```html
<link rel="alternate" hreflang="en" href="https://nomi-ai.net/" />
<link rel="alternate" hreflang="fr" href="https://nomi-ai.net/fr/" />
<link rel="alternate" hreflang="de" href="https://nomi-ai.net/de/" />
<link rel="alternate" hreflang="x-default" href="https://nomi-ai.net/" />
```

## 📝 CONTENU À TRADUIRE (sections)

1. **Meta** — title, description, keywords
2. **Hero** — badge, title, paragraphs, CTAs
3. **TOC** — titre + 10 liens
4. **Summary** — titre, 3 paragraphes, scores, CTA
5. **Characters** — 6 noms + taglines + descriptions
6. **Comparison** — intro, table headers, 8 lignes, conclusion
7. **Pricing** — 3 plans, features, CTAs
8. **Who** — 6 profils (icon + titre + texte)
9. **Features** — 6 features (icon + titre + texte)
10. **Reviews** — 6 témoignages (texte + auteur + contexte)
11. **How** — titre, sous-titre, 3 étapes, CTA
12. **FAQ** — 5 questions + réponses
13. **Verdict** — titre, 3 paragraphes, badges, CTA, note
14. **Footer** — copyright, lien, disclaimer

## 🔗 LIEN D'AFFILIATION
`/go/nomi` → `https://nomi.ai/?via=nomiai`

## ⚡ PERFORMANCE
- Taille: ~45KB HTML
- 0 requêtes JS
- 6 images (WebP)
- Chargement instantané
