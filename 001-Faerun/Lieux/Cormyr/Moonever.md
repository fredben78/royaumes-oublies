---
Type:
  - village
regions:
  - Cormyr
Campagne: faerun
tags:
  - lieu
Population: 800
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


Ce village de pêcheurs d'environ 800 habitants se trouve sur la rive orientale de la rivière Starwater, juste à l'intérieur des terres, près de l'embouchure de la rivière. Ses habitants fournissent des huîtres à de nombreux villages de l'intérieur. Leurs chariots de glace ruisselants sont un spectacle familier sur les routes côtières du [[Cormyr]].

Moonever abrite Hobble's Hooks (une fabrique d'hameçons), un cordonnier et au moins 20 tisseurs de filets. Sinon, il n'y a rien d'autre à voir ici que des bateaux pourris et des poissons en décomposition.