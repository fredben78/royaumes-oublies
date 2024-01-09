---
Type:
  - village
regions:
  - Cormyr
Campagne: faerun
tags:
  - lieu
Population: 
Force-armee: 
Nobles-locaux: 
Marchands-locaux: 
Temple-majeur: 
Lord: 
Herald:
---

> [!infobox]
> # `=this.file.name`
> ![[not-found.webp|cover hsmall]]
> [[not-found.webp|Show To Players]]
> ###### Basic Information
> Type |  Nom |
> ---|---|
> Régions | `=this.regions`|
> Nom | `=this.file.name ` |
> Population | `=this.Population` hab |
> Temple-majeur | `=this.Temple-majeur` |
> Lord | `=this.Lord` |
> Forces armées | `=this.Force-armee` |
> Nobles-locaux | `=this.Nobles-locaux ` |
> **PNJ Importants**
>  ```dataview
list FROM outgoing([[]])
where contains(tags, "PNJ")
sort type ASC
>```
> **Familles Nobles**
> ```dataview
list FROM outgoing([[]])
where contains(tags, "Famille")
sort type ASC
>```


Le Rocher du Rêveur est un point de repère sur le côté nord de la Voie de la Manticore. Cette longue colline au sommet plat se termine par une falaise orientée vers le sud et abrite un petit hameau des pires tempêtes lacustres. Les habitants vivent de l'élevage de moutons, de la culture de petites parcelles de légumes qu'ils entourent de fossés remplis de piquets pour tenir à distance les cerfs et autres prédateurs, et du creusement de petites grottes sous le vent du Rocher du Rêveur pour extraire le cuivre tendre de sa roche.

De temps en temps, ces grottes peu profondes sont utilisées par des bêtes que les habitants tuent pour se nourrir ou pour se débarrasser de leurs prédateurs. Les grottes sont également utilisées par les hors-la-loi en fuite, les voyageurs surpris par le mauvais temps et les contrebandiers. Les contrebandiers paient souvent

Les contrebandiers paient souvent généreusement les habitants pour l'utilisation d'une grotte privée, mais ils assassinent parfois les habitants qu'ils ont payés plus tard pour faire taire toute possibilité de trahison.

La plupart des habitants n'ont ni les compétences ni les moyens de travailler le cuivre et de le vendre aux marchands de passage sous forme de morceaux. Pour un habitant de Dreamer's Rock, une pièce d'or représente beaucoup d'argent. Certains ne voient pas plus de 5 gp en une année.

Le rocher doit son nom au mystique elfique Ilyndrathyl le Rêveur, qui l'utilisait il y a bien longtemps. On l'a souvent vu léviter au-dessus de son sommet, s'asseoir sur l'air vide et faire face à la fureur d'une tempête marine tout en ignorant ses hurlements. Pendant ces méditations, on dit que son esprit parcourt les coins les plus reculés de Faerûn et les plans les plus éloignés. Il disparut un après-midi dans une explosion de flammes en plein vol. Les habitants pensent qu'une chose maléfique s'est aperçue qu'il l'observait et l'a détruit en toute décontraction.