# 👨‍💻 GMX0X1 !

<div align="center">
  <h1>⚡ Bienvenue dans mon espace</h1>
  <p><b>Ingénieur Numérique | Infrastructure | Tech</b></p>
  <p><i>Ce dépôt est mon point d'ancrage. Il sert de page d'accueil et d'aide-mémoire (Cheat Sheet) personnel pour mon écosystème en ligne de commande.</i></p>
</div>

---

## 🐙 GitHub CLI (`gh`) - L'arsenal rapide
Au lieu d'utiliser le site web, voici comment je gère mes dépôts en CLI.

| Commande | Description |
| :--- | :--- |
| `gh auth login` | Se connecter à son compte GitHub (avec clé SSH). |
| `gh repo create <nom>` | Créer un nouveau dépôt de zéro. (Ajouter `--public` ou `--private`). |
| `gh repo list` | Lister tous mes dépôts existants. |
| `gh repo clone <user>/<repo>` | Cloner un dépôt rapidement. |
| `gh repo delete <nom>` | Supprimer un dépôt (nécessite de confirmer le nom). |
| `gh repo view --web` | Ouvrir le dépôt actuel dans le navigateur web. |

---

## 🌿 Git Classique - Le versioning
Les commandes de base pour sauvegarder le code.

```bash
# 1. Démarrer et configurer
git init                  # Initialiser un dépôt vide dans le dossier actuel
git clone <url>           # Télécharger un projet existant

# 2. Sauvegarder (L'état local)
git status                # Voir les fichiers modifiés/ajoutés
git add .                 # Ajouter TOUS les fichiers modifiés pour le commit
git commit -m "Message"   # Figer l'état du code avec un message clair

# 3. Synchroniser (Avec le serveur distant)
git push -u origin main   # Pousser le code vers GitHub (branche main)
git pull                  # Récupérer les nouveautés depuis GitHub

# 4. Utilitaires
git log --oneline         # Voir l'historique propre et rapide
git branch                # Voir sur quelle branche je suis
```

## 📦 NPM (Node Package Manager) - L'écosystème JS/Astro

Commandes pour gérer les projets web modernes (comme Astro, React, etc.). 
| Commande | Description |
| --- | --- |
| `npm create astro@latest` | Scaffolding : Génère un projet Astro complet. |
| `npm install` (ou `npm i`) | Télécharge toutes les dépendances listées dans `package.json`. À faire après avoir cloné un projet. |
| `npm run dev` | Lance le serveur de développement local (avec Hot-Reload). |
| `npm run build` | Compile le projet en fichiers statiques (HTML/CSS/JS purs) pour la mise en production. |
| `npm run preview` | Simule le serveur de production en local pour tester le résultat du `build`. |
| `npm install <nom-paquet>` | Ajoute une nouvelle librairie au projet. |
