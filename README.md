# Online Coaching — programme de sport pour débutants

Site web statique (HTML, CSS, JavaScript) qui propose un programme d'entraînement
hebdomadaire adapté au profil de l'utilisateur, avec des vidéos de démonstration
pour chaque exercice.

## Fonctionnalités

- **Orientation selon le profil** : à partir du genre, du poids et de la taille,
  l'utilisateur est dirigé vers un programme de **prise de masse** ou de **perte de poids**.
- **Planning hebdomadaire** : 5 jours de musculation (2 groupes musculaires par jour),
  une séance de cardio par jour d'entraînement et 2 jours de repos.
- **10 groupes musculaires** (pectoraux, épaules, quadriceps, ischio-jambiers, triceps,
  biceps, dos, abdominaux, avant-bras, mollets) : chaque exercice est accompagné
  d'une vidéo et de consignes étape par étape (bouton « more »).
- **Nutrition** : estimation des besoins caloriques avec l'équation de Harris-Benedict
  et tableau d'aliments (calories, glucides, protéines, lipides pour 100 g).

## Lancer le site

Aucune installation : ouvrir `welcomepage.html` dans un navigateur.

## Structure

```
welcomepage.html          Page d'accueil (formulaire genre / poids / taille)
bulck.html, cut.html      Programmes prise de masse / perte de poids
<muscle>-page/            Une page d'exercices par groupe musculaire + ses vidéos
bulck cardio final/       Séances de cardio du programme prise de masse
cut cardio final/         Séances de cardio du programme perte de poids
```
