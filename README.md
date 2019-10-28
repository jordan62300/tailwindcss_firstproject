# Installation tailwindcss

> npm init

> npm i tailwindcss

# Config

[tailwindcss](https://tailwindcss.com/docs/installation/)

- Dans package.json 

```JSON
 "scripts": {
    "build:css": "tailwind build src/style.css -o dist/style.css"
  },
```

Puis faire la commande pour executer le script

> npm run build:css

Creer son fichier de config tailwindcss (optionnel)

> npx tailwind init