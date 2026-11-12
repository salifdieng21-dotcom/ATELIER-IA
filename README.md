# Atelier — plateforme vidéo multi-agents

Prototype (`prototype.html`) + base de données Supabase (schéma `atelier`, projet youtube-ai-studio).

## Base de données
Tables : brands, projects, scripts, publications, comments. RLS activée : chaque utilisateur ne voit que ses lignes.
Le schéma `atelier` doit être ajouté à Supabase > Settings > API > Exposed schemas pour être utilisable via l’API.

## État honnête
- Fait : prototype d’interface, scripts IA, sous-titres SRT, schéma de base de données sécurisé.
- À faire : application Next.js, authentification, connexion YouTube (OAuth), service de rendu vidéo, publication.

## Déposer sur GitHub
```
git init && git add . && git commit -m "Atelier: prototype + schéma Supabase"
gh repo create atelier-video-agents --private --source=. --push
```
