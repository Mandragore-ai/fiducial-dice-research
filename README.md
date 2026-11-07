# Dés à fiducials capacitifs

![Logo](assets/logo.svg)

[Mandragore.ai](https://mandragore.ai) · Maitresinh@500nuancesdegeek.fr

Cette recherche est publiée pour que d'autres puissent reproduire les prototypes
et partager leurs mesures. Si vous poursuivez les essais, nous serions heureux
de recevoir vos données, y compris les échecs, avec le modèle exact, l'appareil,
le protocole et les résultats bruts ou agrégés. Contactez-nous avant toute
publication ou exploitation commerciale commune.

**Licence :** [CC BY-NC 4.0](LICENSE.md) pour nos modèles, images, documents et
données. Attribution requise ; usage commercial sur accord séparé.

## Contenu

Deux tailles de chaque dé, en 3MF individuel : D6 (34/40 mm), D8 (34/40 mm),
D12 (46/54 mm), D20 (62/72 mm), plus deux plateaux Bambu et les cartes de faces.
Ces cotes sont les encombrements entre sommets, pas la largeur des faces.
Les formes conductrices Itsy sont reliées à un noyau interne et doivent être
touchées sur une autre face pendant la lecture. Les chiffres visibles en haut
sont la valeur à enregistrer ; le fiducial est celui de la face posée.

Ouvrir `models/01_REFERENCE_VERIFIEE_BAMBU.3mf` dans Bambu Studio. Filaments :
TPU aux arêtes, PLA isolant, Protoplasta conducteur. Vérifier l'affectation des
filaments avant impression. Voir [le protocole](docs/LIRE_AVANT_IMPRESSION_ET_TEST.txt),
[le catalogue](docs/catalogue.csv) et les cartes dans `docs/face-maps/`.

## État et limites

Géométrie et tranchage préparés ; aucun de ces dés V18 n'est ici validé par un
essai physique indépendant. Les petites formes peuvent ne pas être résolues
par un téléphone courant. Ce dépôt ne mesure pas la reconnaissance d'un D20.
Un objet posé sans main peut ne pas créer de contact suffisant.

## Référence

L'approche des formes capacitives s'inspire de la recherche
[Itsy Bits](https://github.com/Telecooperation/itsy-bits). Les fichiers 3D ici
sont les modèles Mandragore ; aucun code tiers n'est redistribué.
