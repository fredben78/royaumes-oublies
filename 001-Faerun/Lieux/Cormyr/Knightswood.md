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


# Volo's guide to Cormyr

Ce paisible hameau boisé s'est développé autour de plusieurs steadings de chevaliers (d'où son nom), mais ne semble pas s'être beaucoup développé. Aujourd'hui, Knightswood se compose d'un pont de bois arqué qui enjambe la rivière Starwater, d'une scierie située à côté, d'un atelier de sculpture sur bois où l'on fabrique et vend des coffres, des tabourets et des chaises, des cottages de forestiers et de l'Old Owlbear, une bonne auberge (bien que rustique).

Les sculpteurs locaux sont autorisés à couper un nombre limité d'arbres de la forêt dans des clairières spécifiques autour de Knightswood. Un cercle local de druides dédiés à Silvanus, le Neuf de Knightswood, veille à ce qu'aucune coupe illégale n'ait lieu. Les efforts continus du cercle ont rendu la forêt autour de Knightswood riche en plantes exotiques, animée par des créatures sylvestres et belle à regarder. On dit qu'ils habitent une maison souterraine à laquelle on accède en descendant dans un énorme arbre creux et qu'ils cultivent des champignons dans une vaste série de cavernes reliées à leur demeure. Ces cavernes sont sinistrement éclairées par des champignons luisants qui poussent parmi les champignons et offrent aux druides plusieurs portes de sortie vers la surface. Les sorties émergent dans les bois tout autour du village.

Les Neuf peuvent être contactés en parlant à Aunglar le meunier ou à son assistant Jaerith. Les Neuf sont tous des vieillards. Ils sont dirigés par [[DRAGUTH ENDROUN]], un homme à la crinière blanche et aux opinions bien arrêtées, qui aime entretenir un air de mystère et qui est connu pour manier un bâton des bois.

Knightswood a vu naître le maître barde Chanthalas, compositeur de la célèbre chanson The Cormytes Boast, que l'on entend dans de nombreuses salles de dégustation et au coin du feu lorsque les bouteilles ont été vidées plusieurs fois. J'ai inclus ses paroles sur une page suivante pour les voyageurs qui ne veulent pas être laissés de côté quand tous les autres braillent les paroles plus ou moins en temps, mais rarement plus ou moins en rythme.

La maison délabrée du maître barde doit en grande partie son état actuel de décrépitude aux efforts des nombreux chercheurs qui ont essayé de trouver sa harpe de charme au cours des 50 hivers écoulés depuis sa mort. Si quelqu'un l'a trouvée, c'est qu'il ou elle l'a emportée et n'a pas été repéré.

Knightswood était également la demeure du sorcier Cauldigurn le Noir, un sorcier de guerre à l'esprit doux, connu pour les sorts de combat qu'il concevait, qui combinaient tous des effets néfastes avec une zone d'obscurité conjurée et qui étaient à l'origine de son surnom. Cauldigurn est mort à Sembia il y a 22 ans, et sa petite maison est vide et sans toit. Les habitants insistent sur le fait que quelque part autour d'elle se trouve une porte invisible menant à sa véritable maison, où se trouvent probablement ses livres de sorts, ses objets magiques et ses richesses. Plusieurs sorciers de guerre ont minutieusement fouillé la chaumière et les bois environnants, mais aucune trace d'un moyen magique d'aller ailleurs ou d'une quelconque magie n'a encore été trouvée.

Le résident actuel le plus célèbre de Knightswood est [[BAERELUS THE BOLD|BAERELUS]] , un satyre vieillissant qui est un expert de l'histoire et des habitudes des êtres de la forêt royale et un confident pour de nombreux jeunes gens. Depuis 60 ans, il donne gratuitement des conseils avisés aux jeunes amoureux, aux fugueurs et aux Cormytes dont les problèmes les troublent profondément.

