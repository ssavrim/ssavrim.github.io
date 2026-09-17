# Base éditoriale du CV

Cette arborescence sépare les faits professionnels de leur présentation.

## Fichiers

- [`final.en.md`](final.en.md) et [`final.fr.md`](final.fr.md) : versions Markdown complètes des CV publiés en anglais et en français.
- [`base.md`](base.md) : source de vérité commune — parcours, expériences, technologies, formation et langues.
- [`profiles/general.md`](profiles/general.md) : positionnement général pour les candidatures spontanées.
- [`profiles/datadome.md`](profiles/datadome.md) : variante ciblée pour le poste Software Engineer — Integrations chez DataDome.

## Règles de maintenance

1. Une expérience ou une compétence factuelle est ajoutée d'abord dans `base.md`.
2. Un profil ciblé ne doit jamais introduire un fait absent de la base.
3. Un profil peut sélectionner, reformuler et réordonner les faits selon la cible.
4. Les pages HTML et les fichiers `final.*.md` présentent le CV publié et doivent rester synchronisés ; à terme, ils pourront être générés depuis cette base.
