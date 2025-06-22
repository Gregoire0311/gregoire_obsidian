## ✅ Objectif :

Avoir des messages de commit **clairs, standardisés** et **lisibles automatiquement** (ex : changelogs, CI/CD, etc.)

---
## 📐 Structure standard :

	`<type>(optional scope): <description>`

### 🔹 1. `type` → action du commit

Voici les types les plus courants :

| Type       | Usage                                                        |
| ---------- | ------------------------------------------------------------ |
| `feat`     | Ajout d’une nouvelle fonctionnalité                          |
| `fix`      | Correction d’un bug                                          |
| `docs`     | Changements dans la documentation seulement                  |
| `style`    | Changement de mise en forme (indentation, espaces, etc.)     |
| `refactor` | Refactorisation du code sans ajout ni correction             |
| `perf`     | Amélioration de performance                                  |
| `test`     | Ajout/modification de tests                                  |
| `chore`    | Tâche sans lien direct avec le code (config, dépendances...) |
| `Add`      | Pour ajouter une nouvelle fonctionnalité ou fichier          |
| `Update`   | Pour modifier/améliorer un élément existant                  |
| `Remove`   | Pour supprimer du code, fichiers ou fonctionnalités          |
| `Optimize` | Pour améliorer les performances                              |
| `Document` | Pour des changements dans la documentation                   |
| `Rename`   | Pour renommer un fichier ou une variable                     |
| `Clean`    | Pour retirer du code mort ou faire du ménage                 |

### 🔹 2. `scope` (optionnel) → zone du projet concernée

Exemples : `login`, `API`, `footer`, `form-validation`

### 🔹 3. `description` → phrase courte à l’impératif

---

## 🧠 Exemples réels :

- `feat(auth): add JWT token handling`
    
- `fix(form): prevent crash when email is empty`
    
- `docs(readme): update installation steps`
    
- `refactor(api): split routes into separate files`
    
- `style: reformat code with Prettier`
    
- `chore(deps): update lodash to v4.17.21`