# Commandes git à retenir

## Init un repo
```bash
git init
```

## Ajouter un fichier modifié ou non
```bash
git add nom-fichier  # ex: git add joueur.java
# ou
git add . # pour tous les derniers fichiers modifié
```

## Faire un commit
```bash
git commit -m "Msg concernant ton comit" # ex: ajout joueur
```

## Ajout sur le repo distant
```bash
git push # ou
git push -u origin main
```

## Verifier l'etat de vos fichiers
```bash
git status
```

## Verifier l'etat de vos commits
```bash
git log # si bcp de logs on sort du terminal avec q
```


# Recuperer un projet distant
## De github sur votre ordi
aller sur [Github](https://github.com) copier l'url du https et ensuite taper la commande git clone + l'url
```bash
git clone url
# ex: git clone https://github.com/salamatagoulo/exemple.git
```

## Recuperer les derniers version d'un repo sur votre ordi
```bash
git pull
```