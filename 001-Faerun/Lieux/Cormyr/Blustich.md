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


Blustich est un petit village situé sur la rive ouest de la Wyvernflow, à l'endroit où le bois de l'Ermite descend jusqu'à la rivière. Ses habitants vivent de la pêche, de la chasse dans les bois et de l'agriculture. Ils sont connus pour leurs danses du vent, qui provoquent des coups de vent suffisamment violents pour faire tomber des noix de caryer des arbres à l'orée du bois, par paniers entiers. Les voyageurs ne trouvent rien d'autre d'intéressant ici.