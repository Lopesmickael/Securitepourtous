# Self-Destructing Cookies

Self-Destructing Cookies est une extension de navigateur qui permets de supprimer les cookies dès la fermeture d’un onglet.

Cela permets d’éviter les nettoyage régulier (on n’y pense jamais), et d’avoir moins de cookies qui trainent.

Il est possible d’exclure des sites de la suppression automatique pour garder sa session ouverte à tout moment.

# 1- Installation de l’extension

L’extension est disponible pour Chrome, Edge, Brave, Firefox et Opera.

Vous pouvez la trouver ici et cliquer en haut à droite sur l’icône de votre navigateur : 

https://add0n.com/self-destructing-cookies.html

L’extension aura cet icône dans la barre de vos extensions : 

[Screenshot1]


Cliquez dessus pour la désactiver : 

[Screenshot2]



Cliquez à nouveau dessus pour l’activer : 

[Screenshot1]



# 2 - Configuration

Cliquez droit sur l’icône de l’extension pour  accéder aux options : 

[Screenshot3]



Vérifiez que “Destroy cookies when tab is closed” est coché.

Pour empêcher certains site de détruire le cookie, allez sur le site en question, par exemple https://app.slack.com, cliquez droit sur l’icône et cliquez sur “Add/Remove this hostname to/from exception list” : 

[Screenshot4]



Cela ajouter le site à la liste des exceptions.

Vous pouvez vérifier les sites ajoutés à la liste exceptions en cliquant dans le menu sur “Options” : 

[Screenshot5]



Cela ouvrira un nouvel onglet qui vous donnera une liste des sites qui ne seront pas concernés par la destruction de cookies : 

Vous pouvez en rajouter ici à la main, en ajoutant une virgule “,” puis le site web, sans “https://” : 

[Screenshot6]



Et enfin de cliquer sur “Save Options”.

## Cas de Gmail

Pour Gmail et Google Workplace, il conviendra d’ajouter plusieurs domains pour ne pas se faire déconnecter, le cookie de Google stockant beaucoup d’informations.

Je vous suggère d’ajouter les sites suivants dans la liste vue précédemment pour bien utiliser les outils Google : 

```jsx
google.com, accounts.google.com, www.google.com, drive.google.com, calendar.google.com, meet.google.com, docs.google.com, admin.google.com, apps.google.com, mail.google.com, gstatic.com, googleusercontent.com, apis.google.com, googleapis.com, play.google.com, 
```

Ainsi, votre liste de cookie reste minimaliste à tout moment que vous fermez vos onglets. Plus besoin de penser à faire le ménage régulièrement.
