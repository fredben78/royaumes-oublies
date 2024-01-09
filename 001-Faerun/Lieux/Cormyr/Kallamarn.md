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


Kallamarn, nommé d'après un des premiers colons, est un minuscule village agricole situé sur la rive de la Starwater, au niveau des rapides, au sud-ouest de [[Gladehap]]. Il se compose uniquement d'un groupe de hangars de production autour du chemin de halage où les barges sont promenées au-delà des rapides. On peut le voir de loin grâce aux trépieds utilisés comme ancres par les mariniers.

En fait, il n'y a pas grand-chose d'autre à voir ici, même si les restes d'un verger traînent le long des berges. Ses fruits, les Kallamarn Catsheads, sont d'énormes pommes vertes qui étaient autrefois appréciées sur les marchés de [[Suzail]]. On peut en faire des tartes très acidulées et les cueillir gratuitement, mais les voyageurs sont prévenus que, chaque année, des cueilleurs de pommes sont entraînés dans l'eau par des kelpies ou d'autres menaces fluviales.
