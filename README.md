# SweetFactory 🍬

**Une mini-usine fictive pour découvrir les procédés industriels, l'automatisation et la documentation technique.**

SweetFactory est un projet pédagogique indépendant : il sert de terrain d'entraînement pour apprendre à structurer un projet sur GitHub et présenter une petite ligne automatisée de fabrication de bonbons gélifiés.

> Ce projet est entièrement fictif. Les équipements, scénarios et paramètres sont illustratifs ; ils ne constituent pas des instructions de fabrication alimentaire ni un programme destiné à piloter une installation réelle.

## Documentation du projet

La documentation est organisée comme un carnet de conception :

- **Accueil** : présentation et vue d'ensemble.
- **Procédé** : dosage, mélange, moulage, refroidissement et conditionnement.
- **Équipements** : machines, capteurs et actionneurs proposés.
- **Automatisation** : séquence fonctionnelle et variables de simulation.
- **Journal de bord** : décisions, essais et prochaines étapes.

Le site est construit avec **Jekyll** et le thème **Just the Docs**, dans l'esprit du modèle de documentation du MakerSpace d'Amiens.

## Organisation du dépôt

```text
SweetFactory-Demo/
├── .github/
│   └── workflows/
│       └── pages.yml       # Construction et publication du site
├── docs/
│   ├── _config.yml         # Configuration Jekyll
│   ├── _includes/          # Personnalisation de l'affichage
│   ├── assets/images/      # Illustrations du site
│   ├── index.md            # Accueil
│   ├── procede.md
│   ├── equipements.md
│   ├── automatisation.md
│   ├── journal.md
│   └── Gemfile             # Dépendances du site
├── project/
│   └── README.md           # Sources et fichiers techniques
└── README.md
```

## Consulter le site

Après activation de GitHub Pages avec la source **GitHub Actions** et réussite du premier déploiement, le site sera disponible à l'adresse :

https://dikoums595.github.io/SweetFactory-Demo/

## Contribuer

1. Créer une branche pour une nouvelle fonctionnalité ou une correction.
2. Modifier les pages ou les fichiers concernés.
3. Vérifier le rendu du site.
4. Proposer une Pull Request vers `main`.

Les noms de fichiers doivent rester courts, explicites et sans espaces ni accents.

---

*SweetFactory Demo — apprendre à concevoir, documenter et versionner un système automatisé.*
