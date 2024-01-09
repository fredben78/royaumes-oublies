---
Type:
  - ville
regions:
  - Cormyr
Campagne: faerun
tags:
  - lieu
Population: 12000
Force-armee: 850 Dragons pourpres, mages de guerre, milice
Nobles-locaux:
  - Huntcrown
  - Rowanmantle
Marchands-locaux:
  - Tanalar
Temple-majeur:
  - Gond
Lord: Alasyn Rowanmantle
Herald: Cuthric Snow
---


> [!infobox]
> # `=this.file.name`
> ![[map-tilverton.jpg|cover hsmall]]
> [[map-tilverton.jpg|Show To Players]]
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

# Cormyr ADD2
# Tilverton et Tilver's Gap

Les Thunder Peaks ont trois cols principaux : Thunder Gap au sud et Shadow Gap et Tilver's Gap au nord. Tilverton, un protectorat du [[Cormyr]] avec une population de 12 000 habitants, se trouve à l'intersection des routes entre Tilver's Gap et Shadow Gap.

Sous Tilverton se trouve un labyrinthe d'égouts assez grand pour qu'on puisse y marcher. Sous la ville se trouvent également les ruines d'une ancienne colonie humaine et elfique qui entourait le donjon de Tilvara, une archisorcière. Aujourd'hui en ruines, le donjon est connu sous le nom de Palais de Tilver.

Les égouts abritent de nombreux voleurs et monstres, y compris de puissants morts-vivants. Un groupe de trolls et une bande de goules dirigée par un "roi" ghast se disputent le contrôle des différents secteurs du réseau d'égouts.

## Commerce

Le principal homme d'affaires de Tilverton est Brieth Tanalar (CN hm F6), éleveur de chevaux et propriétaire d'un ranch. Ses chevaux attirent des clients de loin, mais les acheteurs potentiels doivent d'abord surmonter sa grande méfiance à l'égard des étrangers.

Les autres produits importants de la région sont les fourrures des forêts voisines, les pierres précieuses extraites des montagnes et les poteries.

## Sécurité

**[[Lady Regent Alaslyn Rowanmantle]]** (CG hf F9), cousine de **[[Shaerl Rowanmantle]]** de **[[Shadowdale]]**, dirige le protectorat et supervise un conseil local. Alaslyn est assistée par son héraut, Cuthric Snow (NG hm F2), un jeune homme envoyé par la couronne pour s'assurer que les intérêts des Cormytes sont bien pris en compte.

Tilverton possède une garnison de 850 Dragons Pourpres, qui maintient des patrouilles constantes dans et autour de la ville. En ville, une patrouille typique se compose de 10 à 20 F3 et d'un ou deux sorciers de guerre, commandés par un F5.

Le conflit permanent entre les soldats cormyriens et la seule guilde de voleurs organisée dans une ville cormyte, les Rogues de Tilverton, constitue un véritable casse-tête dans cette région. Les Rogues sont composés de 70 voleurs NE de niveaux 2 à 5 et de 3 à 12 combattants de niveaux 3 à 10.

## Société

La ville frontalière de Tilverton se contente de trois auberges, chacune ayant sa propre clientèle.

La Vengeance de Grimwald est la propriété de la bande d'escrocs de Tilverton, qui l'utilise comme lieu de rencontre pour nouer des liens avec les chefs de caravanes et les aventuriers. On dit qu'elle possède des centaines de compartiments, de pièces et de passages secrets utilisés par les brigands.

La Sorcière Chuchotante est connue pour ses événements étranges. Les quatre personnes qui travaillent à l'auberge sont toutes des Harpistes. Il s'agit des gérantes, les sœurs Aluana Nithrin (CG hf W7) et Jhansabella Nithrin (NG hf W6), du cuisinier Alstigar le Silencieux (NG hm B9) et du maître d'écurie Kheldrar Ghaudelar (LN hm B8).

Il y a aussi une taverne intéressante, The Flagon Held High. Cette taverne ne tente pas d'interdire l'accès aux éléments inférieurs de la société, et ceux qui ont de mauvaises manières parviennent à se tenir tranquilles la plupart du temps lorsqu'ils se trouvent dans cette taverne. En raison de son atmosphère paisible et de sa clientèle variée, The Flagon Held High sert souvent de "lieu neutre" où des personnes de différentes classes sociales peuvent se rencontrer sans attirer l'attention.

