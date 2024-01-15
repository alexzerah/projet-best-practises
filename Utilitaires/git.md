# Git

- [Git](#git)
  - [Tags](#tags)
    - [A quoi servent les tags ?](#a-quoi-servent-les-tags-)
    - [Gestion des tags](#gestion-des-tags)
    - [Lister les tags](#lister-les-tags)
    - [Ajouter un tag](#ajouter-un-tag)


## Tags

### A quoi servent les tags ?

Les tags servent à marquer des points dans l'historique des commits. Ils sont utiles pour marquer des versions (`alpha`, `beta`, `v0.1`, `v1.2.3`...) ou des étapes importantes dans le projet (`release`, `stable`, `wip`...).

### Gestion des tags

### Lister les tags

`git tag`

### Ajouter un tag

```bash
git tag -a v1.0 -m "Version 1.0"`
git push origin v1.0
```
