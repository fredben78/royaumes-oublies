---
Type:
  - village
  - ruine
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

Le village de Zundle, aujourd'hui disparu, n'est marqué que par une pompe et une étable affaissée aux murs ouverts, utilisée par de nombreux voyageurs sur la Voie du Dragon. La pompe et l'étable se trouvent sur le côté ouest de la route, à la limite sud de la forêt des Anneaux.

Je mentionne Zundle pour deux raisons. La première, d'ordre pratique, est la présence de grenats dans les roches de la région. Plus d'un oisif ou d'un pauvre voyageur a passé un jour ou deux à extraire des pierres précieuses des rochers pour les vendre dans la ville voisine de [[Suzail]]. Les chasseurs de gemmes doivent cependant se méfier, car une mimique ou une autre créature capable de se cacher a élu domicile parmi les rochers et a commencé à se nourrir d'humains !

L'autre raison pour laquelle je mentionne Zundle est qu'elle est célèbre - ou infâme - dans la tradition cormyréenne comme étant la demeure légendaire des bouseux à l'esprit ennuyeux. "Une vraie fête de Zundle" est souvent utilisée pour décrire un événement, un dîner ou une affaire désorganisé(e) ou ennuyeux(se). "Il s'est fait remarquer à Zundle" ou "Tous les garçons lui courent après à Zundle" sont des expressions utilisées pour décrire quelqu'un de très sale, ébouriffé ou habillé d'un costume ridicule. Le terme "Êtes-vous sûr de ne pas être originaire de Zundle ?" est utilisé à la place de "Êtes-vous fou ? ?" ou "Vous y croyez ? Eh bien, vous êtes un idiot !"

On pense que les habitants de Zundle étaient un peu lents d'esprit. Le village a été en grande partie détruit après qu'un troll particulièrement intelligent, qui avait appris quelques mots de la langue commune en écoutant les voyageurs qui campaient, a convaincu l'unique sentinelle de Zundle d'éteindre son feu une nuit, parce qu'il lui faisait mal aux yeux. L'idiot serviable s'exécuta, et il fut rapidement envahi par deux douzaines de trolls. Ils ne le tuèrent pas tout à fait dans leur empressement à dévorer le reste du village endormi. Le sentinelle s'enfuit pour raconter son histoire, et la patrouille du Dragon Pourpre qu'il rencontra galopa jusqu'à Zundle juste à temps pour trouver un ancien du village qui racontait obligeamment au troll brillant toutes les cachettes, caves et autres dont il se souvenait, tandis que d'autres trolls s'empressaient de vérifier chacune d'entre elles à tour de rôle.

Des rumeurs ont circulé selon lesquelles, des années plus tard, un prêtre renégat de Waukeen aurait enterré le trésor du temple qu'il avait volé à Westgate dans un enclos zundien, peu avant que les agents du temple qui le poursuivaient ne le rattrapent. Mais, en vérité, cela n'a jamais pu se produire, car après le massacre des trolls, le village de Zundle n'a pas été reconstruit.
