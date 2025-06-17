# Missel-Romain-LaTeX

Ce dépôt contient une transcription complète du **Missel Romain de 2002** en LaTeX, avec mise en page fidèle aux éditions liturgiques officielles. L’objectif est de produire un document typographiquement soigné, modulaire, imprimable, et exploitable en contexte liturgique réel (messe, office, formation…).

## Structure du projet

- `main.tex` : point d’entrée principal, organise les différentes parties du missel.
- `temps-liturgiques/` : contient les fichiers LaTeX de chaque temps (Avent, Noël, Carême, etc.).
- `commun-des-saints/` : formulaires du commun.
- `eucharistie/` : prières eucharistiques, préfaces.
- `annexes/` : textes liturgiques constants (Gloire à Dieu, Credo, bénédictions…).
- `ressources/` : images, polices éventuelles, logos liturgiques, gabarits PDF.
- `build/` : fichiers générés (non versionnés).

## Compilation

Utilise **pdfLaTeX** pour compatibilité maximale avec les packages typographiques (`mathptmx`, `lettrine`, `xcolor`, etc.).

```bash
pdflatex main.tex
