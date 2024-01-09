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

Ce village de pêcheurs isolé doit son nom à un rocher qui abrite l'embouchure de son petit port, un port que les contrebandiers utilisent depuis des siècles pour se guider. Aujourd'hui, c'est un crime d'allumer des lumières sur la pierre. Les sorciers de guerre sont chargés de l'explorer de temps à autre afin d'envoyer une patrouille de dragons pourpres pour intercepter les activités de contrebande ou les navires pirates qui entrent discrètement dans le port du village pour se réparer, échapper aux navires de la marine qui les recherchent ou se réapprovisionner.

Smuggler's Stone est un ensemble de cabanes de pêcheurs qui s'étagent sur les flancs abrupts d'une crique balayée par les tempêtes. Par grand vent, les pilotis qui soutiennent les extrémités maritimes de nombreuses maisons grincent de façon inquiétante. Il existe de nombreuses histoires de butin caché que les pirates ont stocké mais ne sont jamais revenus réclamer ici, et les tunnels et cavernes d'au moins une mine gnome désaffectée se trouvent sous les collines au nord de la communauté, mais il n'y a pas grand-chose à voir et à faire ici pour les honnêtes gens, si ce n'est d'acheter du poisson.

La Pierre, comme l'appellent les habitants de la côte, se trouve à l'est de l'embouchure du Wyvernflow. Il est niché dans l'anse abritée par une pointe orientée vers l'est, à mi-chemin entre l'embouchure de la Wyvernflow et celle de la Mistwater. L'anse est indiquée sur la plupart des cartes, mais Smuggler's Stone n'y figure pas forcément.
