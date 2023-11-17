# Skull King - Docker

## Sommaire

- [Pré-requis](#pré-requis)
- [Lancement](#lancement)
- [Important](#important)

## Pré-requis

- [Docker](https://www.docker.com/)
- Cloner les deux autres répositories **à la même arborescence que ce répository** (penser à lire les pré-requis également)
    - [Skull King - API](https://github.com/Maximauve/SkullKing-API)
    - [Skull King - Docker](https://github.com/Maximauve/SkullKing-Docker)

## Lancement
```bash
docker-compose up
```
## Important :
Vous remarquerez qu'il existe un dossier `react` et `api`, ces dossiers étaient utilisés à la base pour pouvoir avoir tous nos environnements de dev dockerisés, mais nous avons rencontrés des problèmes d'encodage de fichier liés au fait que nous sommes sur windows, et cela entrainait également des problèmes de performance. \
Nous avons donc décidé de ne pas dockeriser nos environnements de dev, mais nous avons gardé les dossiers au cas où nous voudrions les réutiliser plus tard.
