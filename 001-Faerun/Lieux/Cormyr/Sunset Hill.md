---
Type:
  - village
regions:
  - Cormyr
Campagne: faerun
tags:
  - lieu
Population: 1000
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

La colline du coucher du soleil doit son nom à sa teinte dorée au coucher du soleil, lorsqu'elle retient la lumière du soleil couchant longtemps après les terres basses qui l'entourent. Cette haute colline herbeuse, située à l'est de [[Bospir]], est un endroit naturel pour une forteresse, mais sa couronne n'abrite que des moutons, bien que des gibbets se soient longtemps dressés sur la colline.

Il n'est pas surprenant que Sunset Hill soit hanté. Certaines nuits, des apparitions fantomatiques de cadavres humains flottants, à la verticale et à la tête pendante se produisent au sommet de la colline. La tradition paysanne locale veut que les moutons qui se trouvent sur la colline à ces moments-là se transforment en monstres aux ailes de cuir, appelés "dark horrors" (horreurs sombres). Les horreurs sombres s'envolent pour attaquer les personnes seules et le bétail dans toute la campagne, et se transforment à nouveau en moutons ahuris le matin, s'ils survivent aussi longtemps.

L'eau est abondante au pied de la colline. Pas moins de trois étangs sont disséminés, alimentés par des sources qui jaillissent au cœur de la colline. De nombreux cottages s'agglutinent autour des étangs, si bien que SunSet Hill pourrait être considéré comme une colonie - un hameau éloigné sans centre ni gouverneur - d'environ 1 000 personnes.
