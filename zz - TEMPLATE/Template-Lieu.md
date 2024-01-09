---
Type: 
regions: 
Campagne: faerun
tags:
  - lieu
Temple-majeur: 
Lord: 
Population: 
Force-armee: 
Nobles-locaux: 
Marchands-locaux:
---
<% tp.file.title %>
<% await tp.file.move("/001-Faerun/Lieux/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewLieu");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Saisir le nom de votre Lieu");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>
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

