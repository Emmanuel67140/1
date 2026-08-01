# AUDIT MAÎTRE DES ILLUSTRATIONS AVANT PRODUCTION
## The Society Group — 1er août 2026

## Décision

Aucune production massive des 300+ images ne doit commencer avant :

- l’inventaire complet des briefs existants ;
- la recherche des images finales déjà produites ;
- le contrôle des identités, époques et doublons ;
- la correction des fichiers obsolètes ;
- la complétion des briefs incomplets ;
- la normalisation des noms de fichiers et identifiants.

## Périmètre audité

Source : `Emmanuel67140/e-cab-service-platform`

Branche : `tsg-histoire-1968-1998`

Comparaison effectuée avec `main`.

Résultat technique :

- branche divergente ;
- 1 496 commits d’avance ;
- 127 commits de retard ;
- corpus très volumineux ;
- nombreuses Bibles, chapitres, registres visuels et dossiers d’illustration ;
- aucune preuve globale d’un corpus PNG final correspondant à tous ces briefs.

## Anomalies déjà retrouvées dans le dépôt source

Le dépôt contient déjà des rapports d’anomalie dédiés, notamment :

- `ANOM-002_REGISTRE_ILL000_IDENTITES_ET_PERIMETRE_OBSOLETES.md` ;
- `ANOM-003_DOUBLON_ILL207_DIRECTRICE_POLE_INNOVATION_RD.md` ;
- `ANOM-017_FICHES_CHAR001_CHAR002_CHAR003_MANQUANTES.md` ;
- `ANOM-018_PORTRAITS_MAITRES_DIRIGEANTS_MANQUANTS.md` ;
- `ANOM-019_ILL_HIST_001_ANCIENS_PERSONNAGES_STRUCTURE_INCOMPLETE.md` ;
- `ANOM-020_ILL_HIST_002_ANCIENS_PERSONNAGES_ET_FAMILLE_INVENTEE.md` ;
- `ANOM-021_ILL_HIST_003_ANCIENS_PERSONNAGES_ET_SCENE_SURCHARGEE.md` ;
- `ANOM-023_IDENTIFIANTS_ILLUSTRATIONS_METIERS_DUPLIQUES_215_243.md` ;
- `ANOM-025_CAS_ECOLE_001_006_REECRITS_ET_ILLUSTRATIONS_NORMALISEES.md`.

Ces rapports prouvent que le corpus visuel ne peut pas être produit en série sans nettoyage préalable.

## Principaux risques à corriger

### 1. Identités obsolètes

- anciens dirigeants incorrects ;
- personnages supprimés du canon ;
- filiations incompatibles ;
- portraits maîtres manquants ;
- personnages familiaux non verrouillés.

### 2. Doublons

- identifiants ILL dupliqués ;
- même métier traité plusieurs fois ;
- même personnage réutilisé avec des physiques différents ;
- scènes collectives utilisées à la place d’illustrations individuelles.

### 3. Époques incohérentes

- mauvais nom de l’entreprise ;
- accessoires ou technologies anachroniques ;
- vêtements, bureaux ou machines trop modernes ;
- âge des personnages incohérent avec la date.

### 4. Briefs incomplets

- absence de description physique précise ;
- absence de décor métier ;
- absence d’interdictions ;
- absence de texte alternatif ;
- absence de légende ;
- absence de statut de production.

### 5. Images finales absentes

- plusieurs fichiers `ILL-*.md` sont des dossiers de conception uniquement ;
- certains indiquent explicitement `illustration à produire et auditer` ;
- aucun corpus global de 300+ PNG finaux n’est actuellement démontré.

## Catégories à auditer

### A — Histoire et saga

- HIST-001 à HIST-084 ;
- grandes scènes de crise ;
- successions ;
- acquisitions ;
- implantations internationales ;
- R&D ;
- gouvernance ;
- centenaire.

### B — Métiers

- plus de 300 métiers ou variantes ;
- un métier = un personnage principal = une image ;
- vérification des identifiants dupliqués ;
- vérification des visages, âges, morphologies et origines ;
- suppression des planches collectives comme images finales.

### C — Personnages maîtres

- Alphonce Falkenberg ;
- Charles François Falkenberg ;
- Marc Falkenberg ;
- épouse et quatre enfants de Marc ;
- cadres dirigeants ;
- familles salariées ;
- personnages récurrents.

### D — Cas d’école, crises et projets

- CAS-001 à CAS-006 ;
- CRISE-001 à CRISE-019 ;
- projets industriels ;
- scènes de conseil, CSE, actionnaires et banques.

## Statuts normalisés

Chaque illustration recevra un statut unique :

- `BRIEF_CONFORME_IMAGE_ABSENTE` ;
- `BRIEF_A_CORRIGER` ;
- `IMAGE_EXISTANTE_A_AUDITER` ;
- `IMAGE_CONFORME_A_CONSERVER` ;
- `IMAGE_A_CORRIGER` ;
- `IMAGE_A_REFAIRE` ;
- `DOUBLON_A_SUPPRIMER` ;
- `HORS_CANON_A_ARCHIVER` ;
- `VALIDEE_ET_ENREGISTREE`.

## Ordre de travail obligatoire

1. auditer les Bibles et anomalies existantes ;
2. construire le registre complet des briefs ;
3. résoudre les identifiants dupliqués ;
4. verrouiller les personnages maîtres ;
5. corriger les briefs historiques ;
6. corriger les briefs métiers ;
7. rechercher les images finales déjà existantes ;
8. auditer visuellement les fichiers retrouvés ;
9. produire uniquement les images absentes ou rejetées ;
10. enregistrer chaque image validée dans GitHub ;
11. mettre à jour le statut après chaque lot.

## Contrôle qualité avant validation d’une image

- [ ] identité correcte ;
- [ ] âge cohérent ;
- [ ] visage non réutilisé ;
- [ ] morphologie distincte ;
- [ ] métier ou événement immédiatement compréhensible ;
- [ ] décor cohérent ;
- [ ] époque correcte ;
- [ ] aucun texte faux dans l’image ;
- [ ] aucun chiffre inventé ;
- [ ] aucune marque ou identité erronée ;
- [ ] format paysage ou double page lorsque requis ;
- [ ] légende et texte alternatif présents ;
- [ ] fichier nommé selon la convention canonique ;
- [ ] image réellement visible dans le dépôt.

## Convention de stockage cible

```text
illustrations/
  histoire/
  metiers/
  personnages/
  crises/
  cas-ecole/
  projets/
  archives-rejets/
```

## État d’avancement

- [x] dépôt source retrouvé ;
- [x] branche historique retrouvée ;
- [x] comparaison globale effectuée ;
- [x] anomalies visuelles existantes identifiées ;
- [x] absence de corpus PNG global démontrée ;
- [ ] registre exhaustif des briefs ;
- [ ] résolution des doublons ILL 215–243 ;
- [ ] audit des portraits maîtres ;
- [ ] audit HIST-001 à HIST-084 ;
- [ ] audit complet des métiers ;
- [ ] audit des crises et cas d’école ;
- [ ] production des images manquantes ;
- [ ] dépôt et validation des 300+ fichiers finaux.

## Règle de production

La génération se fera ensuite par lots contrôlés, jamais en masse aveugle. Chaque lot comprendra :

- briefs relus et corrigés ;
- personnages physiquement distincts ;
- génération ;
- audit visuel ;
- correction éventuelle ;
- enregistrement GitHub ;
- mise à jour du registre maître.
