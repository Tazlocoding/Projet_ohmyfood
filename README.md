Installation de node_module avec la commande npm init
 Installer npm install sass -g
  Aller dans package.json
    pour installer la commande de compilation de sass en css  dans script écrire :
      "compil": "node-sass sass/main.scss public/css/style.css",
      "watch": "node-sass sass/main.scss public/css/style.css -w",
 ensuite la commande "npm compil sass" compilera sass en css
 la commande "npm watch sass" le fera automatiquement pour le rendu navigateur
