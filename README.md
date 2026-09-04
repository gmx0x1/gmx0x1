# 👨‍💻 GMX0X1

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=250&section=header&text=Bienvenue%20dans%20mon%20espace&fontSize=50&animation=fadeIn&fontAlignY=38&desc=Ing%C3%A9nieur%20S%C3%A9curit%C3%A9%20%26%20T%C3%A9l%C3%A9coms&descAlignY=51&descAlign=62" alt="Header" />
</div>

<div align="center">
  <h3>Ingénieur Sécurité & Télécoms</h3>
  <p><i>Ce dépôt est mon point d'ancrage. Il sert de page d'accueil et d'aide-mémoire (Cheat Sheet) personnel pour mon écosystème en ligne de commande.</i></p>

  <p align="center">
    <a href="https://github.com/gmx0x1"><img src="https://github-readme-stats.vercel.app/api?username=gmx0x1&show_icons=true&theme=tokyonight&hide_border=true&title_color=7aa2f7&icon_color=7aa2f7&text_color=c0caf5&bg_color=1a1b26" alt="GitHub Stats" /></a>
    <a href="https://github.com/gmx0x1"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gmx0x1&layout=compact&theme=tokyonight&hide_border=true&title_color=7aa2f7&text_color=c0caf5&bg_color=1a1b26" alt="Top Langs" /></a>
  </p>
</div>

<br>

## 🛠️ Mon Écosystème & Aide-Mémoire

### 🐙 GitHub CLI (`gh`) - L'arsenal rapide
Au lieu d'utiliser le site web, voici comment je gère mes dépôts en CLI :

| Commande | Description |
| :--- | :--- |
| `gh auth login` | Se connecter à son compte GitHub (avec clé SSH). |
| `gh repo create <nom>` | Créer un nouveau dépôt de zéro (`--public` ou `--private`). |
| `gh repo list` | Lister tous mes dépôts existants. |
| `gh repo clone <user>/<repo>` | Cloner un dépôt rapidement. |
| `gh repo delete <nom>` | Supprimer un dépôt (nécessite de confirmer le nom). |
| `gh repo view --web` | Ouvrir le dépôt actuel dans le navigateur web. |

<br>

### 🌿 Git Classique - Le versioning
Les commandes de base pour sauvegarder le code :

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

<br>

### 📦 NPM - L'écosystème Web
Commandes pour gérer les projets web modernes (comme Astro, React, etc.) :

| Commande | Description |
| :--- | :--- |
| `npm create astro@latest` | Scaffolding : Génère un projet Astro complet. |
| `npm i` | Télécharge toutes les dépendances listées dans `package.json`. |
| `npm run dev` | Lance le serveur de développement local (avec Hot-Reload). |
| `npm run build` | Compile le projet en fichiers statiques pour la production. |
| `npm run preview` | Simule le serveur de production en local. |
| `npm i <nom-paquet>` | Ajoute une nouvelle librairie au projet. |
