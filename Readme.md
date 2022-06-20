# Projet HTML de fin d'année

## Éditer le projet

Pour éditer le projet, utiliser le site https://gitpod.io en rajoutant la chaîne `gitpod.io#` devant l'URL de votre dépôt Github. Par exemple, pour éditer ce dépôt, il faut utiliser l'URL `gitpod.io#https://github.com/informatiquecsud/projet-html-1gy` (https://gitpod.io#https://github.com/informatiquecsud/projet-html-1gy)


## Ouvrir le terminal sur Gitpod

Pour ouvrir le terminal, cliquez sur **View => Terminal** (Raccourci : `Ctrl + tréma`)

## Collaborer sur le projet dans gitpod

Il est possible de collaborer sur un même projet dans gitpod. Pour ce faire, il suffit de partager votre workspace gitpod avec l'option **Share running workspace** dans le menu de gitpod.

## Lancer le serveur de développement

Pour lancer le serveur de développement permettant de prévisualiser la page, ouvrez un nouveau terminal si nécessaire et tapez la commande

```bash
python -m http.server 8080


Le port TCP 8080 n'est pas libre, vous pouvez essayer d'utiliser un nombre nombre que 8080, tel que 8081, 8000 ou 9000.

## Sauvegarder les modifications dans Github

Une fois les modifications faites sur Github, il faut utiliser les commandes suivantes pour pousser les modificatins sur Github

> **Attention**
> Si votre serveur de développement tourne, le terminal sera bloqué. Il faut soit quitter le serveur de développement avec le raccourci `Ctrl + C` ou démarrer un nouveau terminal pour insérer les commandes.

1. Ajouter les fichiers à la zone de transit. Dans le terminal

    ```bash
    git add .
    ```

2. Committer les fichiers ajoutés

    ```bash
    git commit -m "message de commit indiquant les modifs faites"

3. Envoyer les modifications sur Github

    ```bash
    git push
    ```
