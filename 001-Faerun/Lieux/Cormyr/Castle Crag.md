---
Type:
  - chateau
regions:
  - Cormyr
Campagne: faerun
tags:
  - lieu
Population: 
Force-armee: 500 Dragons pourpres, mages de guerre
Nobles-locaux: 
Marchands-locaux: 
Temple-majeur: 
Lord: Commander Bren Tallsword
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



Situé au centre-nord du [[Cormyr]], Castle Crag est un avant-poste défensif construit pour empêcher les intrus de venir des Stonelands, de l'autre côté du col de Gnoll et à l'extérieur du [[Cormyr]] proprement dit.

Environ 500 membres des Dragons Pourpres et un détachement de Sorciers de Guerre y sont stationnés, sous la direction de Bren Tallsword (LN hm F10). Il est connu pour être un commandant qui privilégie les exercices réguliers et qui n'hésite pas à appliquer l'ordre permanent de tenir à tout prix. Si Castle Crag est attaqué, Tallsword est persuadé que les forces d'[[Arabel]] pourront renforcer sa position ou mettre en déroute toute force d'invasion qui parviendrait à franchir le poste avancé.

Pour s'assurer que les messages d'aide parviennent à [[Arabel]], Tallsword dispose d'un psioniste capable d'établir un contact avec un membre de la garnison des Dragons Pourpres d'[[Arabel]]. Si nécessaire, le psioniste peut transmettre mentalement la demande de renforts à [[Arabel]]. [[Suzail]] étudie ce système et, s'il est suffisamment efficace, la couronne pourrait décider d'engager des psionistes pour transmettre des messages d'un commandant à l'autre dans toutes les parties du royaume.

Cependant, certains membres de [[Suzail]] s'opposent à ce système, craignant que l'introduction officielle de la psionique ne mette en péril le statu quo de l'armée cormyte en introduisant une "arme" qui envenimerait les choses dans les Stonelands et avec Zhentil. Ils soutiennent que la défense de leurs commandants contre les attaques psioniques deviendrait trop coûteuse et entraverait leurs efforts de commandement. Il y a aussi l'éternelle question de la loyauté des psionistes, car si l'un d'entre eux trahissait [[Cormyr]], il pourrait paralyser les forces de [[Cormyr]].