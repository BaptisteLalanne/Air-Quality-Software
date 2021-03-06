# Génie Logiciel - 3IF
### _Fait par Arthur ROSSELLO-POULET, Rami EL RIFAI, Capucine BOIS, Baptiste LALANNE_




Dans le cadre du projet en Génie Logiciel, nous développons deux fonctionnalités d'un programme d'analyse de la pollution de l'air.

Fonctionnalités retenues pour ce code:
- Vérification des capteurs
- Calculer indice ATMO dans une région et une période donnée


## Utilisation du programme

```sh
make run
```

Par défaut le makefile prend un fichier avec les différents csv requis dans le dossier actuel "$(PWD)/dataset"

Différentes commandes sont utilisables dans le make:
- clean
- mproper
- debug (Valgrind)


## Utilisation des tests

***Pour utiliser les tests, il faut au préalable créer l'executable (via make par exemple) et avoir les droits sur les fichiers***
```sh
make
cd Tests/TestsFichiers
bash mktest.sh
```
Pour observer la validation des tests unitaires et de bout en bout, il est possible d'ouvrir le .csv crée ou tout simplement observé le passage des tests sur le terminal.


**Pour les tests unitaires**
```bash
make runTest
```
> Note: make compile par default l'executable airwatcher et test

## *Versions*
Il y a peu de version car nous utilisons un IDE (CLion de JetBrains) pour coder en direct sur une même session. Nous faisons donc un commit par séance plutôt que un commit par features ou debug.
