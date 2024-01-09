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


Ce hameau doit son nom à la colline couronnée d'un château en ruine qui s'élève à l'ouest de la rivière Darkflow, juste au sud de la Voie de la Manticore. Les raids des monstres du Vast Swamp et les hommes-lézards qui remontent les eaux noires de la Darkflow ont depuis longtemps réduit la population de ce village à quelques robustes cultivateurs de navets et à une seule étable qui se dresse à l'intérieur de sa propre palissade, parmi les ruines surannées de nombreux chalets abandonnés. C'est là que la famille Margar échange des chevaux frais contre des chevaux fatigués ou vend carrément des chevaux aux voyageurs sur la route.

Au fil des ans, plusieurs familles nobles ont eu l'idée de reconstruire le donjon sur la colline pour en faire leur propre maison et une base pour le commerce avec Sembia. Toutes ont renoncé après des expériences désagréables attribuées à des contrebandiers, des cultes sombres ou des morts-vivants. Le château était à l'origine Battlegate, le siège de la famille noble disparue des Auantiver. Le château a la réputation d'être hanté. Des rumeurs récentes prétendent que le Culte du Dragon utilise ses voûtes comme base et fait apparaître des apparitions de dragons fantomatiques à l'aide de sorts inconnus jusqu'à présent, et anime des squelettes et des zombies humains et monstrueux pour empêcher les gens de s'approcher du château.