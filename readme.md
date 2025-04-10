# 📋 Installation de `todo` – Gestionnaire de tâches en ligne de commande

Suivez les étapes ci-dessous pour installer et utiliser le gestionnaire de tâches `todo` en ligne de commande.

---

## 1. Cloner le dépôt

```bash
git clone https://github.com/ramzirn/todolist-cli ~/bin/todolist
```

---

## 2. Se rendre dans le dossier du projet

```bash
cd ~/bin/todolist
```

---

## 3. Donner les droits d'exécution au script

```bash
chmod +x todo
```

---

## 4. Ajouter le dossier au `PATH`

Pour pouvoir exécuter `todo` depuis n’importe quel répertoire dans votre terminal :

```bash
nano ~/.bashrc
```

Ajoutez la ligne suivante à la fin du fichier :

```bash
export PATH="$HOME/bin/todolist:$PATH"
```

Enregistrez avec `CTRL + O`, puis quittez avec `CTRL + X`.

---

## 5. Recharger le fichier `.bashrc`

Pour que les modifications prennent effet immédiatement :

```bash
source ~/.bashrc
```

---

## 6. Tester la commande

```bash
todo
```

Vous devriez voir s'afficher l'aide ou l’interface de la commande `todo`.
