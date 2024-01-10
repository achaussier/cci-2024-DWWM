# Cours Markdown

## Formatage de texte

### Mise en forme

Texte au kilomètre.
Mise **en gras**, *en italique* ou ~~barré~~.

Pas de souligné natif, mais <span style="color: red;text-decoration: underline;">on peut le faire en HTML</span>.

Deuxième contenu.

> Ceci est une citation
> Deuxieme contenu
>
> Avec saut de ligne

### Les puces

#### Liste ordonnée
1. Créer un répertoire
   1. Sous élément
   2. Encore un
2. Rentrer dedans
3. ...

#### Listes non ordonnées

- Item 1
- Item 2
  - Sous item
  - ...

## Les liens

- [Github](https://github.com)
- [Mise en forme](#mise-en-forme)
- [Fichier 2](cours2.md)

## Gestion du code

```html
<html>
  <head>
  </head>
  <body>
    <h1>Coucou</h1>
  </body>
</html>
```

La commande `git init` permet d'initialiser un dépot Git.

## Les tableaux

| Commande | Description
| ---  | ---
| `git init` | Initialise un dépot Git
| `git add` | Ajoute des fichiers

## Les images
![Gandalf](./image/gandalf.png)
![Texte alt](https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/f6676c45-72f5-453d-936c-9581ea67a5b3/d5kguwg-78a956c7-7495-484d-9b2a-623f2e123ffe.png/v1/fill/w_900,h_668/rambo_tux_by_mdh3ll_d5kguwg-fullview.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9NjY4IiwicGF0aCI6IlwvZlwvZjY2NzZjNDUtNzJmNS00NTNkLTkzNmMtOTU4MWVhNjdhNWIzXC9kNWtndXdnLTc4YTk1NmM3LTc0OTUtNDg0ZC05YjJhLTYyM2YyZTEyM2ZmZS5wbmciLCJ3aWR0aCI6Ijw9OTAwIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmltYWdlLm9wZXJhdGlvbnMiXX0.vsrzvWXMJlMscNmw5R0YCY-r2G9TGH7OyfkjoGvQgPo)