# Nouny Kids Landing Page

Landing page one-page statique en francais pour presenter `Nouny Kids` a la fois aux entreprises et aux parents salaries.

## Fichiers

- `index.html` : structure et contenus
- `variante-entreprise.html` : version alternative orientee entreprise-first
- `styles.css` : design responsive desktop + mobile
- `variante-entreprise.css` : surcouche de style pour la variante
- `script.js` : navigation mobile

## Previsualiser en local

Depuis le dossier `nouny-kids-landing-page` :

```bash
python3 -m http.server 8080
```

Puis ouvrir :

```text
http://localhost:8080
```

Pages disponibles :

- originale : `http://localhost:8080/index.html`
- variante entreprise-first : `http://localhost:8080/variante-entreprise.html`

## Hebergement gratuit sur GitHub Pages

1. Creer un repository GitHub, par exemple `nouny-kids-landing-page`
2. Envoyer ces fichiers a la racine du repository
3. Dans GitHub :
   - `Settings`
   - `Pages`
   - `Build and deployment`
   - `Source` = `Deploy from a branch`
   - selectionner la branche principale et le dossier `/ (root)`
4. Recuperer l'URL GitHub Pages generee

## Nom de domaine personnalise

Une fois GitHub Pages actif :

1. Ajouter le domaine personnalise dans `Settings > Pages`
2. Creer l'enregistrement `CNAME` ou les `A records` chez ton registrar
3. Attendre la propagation DNS
4. Activer `Enforce HTTPS`

## Personnalisation rapide

- Remplacer l'emplacement logo dans le hero par ton vrai logo
- Brancher les formulaires sur ton outil de collecte prefere (Formspree, HubSpot, Brevo, Zapier, Google Forms, etc.)
- Remplacer les temoignages placeholders
