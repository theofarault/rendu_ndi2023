# NDI - 2023

## Membres du groupe

- [x] 1. Gabriel FERREIRA
- [x] 2. Théo FARAULT
- [x] 3. Bryan CORRET

# Requirements
- Avoir NPM version 20.0.0

## Installation

**Préparation de l'environnement de travail**

```bash
npm create 
```
Mettre le nom du projet 'ndi2023vf' et appuyer sur Enter pour continuer. Une fois cela fait, exécutez les commandes suivantes :
```bash
npm i vite -D
npm i three
npm i github:codeurdenuit/GLTFLoader
npm install bootstrap@5.3.2
npm install jquery
npm i vite -D
```
Il vous faudra modifier le fichier package.json et le remplacer par ceci :

```js
{
  "name": "ndi2023vf",
  "version": "0.0.0",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "serve": "vite preview"
  },
  "dependencies": {
    "three": "^0.132.2"
  },
  "devDependencies": {
    "vite": "^2.6.4"
  }
}
```
Une fois cela fait, vous pouvez lancer le projet avec la commande suivante :

```bash
npm run dev
```
Il y a une petite chose cachée dans le projet, saurez-vous la trouver ? 
Indice : Le code de triche de Konami est caché dans le projet.

(Le code de triche de Konami est : Haut, Haut, Bas, Bas, Gauche, Droite, Gauche, Droite, B, A, Entrée)

Un manifique sapin de noel en 3D est présent dans le projet, il est possible de le faire tourner en utilisant les touches ZQSD ainsi que Ctrl et shift pour la hauteur

il faut scroll jusqu'en bas de la page pour voir le sapin de noel