## Citoyens remarquables

**[[Andalara]]** (CG hm R9) est une Harper qui voyage avec six combattants demi-elfes. Ils chassent le gibier et tous les maux que les Dragons Pourpres ignorent. Lorsqu'il ne chasse pas, Andalara passe le plus clair de son temps dans la boutique d'armes de son frère, Dundar (CG hm F6).

**[[Hasantasser Bloodshoulder]]** (NG hm T7) dirige Grimwald's Revenge en tant que membre éminent des Rogues de Tilverton. Il a pour hobby d'élever des grenouilles en cage et d'en relâcher une à chaque fois que les Rogues commettent un vol important. **[[Filani de Tantras]]** (N hf W9, S : politique et histoire du Nord de Dragonreach et de Moonsea) vend ses informations mais ne vendra pas d'objets magiques ou ses services magiques. Ses informations sont fiables et le montant offert détermine sa perspicacité.

**[[Artur "le Gros" Grossman]]** (N hm T10) est le chef incontesté des Voyous de Tilverton. **[[Lharae "la Lisse" Grossman ]]**(CG hf T8) est la fille d'Artur qui a usé de ses charmes pour gagner la confiance du clergé gond et de la garnison de Tilverton. De cette position proche du pouvoir, elle a fourni des informations à son père et aux Rogues de Tilverton pendant des années.

**[[GAHLAERD MOSSMERE]]** (NG hm W12) est connu pour deux choses : la recherche de nouveaux sorts et le traitement de toute personne de mauvaise réputation qui se présente à lui. Il fait régulièrement affaire avec les Rogues, les aidant avec de la magie et un refuge.

## Religion

Le principal temple de Tilverton est celui du Gond Wonder- bringer, dirigé par Burlan Almaether (N hm P12) et ses 26 prêtres.

Des temples moins importants sont consacrés à Helm, Lathandre, Silvanus et Tymora. Mask et Cyric sont censés être représentés dans des endroits secrets des égouts.

## Histoire

Depuis son occupation en 1357, Tilverton est devenu un point stratégique de plus en plus important pour le [[Cormyr]]. C'est pourquoi la ville a été fortifiée et ses rues pavées. Une garnison de 850 Dragons Pourpres y est stationnée, et les patrouilles à pied sont fréquentes dans les rues.

Tilverton a été occupé à l'origine par le duc Bhereu en raison des "attaques de Lashan of Scardale et de Zhentil Keep contre les intérêts cormytes". En réalité, le [[Cormyr]] a occupé Tilverton avant que ses ennemis n'en aient eu l'occasion. Les Dales et Sembia ont tacitement approuvé l'occupation, mais chacun craint que le [[Cormyr]] ne devienne trop puissant dans cette région.

# Volo's guide to Cormyr

Cette ville de 12 900 habitants, qui connaît une croissance rapide, est encore officiellement un protectorat du Royaume de la Forêt. Elle est dirigée par une noble Cormyréenne, Lady Regent Alasalynn [[Rowanmantle]], et par un Conseil élu localement et nominalement indépendant. Cependant, personne à Faerûn ne s'attend à voir les Cormyrs relâcher volontairement leur emprise sur Tilverton, et la ville dispose d'une garnison permanente de 850 épées du Dragon Pourpre. Ils patrouillent en permanence contre les monstres, les brigands et les forces zhentish.

Une patrouille typique de Dragons Pourpres est composée de 40 guerriers chevronnés commandés par un officier expérimenté. Tous montent des chevaux de guerre de taille moyenne, portent des plaques de champ et manient lances, masses, épées longues, arbalètes et dagues. Ils sont accompagnés d'un à trois sorciers de guerre et de 10 à 20 archers.

Les archers s'entraînent à tirer depuis la selle et portent une armure de cuir. Chacun d'eux possède une épée longue, des dagues de jet, un arc long et quatre carquois contenant chacun 21 flèches de vol. Les sorciers portent chacun un assortiment complet de sorts, plusieurs parchemins et une douzaine de potions de guérison dans des fioles d'acier, mais ils ne sortent pas leurs livres de sorts en patrouille.

