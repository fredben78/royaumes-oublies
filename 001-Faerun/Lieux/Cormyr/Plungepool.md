---
Type:
  - Gouffre
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

Demandez à la plupart des Cormyréens combien de rivières traversent la Forêt des Rois et ils vous répondront qu'il n'y en a qu'une, la Starwater. Les forestiers, les [[Elfes]] et quelques Dragons Pourpres savent qu'il existe une deuxième rivière, le Sharragh (prononcé Sh air -a). Elle prend sa source dans les forêts rocheuses à l'est d'[[Espar]], coule vers le sud-est à travers une forêt dense sur plusieurs kilomètres et plonge dans les profondeurs de la terre à Plungepool. Ce puits de calcaire naturel engloutit la rivière Sharragh dans une chute d'eau interminable et spectaculaire dont le grondement ne s'estompe jamais. La brume remplit toujours Plungepool, et un riche jardin de mousses et de plantes toujours trempées tapisse ses parois glissantes et croulantes.

La descente pénible des Sharraghs se termine par une chute libre dans l'obscurité d'une centaine de pieds ou plus à travers l'air supérieur d'une gigantesque caverne naturelle et dans un vaste lac souterrain. Il s'agit du lac Thalmiir, nommé d'après son découvreur, un explorateur et mineur demi-elfe d'[[Immersea]]. La violence des chutes d'eau rend les eaux du lac Thalmiir riches en oxygène.  
Les eaux abritent de nombreux poissons et des champignons aquatiques qui brillent étrangement dans les profondeurs obscures. Des explorateurs récents m'ont dit que le lac Thalmiir se déverse à son tour dans un autre lac plus profond, Daerbraun, plus profond, Daerbraun, qui est pêché par les drows qui habitent une cité souterraine à proximité et qui considèrent Daerbraun comme leur territoire privé.

La plupart des voyageurs ne voient jamais les merveilles de Plungepool, mais c'est l'un des endroits les plus époustouflants que j'aie jamais observés. Attention : Les Stirges habitent les skypines qui poussent en abondance autour des bords humides du puits, et les parois glissantes du puits rendent extrêmement dangereux le fait de descendre pour jeter un coup d'œil ou pour récolter certaines des fleurs et des plantes rares qui poussent ici de manière si prolifique.
