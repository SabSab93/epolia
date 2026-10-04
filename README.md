# Epolia

Repository transversal de pilotage du projet **Epolia**.

Ce repository ne contient pas le code applicatif du backend, du frontend ou de la documentation technique. Il sert de point central pour le **pilotage projet**, l'agrégation des données GitHub et le futur **dashboard de suivi des sprints**.

## Repositories du projet

- `epolia-back` — API, logique métier, Prisma et PostgreSQL.
- `epolia-front` — application Epolia Android/iOS.
- `epolia-doc` — documentation technique Docusaurus.
- `epolia` — pilotage transversal et dashboard.

## Organisation du travail

Le suivi global est réalisé dans le **GitHub Project Epolia**.

- **Sprint** : itération de 2 semaines, transversale aux repositories.
- **Milestone** : objectif fonctionnel ou technique.
- **Issue** : unité de travail concrète, créée dans le repository concerné.
- **Status** : Todo, In Progress, Review, Done.
- **Pull Request** : implémentation et revue du travail.

Un sprint peut donc contenir simultanément des issues Backend, Frontend et Documentation.

## Sprints

Les sprints ne sont pas représentés par des issues dans ce repository. Ils sont gérés par le champ **Iteration / Sprint** du GitHub Project Epolia.

Le dashboard de pilotage pourra exploiter les données de GitHub afin de suivre notamment la progression des sprints, les issues terminées, la vélocité, les milestones et les Pull Requests.

## Architecture des repositories

```text
GitHub Project Epolia
        |
        +-- epolia-back
        +-- epolia-front
        +-- epolia-doc
        |
        +-- Sprint / Status / pilotage global

epolia
        |
        +-- dashboard
        +-- scripts d'agrégation GitHub
        +-- pilotage projet
```
