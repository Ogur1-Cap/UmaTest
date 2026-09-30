# Quelle Umamusume es-tu ?

Questionnaire de personnalité animé (fan-made) qui te dit à quel personnage
d'*Umamusume: Pretty Derby* tu ressembles le plus.

**Pour jouer :** ouvre `index.html` dans un navigateur (aucune installation).

## Comment ça marche

- **5 axes de personnalité** (de -2 à +2) : énergie sociale, discipline,
  esprit de compétition, confiance en soi, excentricité.
- **19 personnages**, chacun avec un profil sur ces 5 axes, établi à partir de
  leur caractère dans l'anime et le jeu.
- **14 questions en situation** (« Ton rival vient de te battre… ») plutôt que
  des adjectifs à cocher : on décrit un comportement, pas une qualité
  flatteuse, ce qui limite le biais de désirabilité sociale.
- L'ordre des réponses est mélangé à chaque partie.
- Le résultat = le personnage le plus proche de ton profil (distance
  euclidienne), avec les 3 suivants et la comparaison axe par axe.

Tout tient dans le seul fichier `index.html` (personnages, questions et calcul sont dans le premier bloc `<script>`).
Une simulation a vérifié que les 19 personnages sont atteignables.

*Quiz non officiel. Umamusume: Pretty Derby © Cygames.*