On peut généralement trouver [[BAERELUS THE BOLD|Baerelus]] près du Vieux Chêne, un vieil arbre énorme et noueux qui se dresse seul dans la première clairière au nord du moulin. On dit qu'il dispose de moyens magiques pour se protéger contre ceux qui lui font du mal ou tentent de le kidnapper. Au Old Owlbear, on raconte souvent qu'il a été drogué avec du vin frelaté, mis en cage et emmené clandestinement à Sembia par des marchands qui voulaient le vendre à un collège d'enseignement à Sel-Gaunt. La deuxième nuit du voyage, les ravisseurs campent près de la forêt de Hullack. Ils s'enfuirent pour sauver leur vie lorsqu'ils allèrent nourrir [[BAERELUS THE BOLD|Baerelus]] et ne trouvèrent aucun signe du vieux satyre. La cage était ouverte et une gargouille en colère les attendait à l'intérieur.

# Lieux d'intérêt à Knightswood
## Magasins
### Moulin d'Aunglars
#### Scierie
💰💰

Ce vieux hangar encombré possède un étang placide, hanté par les canards, et trois petites roues dans son canal de broyage plutôt qu'une seule grande, comme c'est le cas habituellement. C'est là qu'Aunglar, son assistant Jaerith et une demi-douzaine d'aides moins qualifiés découpent le bois en blocs, en planches, en poutres et en longerons. Ce ne sont pas des bûcherons très habiles, mais ils ne font pas payer grand-chose non plus.

## Auberges
### Le vieil ourson
💰💰💰
🍺🍺
🛏️🛏️🛏️

Le Owlbear est vieux, rustique et confortable. C'est un endroit décontracté tenu par des barbes grises dont la tranquillité correspond à leur rythme. Méfiez-vous de leur vin de panais, il est bien plus fort qu'il n'y paraît. Cette auberge n'a rien de spectaculaire et n'est qu'un endroit solide et honnête, idéal pour se reposer et récupérer.



> [!quote] Le bateau du Cormyte
> *Lorsque les Dragons Pourpres ont parcouru les chemins pour la première fois, Swordingant tous les monstres vus,*
*Alors les aventuriers puissants jouaient à Hearten sur cette terre verte.*
>
*Mais maintenant, avec le fermier et le marchand, j'écoute plus pour une paix durable,*
*Et je me sens de plus en plus mal à l'aise*
*To welcome the weapons charter wreath*.
>
**Chorus**
*Et dans ce pays, je me tiendrai fièrement debout jusqu'à mon dernier jour, monsieur.*  
*Car quel que soit le roi ou le commandement, je serai toujours un brave Cormyte, monsieur.*
>
*Maintenant, l'or de Sembian s'empile,*
*Et les hommes montrent le prix de leurs peaux. Mais il y a ici des gens qu'on ne peut pas acheter, quelles que soient les fluctuations de la fortune.*  
*Alors, que tous les dandys se pavanent, fassent n'importe quoi pour les pièces de monnaie qu'on leur lance. Ici, dans cet agréable royaume vert*
*Ill steadfast unbending stay.*
>
**Chorus**
>
*Maintenant, d'autres pays chantent des chansons plus fières, et leur peuple vient se pavaner sur notre chemin. Mais si ces pays sont si exempts de torts, Pourquoi leur peuple s'éloigne-t-il de la maison ?*  
*Oh, beaucoup de vantardises sont des vantardises vides,*
*Et nos cœurs se souviennent de rivages lointains,*
*Mais parmi tous les autres toasts étincelants, il y en a un qui les surpasse tous.*
>
**Chorus**
>
*Et dans le [[Cormyr]], personne ne mourra de faim ou de soif, comme le veut la loi.*  
*Mais de toutes les personnes honnêtes, nous sommes les premiers*
*Pour faire tomber les mauvaises lois et les mauvais ordres. Certains peuvent vivre dans des salles de couche*
>
*Ou portent des pierres précieuses à chaque orteil.*  
*Ces gens-là font des chutes plus grandes et plus graves et trouvent ainsi des rangs plus difficiles à bûcher.*
>
**Chorus**
>
*(Répétez le refrain si la compagnie l'exige. En général, le dernier refrain est chanté une fois, puis une seconde fois à mi-vitesse et à un volume deux fois plus élevé, avec fierté et emphase).*
