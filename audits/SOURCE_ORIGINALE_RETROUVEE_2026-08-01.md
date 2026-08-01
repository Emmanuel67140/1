# SOURCE ORIGINALE RETROUVÉE
## Audit du 1er août 2026

## Dépôt source identifié

Le corpus historique de The Society Group ne se trouvait pas uniquement dans le nouveau dépôt `Emmanuel67140/1`.

La source principale retrouvée est :

`Emmanuel67140/e-cab-service-platform`

Chemin confirmé :

`docs/media-center/bibles/`

## Preuve technique

Commit retrouvé :

`75da579c0b86eb50f36114e8ec102c3f2534e35b`

Message :

`docs(tsg): define historical company identity through 1998`

Fichier confirmé :

`docs/media-center/bibles/BIB-019_IDENTITE_HISTORIQUE_ENTREPRISE_1926_1998.md`

Ce commit confirme que les Bibles de The Society Group étaient bien versionnées dans le dépôt E-CAB SERVICE.

## Conséquence

Les anciens textes, Bibles, chemins d’illustrations et éventuellement les fichiers visuels doivent maintenant être inventoriés directement depuis `Emmanuel67140/e-cab-service-platform`, puis rapatriés progressivement dans `Emmanuel67140/1`.

## Alerte canonique

Le fichier BIB-019 retrouvé contient encore une ancienne version attribuant la période 1951–1982 à Henri Falkenberg. Cette partie est désormais contradictoire avec les corrections validées par Emmanuel concernant Charles-François. Elle doit être classée `À CORRIGER`, pas recopiée aveuglément.

## Plan de récupération

- [x] Dépôt source principal retrouvé.
- [x] Chemin des Bibles retrouvé.
- [x] Premier commit TSG retrouvé.
- [ ] Inventaire de tous les fichiers `docs/media-center/bibles/`.
- [ ] Inventaire de tous les chemins d’illustrations cités dans les Bibles.
- [ ] Recherche des fichiers PNG, JPG, WEBP et SVG associés.
- [ ] Contrôle visuel de chaque illustration.
- [ ] Classement : conserver, adapter, refaire, supprimer.
- [ ] Copie des fichiers conformes vers `Emmanuel67140/1/illustrations/`.
- [ ] Mise à jour du registre maître des illustrations.
