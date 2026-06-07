# BioSentinel Dashboard

Mini site statique prêt pour Vercel.

## Déploiement Vercel

1. Créer un nouveau repository GitHub vide.
2. Pousser ce dossier dans le repository.
3. Dans Vercel, importer le repository.
4. Garder les réglages par défaut :
   - Framework Preset: Other
   - Build Command: vide
   - Output Directory: `.`

Le dashboard sera servi directement à la racine du domaine Vercel.

## Test local

Depuis ce dossier :

```bash
python3 -m http.server 8765 --bind 127.0.0.1
```

Puis ouvrir `http://127.0.0.1:8765/`.
