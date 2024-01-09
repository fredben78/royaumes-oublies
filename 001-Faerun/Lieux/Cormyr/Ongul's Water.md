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

Nommée d'après son petit étang, cette communauté occupe une minuscule vallée boisée au nord-ouest du Bois de l'Ermite, où une source jaillit pour remplir un petit lac rond et placide. Le lac s'écoule vers l'ouest dans la Starwater, qui se jette dans une petite île boisée connue sous le nom de Hunters' Isle (île des chasseurs). Un moulin à grains géré par un descendant d'Ongul, un certain Durkin, est la seule industrie d'importance. Les habitants d'Ongul's Water cultivent des légumes et élèvent des canards, et il ne se passe pas grand-chose d'autre. Quelques courageux habitants chassent dans le Bois de l'Ermite et se font même les guides de visiteurs qui ne se doutent pas du peu que ces gens ont vu de la forêt.