Les rues de Tilverton sont surveillées par des patrouilles à pied composées de 10 à 20 dragons pourpres armés de frondes (au lieu d'arcs et de lances) et accompagnés d'un ou deux mages. Ces patrouilles ne sont pas accompagnées d'archers, mais 26 d'entre eux sont toujours disponibles à l'une des trois portes de la ville.

Lorsque Tilverton est menacé par une attaque en force, le Conseil peut voter l'appel à la milice. (Son effectif maximum est de 470 membres, dont des aventuriers locaux, des trappeurs et des chasseurs qui connaissent bien la campagne. La milice est formée à l'équitation et aux armes.

Si tout cela ressemble plus à un camp armé qu'à une colonie, ce n'est pas faux. Tilverton est la base armée de Cormyrs dans le nord-est, protégeant le royaume des forêts contre les raids de toutes sortes d'ennemis. Tilverton est mis en péril par les brigands de Tilverton, un groupe mystérieux connu sous le nom de Couteaux de feu, et des agents zhent de l'intérieur, et menacé par des hordes d'[[orcs]], des monstres en maraude, de grandes bandes de brigands, des armées zhentilar et des mercenaires à la solde de l'extérieur.

Tilverton a longtemps servi de base aux prospecteurs, aux bûcherons, aux chasseurs et aux explorateurs des régions sauvages environnantes, et a toujours été un centre d'approvisionnement important pour les voyageurs qui empruntaient Tilvers Gap. Aujourd'hui, Tilverton exporte des poteries locales, des pierres précieuses, des fourrures et des chevaux de montagne robustes. Les pierres précieuses sont extraites des montagnes au sud et (surtout) au nord-ouest, et les fourrures proviennent de bêtes piégées dans les forêts avoisinantes. Les chevaux des collines sont des chevaux de guerre de taille moyenne élevés, entraînés et dressés localement. Les bêtes élevées par l'ex-dragon pourpre Brieth Tanalar sont célèbres.

Tilverton est une ville fortifiée à peu près circulaire dont les rues concentriques suivent la forme générale du mur d'enceinte. Ce schéma général est traversé par la Ride de la Lune et de la Mer, qui traverse la ville d'est en ouest. Le schéma concentrique général est également interrompu par la route qui devient la Chevauchée du Nord, qui sort de la ville vers le nord jusqu'à Shadow Gap. Elle rejoint la Chevauchée de la mer de lune sur un marché au centre de la ville. Sur le marché se dresse la Tour du Conseil, un repère utile pour les nouveaux arrivants. Le tiers sud-ouest de la ville s'élève au-dessus du reste et en est séparé par un mur intérieur. Il occupe une butte fortifiée, où se trouve la partie la plus ancienne de la ville, et est accessible depuis le reste de la ville par quatre entrées : trois escaliers et une porte.

Il n'y a pas si longtemps, Tilverton était une petite ville boueuse composée de parcs à bestiaux et de terrains de camping pour caravanes autour d'une colline couronnée de quelques grandes maisons, d'un donjon en ruine et du temple de Gond (alors appelé Gharris House). De vieilles maisons de pierre abîmées et de nombreuses cabanes en bois penchées entouraient les parcs à bestiaux.

C'est alors qu'arriva [[Cormyr]]. Face à l'expansion de l'empire lashan et à la multiplication des raids [[orcs]] et zhentilars, le [[Cormyr]] prit des mesures pour sécuriser Tilvers Gap, envoyant une aide non sollicitée à la ville assiégée sous la forme d'une garnison permanente. Les parcs à bestiaux et les terrains furent démolis en faveur d'une nouvelle construction et relogés à l'extérieur d'une crête et d'un fossé de terre construits à la hâte (qui est maintenant un mur de pierre), les cabanes furent remplacées par de solides bâtiments de pierre, et des Cormyréens opportunistes s'y installèrent par centaines.

Les habitants qui se plaignaient à l'époque d'être piétinés par les bottes d'Azouns se sont largement tus, car l'afflux de soldats, de marchands et d'échanges commerciaux cormyréens les a enrichis et le mur les a (enfin !) protégés contre les brigands et les monstres qui sévissaient. D'autres citoyens, comme Gharri (de Gond), étaient mécontents de la main de fer du duc Bhereu, le cousin de l'anneau [[Azoun IV Obarskyr|Azoun]] qui avait été envoyé pour gouverner la ville, et sont partis. Cependant, peu après la chute de Lashans, Bhereu reprit ses fonctions normales. Une noble Suzailan agitée fut nommée régente, et certains de ceux qui étaient partis revinrent.

Tilverton a toujours été une dangereuse ville frontière d'aventuriers et de magie prête à l'emploi, où les hordes perdues d'aventuriers partis pour une expédition de trop et jamais revenus ont été cachées au fil des ans. Aujourd'hui, c'est une ville animée où les pièces de monnaie s'accumulent rapidement et où la culture est en plein essor. Deux mages importants ont élu domicile à Tilverton : le sage respecté [[FILANI de Tantras]] et [[GAHLAERD MOSSMERE]], un chercheur de nouveaux sorts dont la rumeur dit qu'il aide les Rogues de Tilverton (la guilde des voleurs locale).

Les Rogues sont désormais la seule bande de hors-la-loi locale. Les Zhentarim organisés et les agents du Culte du Dragon ont tous été tués ou chassés. Ces dernières années, les Rogues ont dû faire face à la concurrence des sinistres Couteaux de feu, mais ces derniers ont apparemment tous quitté les lieux ou ont été détruits.

Les Couteaux étaient liés au dieu déchu Moander et habitaient dans les égouts de la ville. Les Rogues habitent maintenant les égouts, et leur groupe compterait plus de 70 voleurs, aidés par les marchands locaux. Ces marchands échappent aux vols les plus importants grâce à leur coopération et aux informations qu'ils fournissent.

Les Rogues sont dirigés par la famille Gross- man depuis des décennies. Actuellement, leur chef est la belle et rusée Lhaerae the Lithe Grossman, fille du célèbre

Artur le Gros (que l'on croit décédé). Lhaerae, qui possède une dextérité et un talent d'actrice incroyables, n'a pas joué de rôle ouvert dans les Rogues jusqu'à récemment. Elle utilisait plutôt sa beauté et son intelligence pour infiltrer le clergé local de Gond, puis la garnison cormyréenne, afin de recueillir des informations pour les Rogues et de s'approprier, à l'occasion, une pièce d'or ou un objet magique.

## Points de repère

Il est peu probable que la plupart des visiteurs de Tilverton croisent la route de Lhaerae et de ses semblables, et ils peuvent donc visiter cette future ville avec circonspection. La partie la plus intéressante de Tilverton est la vieille ville. Dans la vieille ville, il n'y a pas autant de monde qu'ailleurs à Tilverton, et les nouvelles constructions sont interdites, sauf par un vote spécial du conseil. On accède à la vieille ville en empruntant les escaliers du [[Cormyr]], les escaliers du marché, les escaliers de Tilver ou en entrant par la porte de la ville haute.

L'escalier du [[Cormyr]] est situé à l'ouest de la porte du [[Cormyr]]. Il comporte un palier couvert avec un autel des boucliers consacré au dieu Helm. L'escalier du marché relie directement le marché au centre de Tilverton et possède un palier couvert contenant l'autel de la rose, consacré au dieu Lathandre. L'escalier de Tilver, à l'est, mène la rue de la Sorcière à la vieille ville. Il comporte un autel vert entouré d'un jardin, consacré à Silvanus.

Ceux qui n'aiment pas les marches ou les haltes pour se recueillir peuvent emprunter le chemin Gateguard à partir de la rue de la Sorcière et longer le mur de la ville, en entrant dans la vieille ville par la porte de la ville haute, le long du mur sud de la ville. Là, ils peuvent facilement passer devant le sanctuaire de la Main de la Chance de Tymora s'ils ne sont pas de cette confession.

Une fois à l'intérieur de la vieille ville, qui ressemble à un jardin, le visiteur doit jeter un coup d'œil au palais de Tilvers, en ruines, dans le coin nord-ouest des hauteurs qu'occupe ce quartier. Cette ancienne demeure de Tilvara reste intacte en grande partie grâce à son jardin de Medusas, une forêt de personnes et de monstres pétrifiés qui s'animent comme des gargouilles pour attaquer tout intrus. D'étranges lumières magiques dérivent et clignotent à l'intérieur des ruines, et peu de ceux qui y pénètrent survivent à l'idée de revoir l'extérieur des murs en ruine. Un guerrier affirme avoir combattu un fantôme de garde pour regagner son domaine ; il dit avoir également vu des porteurs de visions ou d'autres êtres sphériques aux yeux multiples flotter dans les profondeurs. De puissantes protections empêchent toutes les magies connues de divination et de scrutation de pénétrer dans la ruine.

La prochaine rue à l'est du donjon en ruines, que l'on atteint en empruntant la courte avenue sinueuse de Knights Ride, est le large arc de Gate...

guard Road, qui contourne l'enceinte du donjon dans un virage serré. A l'extérieur (est) de ce virage se trouve la maison de [[FILANI of Tantras|Filani]] la Sage, qu'elle appelle ironiquement la Tour de l'esprit et du travail, et l'ancien site de l'auberge Windlords Rest, aujourd'hui une maison de chambres. Dans l'angle du coude se trouve la Maison du Faiseur de Merveilles, le grand temple de Gond de la ville (anciennement Maison Gharris).

Ceux qui suivent la route de Gateguard en direction de la porte de la ville haute passent devant la nouvelle auberge Windlords Rest. Ils devraient apprécier le fait que son nouvel emplacement l'isole au maximum de l'agitation de Tilverton.

La Chevauchée des Chevaliers est également reliée à la Rue de la Sorcière, qui forme une boucle assez torturée à l'intérieur de la Route de Gateguard, de l'Escalier du Marché à l'Escalier de Tilver. L'embranchement en cul-de-sac de Phorns Lane se trouve juste à l'ouest des escaliers de Tilver, et c'est sur cette voie que se trouve le Flagon Held High, la seule taverne de Tilverton, bien que de nombreux chariots de boissons parcourent les rues et les allées chaque nuit. De nombreux visiteurs et citoyens s'y pressent chaque soir pour boire et discuter. À portée de main à l'ouest, dans l'angle de la ville de Tilvert.

boucle de la rue de la Sorcière, se trouve l'auberge Grimwalds Revenge. L'auberge de la Sorcière Chuchotante se trouve sur Haddock Row, la prochaine rue secondaire de la boucle avant que la Chevauchée des Chevaliers ne la croise.

## Lieux d'intérêt à Tilverton
### Temples
#### The House of the Wonderbringer (La Maison du Merveilleux)

Ce grand temple dédié au dieu Gond Won- dermaker était autrefois connu sous le nom de
Gharris House. Il a été nommé d'après le grand prêtre Gharri, un ancien de la ville qui fut plus tard seigneur régent avant de disparaître. Elle est aujourd'hui dirigée par le Grand Artificier Burlan Almaether. Burlan dirige plus de 40 prêtres qui conçoivent de nouvelles inventions en l'honneur du dieu. Une innovation récente notable est le robinet à flotteur, dans lequel l'augmentation du niveau de liquide dans une enceinte provoque le déclenchement d'un interrupteur par un objet flottant, généralement pour couper l'arrivée d'eau supplémentaire.

Ce temple attirait de nombreux membres du clergé à l'époque de Gharris. Il était considéré comme un serviteur important de Gond qui avait une relation personnelle avec le dieu. Il y a un grand intérêt à voir comment Burlan Almaether se comporte. Les gens sont impatients de savoir s'il développera lui aussi une relation étroite avec Gond, assurant ainsi la grandeur du temple et la place de Tilverton dans Faerûn.

### Boutiques
#### Dundars Fine Blades
##### Forgeron d'armes et d'outils
💰💰💰💰

Anciennement Dundars Pine Swords, cette boutique a récemment élargi sa gamme de produits pour inclure des haches, des faux et des scies. Dundar est un guerrier compétent qui enseigne aux guerriers l'utilisation des lames à titre onéreux. Sa sœur Andalara s'occupe alors de l'atelier, finissant les lames et fabriquant les fourreaux. Andalara est une ranger et une Harper qui parcourt les régions sauvages des environs avec six guerriers demi-elfes, ramassant du gibier précieux et des bois rares. Son groupe traque également les [[orcs]] et autres démons qui parviennent à échapper aux patrouilles du Dragon Pourpre.

#### Tanalars Fine Mounts
##### Éleveur de chevaux
💰💰💰💰💰

Voici le bureau de Brieth Tanalar, le célèbre éleveur de chevaux local. Ses chevaux sont achetés par des gens venant d'aussi loin que Calimshan pour être utilisés comme chevaux d'équitation, pour les courses et pour l'élevage. Il se méfie des étrangers, et le monde lui semble trop plein de voleurs de chevaux. Il peut se permettre de faire payer ce qu'il veut et de refuser de vendre à des gens qu'il n'apprécie pas. (Les marchands devraient en prendre note.)

#### Facilités de l'Undreir
##### Marchandises d'occasion et clôtures
💰💰💰💰

Cette étroite boutique à l'enseigne discrète se trouve de l'autre côté d'une ruelle du Repos des Vents. C'est le bureau du gros marchand avide Phidalpar Undreir, un mer- chant peu scrupuleux et un marchand de biens d'occasion dont les opérations astucieuses l'ont rendu très riche. Bien qu'il ne fasse pas partie des malfrats, Phidalpar utilise des tactiques similaires. Il a au moins une douzaine de gardes du corps armés de fléchettes et de dagues empoisonnées par le sommeil dans sa boutique ou à proximité. Il est toujours prêt à procurer des objets gênants aux aventuriers ou à les engager pour tel ou tel petit travail simple.

### Tavernes
#### The Flagon Held High
💰💰
🍺🍺🍺🍺

Cet endroit coloré est une sorte de fes- tival permanent. Presque tout le monde à Tilverton, le haut et le bas de l'échelle, vient ici pour acheter des boissons, rire des conteurs de blagues, des danseurs et des mineurs, et faire des commérages. Des escortes professionnelles et des voleurs s'occupent de la foule qui se répand chaque soir dans Phorns Lane, et chaque nuit, des Dragons Pourpres amusés mais vigilants ramènent à leurs auberges les étrangers égarés et abrutis par l'alcool.

Par tradition, la loi regarde souvent ailleurs au Flagon, et l'on peut voir beaucoup de cascades, de gaieté, de bagarres et de flirts amoureux dans cette maison bondée, mais d'une manière ou d'une autre toujours légère. Tout est propre et neuf depuis la récente reconstruction après un incendie, et les caves offrent une aussi bonne sélection de bières que n'importe quelle taverne de premier rang dans tout Faerûn. Ce n'est cependant pas l'endroit idéal pour passer une soirée tranquille.

### Auberges

Tilverton compte plus de quatre douzaines de maisons de chambres, et de nouvelles ouvrent chaque été. En été, elles se remplissent rapidement de chasseurs et de marchands de chevaux. En hiver, elles sont vides, à l'exception des trappeurs, des aventuriers venus tenter leur chance dans les Stonelands, et des soldats en repos qui aimeraient une chambre pour une ou deux parties de dés tranquilles, loin des officiers vigilants. Bien que des cuisines de ruelles commencent à apparaître, servant des soupes et des brioches chaudes aux acheteurs passant dans la rue, les auberges de Tilverton restent ses seuls véritables restaurants. Pour cette raison et par familiarité, la plupart des visiteurs de passage à Tilverton se dirigent toujours vers l'une des trois auberges de la ville.

#### La revanche de Grimwalds
💰💰💰💰
🛏️🛏️🛏️

Le Revenge est la propriété des Rogues de Tilverton, et il leur rapporte un revenu assez régulier. Ils s'en servent pour rencontrer les maîtres des caravanes désireux d'apporter les fournitures nécessaires et pour emporter le butin qui serait trop facilement reconnaissable afin qu'il puisse être vendu ailleurs. Le Revenge est insonorisé et truffé de panneaux et de passages secrets, ce qui permet aux malfrats de voler facilement les clients payants. Attention !

L'auberge doit son nom à la menace de vengeance proférée par le magicien Grimwald à l'encontre de ceux qui auraient transformé une de ses créations, dont la beauté n'a pas été précisée. Il menaçait de transformer ses ennemis en grenouilles et de s'emparer de leurs biens. Les prix de l'auberge sont effectivement élevés, et il y a beaucoup de grenouilles qui sautillent, mais pour autant que je sache, il n'y a pas de cas connu de disparition de clients.

L'auberge est tenue par un voleur jovial, portant un cosh, connu sous le nom de Hasantasser Bloodshoulder. Il garde des grenouilles en cage, et en libère une pour qu'elle se promène lorsque les Rogues réussissent un vol important. Deux grenouilles portant de grandes marques jaunes sur le dos ont des paquets scellés de poussière de disparition collés sur leur ventre, à l'intention des voleurs en détresse.

Mes investigations confirment les rumeurs locales : Tous les poteaux et les rampes de l'auberge se tordent d'une certaine manière pour révéler des niches de rangement pratiques. Chacune d'entre elles contient une dague, une gar- rote, un masque de soie noire et un paquet de poussière de disparition utilisé par les malfrats.

La Vengeance est reliée aux couturières par plusieurs moyens cachés. Je n'aimerais pas être un Dragon Pourpre en train d'attaquer l'endroit, et je dois avouer que je me sentais mal à l'aise en y séjournant en tant qu'invité. Séjourner à Grimwalds Revenge est à vos risques et périls.

#### The Whispering Witch
💰💰💰
🛏️🛏️🛏️

C'est un établissement sombre et douillet où l'on entend souvent des bruits inexpliqués et où des sorts se déclenchent derrière des portes closes. La Sorcière est tenue par deux sœurs qui semblent d'abord assez sinistres, mais je peux être le premier à dire au monde qu'elles ne sont pas des voyous ou des cultistes fous, mais des Harpistes sous couverture !

Aluana et Jhansabella Nithrin sont toutes deux des mages. Leur cuisinier, Alstigar le Silencieux, chauve et barbu, est secrètement un barde, tout comme leur maître d'écurie, Khel- drar Ghaudelar.

#### The Windlords Rest
💰💰💰
🛏️🛏️🛏️

Cette ancienne petite auberge confortable a déménagé dans un labyrinthe d'anciennes maisons et boutiques reliées entre elles par des passages pleins de courants d'air et au sol inégal. Elle est maintenant située près du mur de la ville, à l'endroit le plus au sud de Tilverton. Bien que le personnel se perde parfois dans ce labyrinthe mal éclairé, le Repos est toujours réchauffé par la sagesse et la gentillesse de son propriétaire, l'illusionniste à la retraite Thungor Triblane, un gnome au crâne dégarni mais à la barbe magnifique et aux sourcils hérissés.

Thungor considère ses hôtes comme des membres officieux de sa famille, leur prodiguant conseils, instructions, pantoufles pour les pieds humides, réprimandes et argent de poche comme si les clients étaient ses enfants dévoyés. Cela en irrite plus d'un, mais la plupart l'adorent et deviennent des clients fidèles qui envoient des acomptes pour s'assurer une chambre ou une suite privilégiée et paient même un supplément lorsque Thungor leur remet leur facture après leur séjour.

Thungor a dû déménager le Rest en grande partie parce que l'ancien lieu était trop petit pour accueillir la moitié des clients qui voulaient y séjourner. L'ancien emplacement est maintenant une maison de chambres, Jonstyls Banner, tenue par une ancienne aventurière [[Nains|naine]] infirme. Thungor paie toujours Jonstyl pour qu'elle laisse un espace de salon à deux gnomes timides. Leur seule tâche consiste à conduire les gens qui se présentent à la porte de Jonstyls et s'attendent à voir Thungor au lieu de cela, vers le nouveau Repos du Seigneur des Vents.

```leaflet
id: tilverton-map
image: [[map-tilverton.jpg]]
height: 900px
lat: 50
long: 50
minZoom: 1
maxZoom: 18
defaultZoom: 16
unit: meters
scale: 3
marker: default, 39.983334, -82.983330, [[Note]]
darkMode: false
```

> [!info] 
> ### Tilverton Map Key
>1. La maison du Wonderbringer (temple de Gond Wondermaker ; anciennement Gharris House)
>2. Le repos du seigneur des vents (auberge)
>3. La Tour de l'esprit et du travail ([[FILANI des Tantras|Filani]] le Sage)
>4. le marché (avec la Tour du Conseil en son centre)
>5. Escalier du [[Cormyr]] et autel des boucliers (autel de Helm)
>6. escalier du marché et autel de la rose (autel de Lathandre)
>7. Escalier de Tilver et autel vert (sanctuaire de Silvanus)
>8. Porte de la ville haute et Main de la chance (sanctuaire de Tymora)
>9. Lames fines de Dundars
>10. Sorcière chuchotante (auberge)
>11. The Flagon Held High (taverne)
>12. Jonstyls Banner (maison de chambres)
>13. La Chevauchée des Chevaliers
>14. Rue de la Sorcière
>15. Route de Gateguard
>16. Ruelle Drakar
>17. Ruelle de Phorn
>18. Rangée de l'aiglefin
>19. The Northride
>20. Tanalars Fine Mounts 
>21. Facilités d'Undreir 
>22. La porte de [[Cormyr]]

