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


Ce hameau peu connu se trouve au nord de [[Kirinwood]], au milieu des tourbières qui constituent la source de l'Evenbrook, la branche ouest de la rivière Mistwater (la branche est, qui traverse [[Kirinwood]], porte le nom de Kirinar Stream). (Gorthin est un endroit désolé, avec des arbres rabougris, des crêtes rocheuses, de la brume et des buissons de ronces. Des gens simples y vivent de l'élevage de moutons et de la cueillette de baies dans les tourbières.
Méfiez-vous des druides locaux, qui protègent l'intimité de la communauté en lançant des sorts d'épines ou en créant des murs d'épines.

Comme [[Dreamer's rock]], Gorthin est un endroit relativement pauvre. C'est un trou perdu peu fréquenté dont les habitants savent à peine dans quel royaume ils se trouvent et qui est leur roi. L'endroit ne vaut pas la peine d'être visité, même si des rumeurs persistent sur la découverte de pierres précieuses dans les crêtes rocheuses tout autour de Gorthin. Une autre légende veut que Gorthin, qui porte le nom du hameau, ne soit pas un fermier fondateur, mais un ancien roi [[Nains|nain]] dont le tombeau, d'une richesse inouïe, se trouve sous le hameau. Cependant, personne n'en a jamais trouvé la trace.