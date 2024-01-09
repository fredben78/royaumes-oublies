---
Type: 
regions: 
Campagne: faerun
tags:
  - PNJ
Alignement: 
Race: 
Sexe: 
Classe: 
niveau:
---


<% tp.file.title %>
<% await tp.file.move("/001-Faerun/PNJ/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewNPC");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Saisir le nom de votre PNJ");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>


> [!infobox]
> # `=this.file.name`
> ![[not-found.webp|cover hsmall]]
> [[ImagePlaceholder.png|Show To Players]]
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Home | `=this.Location` |
> Group | `=this.AssociatedGroup` |
> Sex | `=this.gender` |
> Race | `=this.race` |
> Age | `=this.age` |
> Condition | Healthy |
> ###### Rules Info
> Type |  Stat |
> ---|---|
> Alignment | `=this.alignment` |
> Class | `=this.class` |
> Character Role | `=this.character-role` |


# `=this.file.name`
## Description






