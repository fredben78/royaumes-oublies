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


Ce petit village poussiéreux de cottages se trouve au milieu de nombreux ranchs de moutons et de bovins, regroupés autour de trois puits profonds. La seule route praticable la relie à l'East Way, au nord. L'odeur des bouses de mouton est omniprésente.

Bospir n'est pas un lieu inspirant à visiter, à moins d'aimer la laine, d'avoir envie d'agneau sur sa table ou de vouloir acheter et vendre des bêtes. L'auberge Drovers Inn est le seul endroit où l'on peut passer la nuit, bien qu'il y ait de nombreuses maisons de chambres qui louent des chambres à la journée. La taverne Nightbleat est régulièrement secouée par des bagarres d'ivrognes, les tondeurs de moutons se défoulant les uns sur les autres. Le nom des Nightbleats est un exemple éclatant de l'humour bospiranais.
