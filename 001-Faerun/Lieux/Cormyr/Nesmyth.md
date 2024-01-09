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


Ce village agricole se trouve au nord-est de [[Marsember]], parmi les collines, sur les terres les plus élevées au nord et à l'est du grand coude de la rivière Starwater, là où la rivière tourne vers le sud pour se jeter dans la mer. Lorsque les pentes couvertes d'arbres autour de Nesmyth ont été déboisées, la terre s'est asséchée. Les fermiers désespérés ont creusé des canaux d'irrigation à partir de la Starwater et ont construit une tour de pompage actionnée par des bœufs, mais l'eau s'est écoulée dans le sol sablonneux et la terre est restée desséchée. Pour colmater le fond des canaux, les villageois ont fait venir des écrevisses de la Wyvernwater, car les carapaces de ces créatures (plus ou moins) comestibles se dissolvent dans une gelée semblable à de la colle.

Cette tactique a fonctionné, mais les écrevisses ont non seulement dévoré la plupart des poissons de la partie inférieure de Starwater, mais elles ont également attiré des anguilles électriques désireuses de s'en nourrir. Ces anguilles ont causé de nombreux décès parmi les villageois. Le Stelk, un arbuste ressemblant à un chou, cultivé à [[Hilp]] comme appât pour les poissons, car toute la vie aquatique semble aimer son goût, s'est avéré neutraliser les rejets des anguilles qui l'avaient mangé pendant sept jours environ. Après la découverte des effets fortuits du stelk, le mage Harhansen de Nesmyth a découvert que l'eau des canaux - et seulement des canaux de Nesmyth - électrisé par les anguilles s'illumine comme un sort de lumière continue lorsqu'elle est versée dans un récipient en verre. Il préconise la vente de jarres lumineuses pour enrichir le village.

Nesmyth est aujourd'hui une communauté en guerre contre elle-même : Une faction de villageois veut vendre des jarres de lumière, une autre veut utiliser le stelk pour neutraliser continuellement les anguilles et rendre les canaux sûrs, et une troisième veut exterminer les anguilles, abandonner les canaux et passer à des cultures adaptées aux sols plus secs, comme la vigne pour la fabrication du vin. Les factions s'opposent violemment et il est conseillé aux visiteurs de ne pas se rendre à Nesmyth s'ils n'ont pas d'affaires urgentes à y régler. Si vous devez vous y rendre, ne parlez pas d'anguilles.
