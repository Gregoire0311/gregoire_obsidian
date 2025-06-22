## 🚀 Créer une nouvelle branche
```
git checkout master
git pull origin master
git checkout -b nom_de_ta_branche
```
(exemple : ajout-notes-2025-06-22)

## 🚀 Travailler et pousser la branche
```
git add .
git commit -m "Description de tes modifs"
git push origin nom_de_ta_branche
```

## 🚀 Créer la pull request
- Va sur GitHub
- Clique sur **Compare & pull request**
- Crée ta PR
- Merge quand c’est bon

## 🚀 Mettre à jour master local
```
git checkout master
git pull origin master
```

## 🚀 Nettoyer les branches après merge
```
git branch -d nom_de_ta_branche
git push origin --delete nom_de_ta_branche
```

## 💡 Astuce : ignorer .DS_Store
```
echo .DS_Store >> .gitignore
git add .gitignore
git commit -m "Ignore .DS_Store"
git push origin master
```