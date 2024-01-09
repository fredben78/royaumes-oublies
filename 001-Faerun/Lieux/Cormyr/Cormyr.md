---
Source: Cormyr ADD2
Campagne: faerun
JDR: 
Type:
  - Pays
tags:
  - lieu
regions:
  - Cormyr
aliases: 
Temple-majeur: 
Lord: 
Population: 
Force-armee: 
Nobles-locaux: 
Marchands-locaux:
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



# Introduction

Le Cormyr est l'un des royaumes les plus anciens et les plus intéressants des Royaumes oubliés. C'est une terre de fantasy classique, avec un roi fort qui gouverne ses sujets de façon juste et équitable, des nobles qui luttent les uns contre les autres pour les miettes de pouvoir que le roi ne garde pas pour lui, et des compagnies d'aventuriers prêtes à débarrasser les terres dangereuses de monstres féroces pour une petite part du trésor de la couronne. Et il y a de la magie, beaucoup de magie. Ce guide du Cormyr devrait vous permettre de parcourir la Forêt du Roi et les ruelles de [[Suzail]] dans votre esprit. Il devrait également vous aider à mener vos aventures dans le Cormyr ou, si vous jouez, à visualiser ce à quoi ressemble votre monde de campagne.

## A l'aventure dans le Cormyr

Les informations relatives à l'aventure dans le Cormyr intéresseront particulièrement les joueurs. Le roi [[Azoun IV Obarskyr|Azoun IV]], souverain du Cormyr, n'autorise pas les groupes d'individus armés à parcourir son pays à leur guise. Ce serait une invitation à la rébellion. Le roi est particulièrement strict à ce sujet depuis que Gondegal, un renégat, a pris les armes contre le Cormyr et a laissé un large chemin de destruction dans son sillage. Tous ceux qui souhaitent porter les armes dans le Cormyr doivent s'enregistrer auprès de la couronne. Cela fera du jeu de rôle au Cormyr une expérience inhabituelle, surtout si les personnages et les joueurs n'ont pas l'habitude d'une telle pratique. (Assurez-vous que tous les joueurs connaissent les restrictions et les pratiques décrites dans "Les aventuriers et l'aventure" avant que leur groupe ne se déchaîne dans le Cormyr).

## Ce qu'il y a à l'intérieur

Ce guide contient suffisamment d'informations pour qu'un maître de jeu de DUNGEON (DM) et ses joueurs puissent mener une campagne se déroulant au Cormyr. La visite commence par une description de la géographie de base de la nation.
Vient ensuite l'histoire du Cormyr, qui décrit certains des événements marquants du royaume dans le passé. Vous en apprendrez plus sur la rébellion de Gondegal et sur les projets d'expansion du Cormyr. Vient ensuite une description de la vie dans le Cormyr. En parcourant le pays, vos personnages pourront interagir avec les Cormyréens (ou Cormyriens) comme s'ils étaient eux-mêmes des habitants du royaume. Des discussions sur les coutumes cormyriennes, les divertissements et le système juridique sont incluses, juste au cas où les personnages auraient besoin d'en savoir plus.

Le chapitre suivant traite de la classe dirigeante du Cormyr, des différentes familles nobles et des grands seigneurs. Leurs objectifs et les moyens mis en œuvre pour les atteindre peuvent avoir un impact important sur une campagne au Cormyr.

Vient ensuite une description des classes inférieures de la société, les gens du peuple. Il s'agit des fermiers, des artisans et des marchands, tous susceptibles d'avoir des relations avec les personnages.

Le chapitre suivant familiarise les joueurs avec l'armée cormyte, des Dragons Pourpres à la milice locale. Ceux qui pratiquent la magie au Cormyr seront intéressés par le chapitre sur les mages, qui traite du Conseil des mages et des restrictions imposées à ceux qui pratiquent la magie. Ce chapitre décrit également l'attitude des non-mages à l'égard de ceux qui possèdent des talents magiques.

Le dernier chapitre, "Aventuriers et aventures", contient des informations pertinentes qui s'appliquent à tous ceux qui partent à l'aventure dans le Cormyr. Il décrit les chartes des compagnies d'aventuriers ainsi que d'autres informations utiles aux MJ et aux joueurs.

Bonne visite du Cormyr, une terre de haute fantaisie, de riche noblesse et de magie merveilleuse !


# Geography 

```leaflet
map](<```leaflet
id: Cormyr-map
image: [[map-cormir-details.gif]]
height: 900px
width: 100%
lat: 50
long: 50
minZoom: 1
maxZoom: 10
defaultZoom: 9
unit: 50 kilometres
scale: 3
marker: default, 39.983334, -82.983330, [[Note]]
darkMode: false 
```


## Limites et frontières

Le Cormyr, parfois appelé le Pays de la Forêt, est situé entre le royaume désertique d'Anauroch au nord et le Lac des Dragons (lui-même appelé la mare aux dragons) au sud. Il se trouve généralement au nord-ouest de la mer des étoiles déchues. Les Pics du Tonnerre forment la frontière orientale du Cormyr et les Cornes de l'Orage la frontière occidentale. Le Cormyr est relativement sûr, mais les Cormyréens ont mené la croisade contre la horde des Tuigans, et il y a constamment des conflits frontaliers qui requièrent une attention militaire.

## Climat

Le Cormyr est une terre humide et tempérée, qui reçoit des pluies abondantes en été et au printemps et de la neige en abondance en hiver. Ses hivers sont longs et froids et ses étés courts mais chauds. La douceur du printemps et de l'automne donne naissance à de riches forêts verdoyantes qui se parent de splendides couleurs automnales et à des champs de céréales sains qui donnent lieu à d'abondantes récoltes. Le brouillard est fréquent le long de la côte, et il y a souvent des brumes dans les Hautes Landes, qui s'étendent jusqu'au col de [[High Horn]] et aux gorges au nord d'[[Eveningstar]].

## Topographie

Le Cormyr était autrefois très boisé, mais des générations de défrichement et d'agriculture ont réduit la forêt à une région centrale et à une partie orientale connue sous le nom de forêt de Hullack. Les forêts approvisionnent le royaume en bois et en gibier, mais seulement grâce à une réglementation stricte de la couronne. Des créatures monstrueuses errent encore dans la forêt de Hullack, et les Cormyréens ne recherchent du bois et du gibier qu'à sa lisière occidentale. Les parties les plus denses de la forêt restent dangereuses pour tous. Autour des forêts, des milliers de champs et de pâturages constituent le Cormyr.

Plusieurs rivières, petites et grandes, traversent le Cormyr. La plus importante est la Starwater, qui part des montagnes du Stormhorn et se jette dans le lac des dragons à [[Marsember]]. Elle traverse la forêt centrale du Cormyr et est la rivière la plus utilisée du royaume. Trois routes principales la traversent, et la deuxième ville du Cormyr profite du commerce que la rivière favorise. Les deux plans d'eau les plus importants du Cormyr sont le lac des Dragons (également appelé Dragonmere) et le Wyvernwater. Le lac des Dragons forme la frontière sud du Cormyr et offre un accès maritime aux deux plus grandes villes du Cormyr, [[Suzail]] et [[Marsember]]. Le lac est le principal point d'embarquement vers la mer des étoiles déchues, qui mène au reste du monde.

Wyvernwater est un lac intérieur qui a la forme d'une étoile de mer malformée. Quatre grands fleuves - dont deux sont l'Immerflow et le Wyvernflow - se déversent dans ce lac et permettent d'accéder à quatre grandes villes, dont le centre commercial d'[[Arabel]].

Le Cormyr compte deux grandes régions montagneuses : les Pics du Tonnerre et les Cornes de l'Orage. Ces deux chaînes de montagnes servent de frontières pratiques au Cormyr. Les Cormorans, qui s'étendent du sud au nord avant de s'incurver d'ouest en est, coupent le corps principal du Cormyr d'un territoire situé au nord de la chaîne et connu sous le nom de Marches des Gobelins. Bien que le Cormyr revendique les Marches des Gobelins, il est difficile de se rendre dans cette région et d'en revenir, et peu de Cormyréens y vivent.

De violentes tempêtes balayent la région éponyme des Stormhorns. Il n'y a pas de refuge contre les tempêtes, car elles se produisent en toute saison et peuvent se former en quelques instants, même par temps clair. De tels orages ont surgi d'un ciel dégagé, accompagné d'un tonnerre assourdissant, d'éclairs aveuglants et de vents terribles, et se sont éloignés en l'espace d'une demi-journée ou moins.

Des tempêtes terribles assiègent également les Thunder Peaks. Chaque chaîne a son lot d'histoires d'horreur, avec des groupes d'explorateurs décimés par les ravages du ciel.

De nombreuses rumeurs entourent deux endroits mystérieux dans les Thunder Peaks. Le premier est l'ancienne citadelle brûlée de la défunte Marchayn d'Archendale, connue sous le nom de Sorcière Folle des Pics du Tonnerre. L'autre site mystérieux est une grotte que l'on dit être la demeure d'Aubaerus (N hm D16), un disciple de Silvanus qui, parce qu'il passe une grande partie de son temps sous la forme d'un corbeau (dit-on), est connu sous le nom de maître des corbeaux.

## Les marais de la Farzsea et le marais de Tun

Ces deux lieux désolés ne sont pas revendiqués, mais ils sont généralement considérés comme faisant partie du Cormyr en raison de leur proximité.

Les légendes locales disent que les deux marais étaient autrefois le siège d'anciennes civilisations, mais même les [[Elfes]] n'ont aucune trace de l'une ou l'autre de ces civilisations. Néanmoins, de nombreux rapports font état de constructions et de ruines fantastiques situées dans les marais. On parle par exemple de flèches aux formes inhabituelles, faites de verre aussi solide que l'acier. Malheureusement, il n'y a jamais eu d'effort concerté pour explorer les deux marais et répertorier les merveilles qu'ils recèlent, car de toutes les personnes qui se sont aventurées au plus profond des marais, aucune n'est connue pour avoir vécu très longtemps après en être sortie. Les marais abritent de nombreux types de maladies, de fléaux et de pestilences contre lesquels personne ne semble immunisé.

Malgré les dangers, des hommes sans foi ni loi utilisent les marges du marais de Tun comme base pour effectuer des raids sur le commerce de passage. Leur chef est un homme sans scrupules nommé Thaalim Torchtower, dont on dit qu'il dispose d'un réseau d'espions dans tout le Cormyr, qui lui communiquent les horaires de voyage des riches caravanes.

## Marches des Gobelins et Hautes Landes

Les gobelins et leurs alliés régnaient autrefois sur cette région. Leur pouvoir était incontesté, mais cette époque est une histoire vieille de mille ans.

L'empire des gobelins menait de nombreux raids. Ils sont allés jusqu'à [[Suzail]], Asram et Anuria, qu'ils ont détruite en 200 DR. Le bastion gobelin fut finalement vaincu, non par les armes, mais par l'omnipotent Désert d'Anauroch. Il s'est infiltré dans le territoire des gobelins et a détruit leurs terres cultivées. Les gobelins se dispersèrent devant la force du désert et établirent des positions de pouvoir mineures dans ce qui est aujourd'hui les Marches des Gobelins, les Hautes Landes et le Téthyamar, qui fut gagné lors d'une bataille contre les [[Nains]].
Les Marches des Gobelins sont aujourd'hui occupées par des bandes de gobelins nomades et d'autres groupes de raiders demi-humains. Ils attaquent toujours les colonies cormytes, mais ils s'attaquent aussi les uns aux autres sans scrupules. Il n'y a pas d'organisation cohérente parmi eux, ni même un groupe de raiders ou une tribu qui soit significativement plus fort que les autres. [[High Horn]] et [[Castle Crag]] maintiennent les tribus des Marches des Gobelins à l'écart des terres plus riches des Cormytes.

Il existe de nombreuses similitudes entre les Marches des Gobelins et les Hautes Landes. La principale caractéristique est le grand nombre de ruines dans les Hautes Landes. De plus, cette zone est plus difficile à explorer que les Marches des Gobelins, qui sont situées sur un terrain plus clément. En raison de la difficulté de l'exploration, de nombreuses rumeurs circulent sur ce qui se cache dans la partie septentrionale des monts Stormhorn.

Les Zhentarim ont une route commerciale qui traverse les Marches des Gobelins, ce qui les met fréquemment en contact avec les tribus gobelines. Les chefs zhentarims traitent les gobelins de différentes manières, en les engageant (rarement), en les payant (parfois) ou en les tuant (le plus souvent). Les Zhentarim se sont efforcés de recruter les gobelins à long terme. Il a même été question d'une armée gobeline soutenue par les Zhentarim, sous la direction de monstres puissants capables d'impressionner les gobelins pour qu'ils les suivent. Cependant, la structure chaotique des tribus gobelins et la menace omniprésente de l'armée cormyte ont fait échouer toutes ces tentatives.

## HelmLands

Nommée d'après Helm, le dieu considéré comme responsable du maintien de ses avatars en Faerun, cette région est située à l'extrémité est des monts Stormhorn, près du col du Gnoll et de [[Castle Crag]].

Pendant la période des troubles, cette région a été le centre d'activités contre nature, notamment des milliers de puits de goudron qui ont pris vie du jour au lendemain et qui continuent d'affliger la région aujourd'hui, bien qu'à un degré moindre.

En outre, de nombreuses zones de magie sauvage et morte recouvrent les Helmlands. Ces zones se déplacent constamment, faisant de l'exploration des Helmlands une entreprise apparemment aléatoire. Ces phénomènes étranges affectent la magie de manière chaotique. Les sorts ne se comportent pas comme ils le devraient, produisant des résultats inattendus ou nuls. Même les objets enchantés sont sujets à ces poches d'irréalité.

Naturellement, les Cormyréens évitent cette zone. Tout aussi naturellement, les monstres et les êtres immondes s'y sentent chez eux. Les pillards frontaliers utilisent les Helmlands comme base pour attaquer les communautés, les fermes et même la ville d'[[Arabel]]. Les Corbeaux Rouges ont débarrassé la région des monstres à deux reprises, mais un nouvel assortiment de créatures immondes a comblé le vide à chaque fois.

Il ne semble y avoir qu'un seul moyen de mettre fin à ce cycle. La rumeur veut que le magicien [[Vangerdahast Aeiulvana]] travaille à la mise au point d'une méthode permettant d'éliminer les Helmlands du continent. Il existe deux versions de cette rumeur, l'une selon laquelle [[Vangerdahast Aeiulvana]] tente d'éradiquer complètement les Helmlands et l'autre selon laquelle il prévoit de transporter les Helmlands par magie dans un autre endroit, loin du Cormyr. Seul l'avenir nous dira si l'une ou l'autre de ces rumeurs est vraie.

## Bois d'ermite

Situé au sud de [[Wheloon]], ce bois n'a qu'une seule particularité : la rumeur d'une activité fantomatique. Le fantôme est généralement décrit comme un vieil homme vêtu d'une robe grise et portant une lanterne qui produit une lumière bleue peu naturelle.

L'origine et même l'existence de l'esprit font l'objet de nombreuses spéculations. L'explication la plus courante est que le fantôme est l'esprit d'un ermite qui fut le premier habitant des bois, et que sa mort fut le résultat d'une cause terrible et non naturelle, quelque chose qui existe encore quelque part dans les bois. Les personnes qui adhèrent à cette théorie citent le fait que le bois de l'ermite est dépourvu de tout ce qui est intelligent et qui n'est pas un humain stupide. Ils pensent que les non-humains savent instinctivement qu'il ne faut pas construire une habitation dans le bois. Malgré le danger d'une mort non naturelle et la malédiction de marcher la nuit comme un fantôme, les Cormyréens ont beaucoup parcouru la forêt et y ont chassé le gibier sans incident.

## Forêt de Hullack

Cette forêt, qui constituait autrefois la frontière orientale du Cormyr, est une terre primitive qui recèle bien des secrets et des choses invisibles aux yeux des mortels. La civilisation empiète sur elle à un rythme de plus en plus rapide. La demande en bois et en gibier augmente au fur et à mesure que le Cormyr se développe. C'est pourquoi la couronne encourage les compagnies d'aventuriers et autres entités à débarrasser la forêt des monstres et autres êtres (tels que les nombreuses tribus d'[[orcs]] et de gobelins) et à explorer ses régions les plus profondes. Plus vite la forêt sera nettoyée et plus vite les rumeurs de danger seront démenties, plus vite la forêt pourra être utilisée dans toute son étendue. À cette fin, la Couronne a suspendu bon nombre de ses règles de conduite des aventuriers afin d'encourager une participation maximale aux efforts d'élimination des monstres. Une base d'opérations commune pour de telles expéditions est [[Thunderstone]], une petite ville située à la lisière sud de la forêt.

## La Forêt du Roi

Autrefois habitée par les [[Elfes]] et d'autres peuples, la Forêt du Roi est aujourd'hui entièrement habitée par les humains et le gibier. Le chêne, l'érable et le sorbier sont les principaux arbres de la forêt. Il y a peu de sous-bois, et l'âge de la forêt crée de hautes canopées et de beaux décors. Un réseau de routes traverse la forêt, reliant de nombreuses petites villes et fermes.

Si la forêt est si densément peuplée, c'est parce qu'il n'y a pas de menaces naturelles. Les plus grands animaux sont les ours et il n'y a pas de monstres intelligents. La région est très giboyeuse et très appréciée des braconniers. Cependant, la Couronne réprouve fortement cette activité. Toute chasse est interdite et les peines encourues comprennent généralement le travail forcé. C'est l'un des rares endroits du Cormyr où il n'y a pas de ruines ou d'autres attraits pour les aventuriers.

Bienvenue dans une vue de Volo du Cormyr, le royaume légendaire des forêts anciennes, des chevaliers au galop, des gens heureux, des festins qui grondent jusqu'à la tombée de la lune, et des fiers donjons où les fanions brillants flottent dans la brise. Le Cormyr est un endroit que les gens rêvent de visiter, qu'il s'agisse des vallées, de l'effervescence de [[Eauprofonde|Waterdeep]], des ruelles des villes amniennes ou des hautes terres surpeuplées de Vilhon Reach. C'est une terre de chevalerie et de romance, où le trône est détenu par des Obarskyrs en ligne ininterrompue depuis la fondation du royaume, et où des sorciers de guerre toujours vigilants veillent à la sécurité du royaume et du trône.

### Le port d'armes dans le Cormyr

Que ceux qui liront ces conseils pratiques aux voyageurs ne se méprennent pas sur mes intentions : Je n'ai aucune intention de nuire au trône ou au royaume du Cormyr, mais je m'efforce seulement d'éclairer les lecteurs qui pourraient, sans le vouloir, s'aventurer dans des actes illégaux ou des domaines sensibles et, par conséquent, offenser par ignorance.

La vigilance des sorciers de guerre rend nécessaire un ou deux mots d'avertissement : Toute personne transportant un objet clairement considéré comme une arme dans le Cormyr doit se rendre au poste de garde du Dragon Pourpre le plus proche afin de faire inspecter ses armes et de les attacher avec des lacets. Dans ce contexte, une arme est un couteau plus grand qu'une lame de ceinture utilisé pour les repas, ou tout objet qui fait du mal lorsqu'il est brandi et qui ne peut être considéré comme un bâton de voyageur ou un outil de commerçant. Les patrouilles du Dragon Pourpre et les sorciers de guerre de passage sont étonnamment fréquents, et toute personne se présentant armée sera interpellée à moins que ses armes ne soient clairement attachées. Être trouvé avec une arme non attachée - à moins que l'on vienne de défendre sa vie contre un attaquant armé et que des témoins puissent attester que l'on n'a pas dégainé d'abord - est un motif d'arrestation sur-le-champ et une condamnation au moins à la confiscation des biens et à l'expulsion du royaume.

Seules les personnes nommées dans une charte royale d'armes (habituellement vendues aux bandes d'aventuriers pour des sommes importantes), titulaires d'une licence de vente d'armes, capables de prouver leur appartenance aux Dragons Pourpres ou aux sorciers de guerre, ou remplissant d'autres conditions spécifiques, ont le droit de porter des armes dans le royaume. Parmi les autres raisons valables de porter des armes, on peut citer : les personnes de noble naissance cormyréenne, les miliciens, les personnes qui s'entraînent au maniement des armes sous la supervision de leur seigneur local, les personnes qui participent à une chasse approuvée par leur seigneur local, les personnes qui fréquentent temporairement un pavillon de chasse reconnu, ou les personnes qui détiennent un titre de la Couronne. Les Outlanders en visite au Cormyr ne peuvent invoquer que les deux dernières raisons.

Les brefs de la Couronne sont délivrés pour confirmer le droit temporaire de porter des armes. Par exemple, ils peuvent confirmer le statut d'une personne en tant que noble invité du royaume (comme un envoyé en visite d'un autre pays), garde du corps d'un noble invité, ou messager spécial ou agent de la Cour. Ces personnes doivent porter sur elles le bref, un anneau du Dragon pourpre ou un jeton de la Cour. Dans tous les cas, il existe des registres permettant de vérifier la délivrance des brefs, des jetons, des chartes et autres. Les voyageurs qui souhaitent s'armer illégalement dans le Cormyr doivent être de très bons bluffeurs, sinon leur carrière en liberté ne sera pas longue. La vigilance des dragons pourpres et des sorciers de guerre permet au royaume de rester à l'abri du brigandage occasionnel.

### Comment se comporter

Les défenseurs du Cormyr sont diligents et vigilants. Les gens qui cherchent ouvertement à obtenir des informations éveillent les soupçons, ce qui leur vaut souvent une fouille corporelle et un interrogatoire par les Dragons Pourpres soutenus par un ou plusieurs sorciers de guerre. Ma couverture de plusieurs lieux du Cormyr a souffert dans ces pages parce que ma curiosité m'a rendu indésirable. Soyez avertis.

Mais ne restez pas non plus à l'affût. Un tel comportement fait de vous un voleur et un imbécile. Les Cormyréens aiment leur roi et respectent les Dragons Pourpres, mais ils se méfient des nobles puissants et des sorciers de guerre, qui peuvent se montrer un peu autoritaires et obstinés. Le Cormyréen moyen est honnête, sûr de lui et loyal envers son pays. Pour illustrer ce que je veux dire, jetez un coup d'œil aux paroles de la ballade populaire "The Cormyte's Boast" dans l'article sur [[Knightswood]].

Cela ne veut pas dire qu'il n'y a pas de gens qui attachent des lacets dans les nœuds secrets utilisés par les Dragons Pourpres, mais seuls les sorciers capables de lire les pensées par magie peuvent s'en tirer longtemps. La façon habituelle de contacter ces mages obscurs est d'acheter un verre dans une taverne et de laisser voir au tavernier une corde, un cheveu ou une paille attachée autour de votre doigt. On vous sondera secrètement pour s'assurer que vous n'êtes pas un mage et on vous interrogera pour vous forcer à révéler votre statut d'agent de la Couronne. Si l'on estime que vous êtes en sécurité, vous devrez payer une somme d'au moins 500 gp lorsque le contact avec le mage sera enfin établi. Pour ceux qui ne tiennent pas à leurs armes, une solution plus simple consiste à jeter les objets incriminés dans un puits ou une fosse septique et, en cas d'interrogatoire, à prétendre qu'ils ont été volés.

### Mots de passe

Lorsque l'on est pris en flagrant délit d'armement, le plus simple est souvent de se montrer effronté. Faites comme si vous aviez le droit de porter des armes. Dites à la personne qui vous accoste de parler doucement et de marmonner : "Je sers la Couronne !" Ne dites rien de plus, si ce n'est des allusions mystérieuses, jusqu'à ce que vous soyez escorté en présence d'un sorcier de guerre et vous le serez.

En supposant que vous n'affrontiez pas [[Vangerdahast Aeiulvana]] lui-même (auquel cas je crains que votre carrière ne soit, comme on dit, sur le point de s'achever), dites à l'auguste sorcier de guerre que votre nom et votre mission ne sont connus que de [[Vangerdahast Aeiulvana]], et prononcez : " Mes ordres sont de ne vous donner que ce mot de passe " :

- "Nuit rouge", ce à quoi le magicien de guerre répond "Aube grise", ce à quoi vous ajoutez "Et matin plus lumineux !".
- "Le donjon de Thorn tombe", ce à quoi le magicien de guerre répond "Pour toujours" ou "Plus jamais". Si elle (ou il) dit "Pour toujours", vous répondez "Par la grâce des Neuf !" et si elle dit "Plus jamais", vous dites "Comme rêvé".
- "L'épée noire", à laquelle le sorcier de guerre répond "Le bouclier vert", ce à quoi vous répondez "Pour faire la guerre rouge".

Abandonnez l'expression "sept yeux autour du trône" pour indiquer une mission personnelle et top secrète pour le roi. Si un sorcier de guerre vous dit "Étoile brillante !" à n'importe quel moment, répondez instantanément "Mais le puits est sombre !".

### Obtention de licences

Un autre moyen d'éviter les ennuis si vous êtes pris en flagrant délit d'armement est de produire une licence attestant que vous êtes un marchand d'épées cormyréen. Ces licences peuvent être obtenues auprès de n'importe quel seigneur local selon la procédure habituelle, moyennant une taxe de 4 000 gp et un renouvellement annuel de 2 000 gp exigible au prochain Greengrass. Le processus d'approbation implique des enquêtes très lentes et très approfondies sur l'esprit, le passé et les activités actuelles d'une personne par un certain nombre de sorciers de guerre curieux.

Une fausse licence peut également être obtenue auprès de l'homme qui se fait pousser un œil supplémentaire et n'apparaît que les nuits brumeuses au bout de quais aléatoires à [[Marsember]], auprès d'une certaine escorte professionnelle de Suzailan à qui vous devez chuchoter le nom de "Sharanne" lorsque vous êtes en privé, ou auprès d'un homme à tête de serpent dans la salle de dégustation de l'auberge du Serpent du Monde à [[Arabel]] (le Serpent du Monde est un établissement qui ne peut être trouvé que par ceux qui savent comment y pénétrer ; tous les autres entrent dans une taverne délabrée appelée l'Oie sauvage lorsqu'ils franchissent la porte.) Les Dragons Pourpres ont tenté de tuer ou d'appréhender l'homme-serpent à plusieurs reprises, mais celui-ci possède une magie de transposition qui lui permet d'échanger son corps avec celui d'un Beholder !

L'un de ces individus - et probablement d'autres à [[Tilverton]] et [[Wheloon]], ainsi que plusieurs faussaires ambitieux à [[Suzail]] - peut vous délivrer un permis de vente d'armes pour 600 à 900 gp. Négociez astucieusement : ceux qui acceptent de rendre un ou deux services louches à ces vendeurs peuvent obtenir le document qu'ils désirent à un prix très réduit.

Il est également possible d'obtenir un permis de passage pour le transport d'armes en vrac à travers le Cormyr, qui ne sont pas destinées à être utilisées ou vendues dans le royaume. Ce permis coûte généralement 25 gp par coffre ou caisse ; toutes les armes doivent être enfermées dans des conteneurs verrouillés. Les autorités apposent des sceaux d'aluminium estampillés du dragon pourpre sur tous les joints de ces conteneurs. Si ces scellés sont brisés lors du passage d'une autre frontière, l'amende est de 100 gp par conteneur, plus la confiscation de tout ce qu'il contient ! Bien entendu, il est possible d'acheter des scellés de remplacement auprès de nombreux Cormyréens qui ne font pas partie du gouvernement. À [[Marsember]], en particulier, chaque rue semble abriter un ou plusieurs de ces individus moralement aventureux.

Il est à noter que le passage d'armes dans le royaume représente une menace pour la sécurité du Cormyr. Que se passerait-il si un millier de caravanes zhent se présentaient avec des cargaisons d'armes, se rassemblaient dans des endroits défendables du Cormyr, ouvraient leurs armes d'un seul coup et lançaient une attaque sur le Royaume de la Forêt de l'intérieur ? En raison du risque de sécurité que représente le transport d'armes, les patrouilles du Dragon Pourpre et les sorciers de guerre utilisant des sorts d'œil de sorcier surveillent plus ou moins constamment les détenteurs de licences de passage.

Les forgerons du Cormyr doivent eux-mêmes être titulaires d'une licence. Ils doivent également rendre compte de l'utilisation du métal qu'ils se procurent afin de s'assurer que des armes ne sont pas fabriquées clandestinement à l'intérieur des frontières du royaume et cachées pour être utilisées par des brigands, des rebelles ou des agents loyaux à un autre pays qui pénètrent dans le Royaume des Forêts. Les candidats à la licence de forgeron doivent prouver qu'ils résident dans le Cormyr, demander le parrainage d'un seigneur local, qui enverra régulièrement des patrouilles du Dragon Pourpre pour vérifier les allées et venues du forgeron, et payer 600 gp par an. Les frais de la première année doivent être payés d'avance.

Les citoyens du Cormyr doivent s'acquitter de nombreuses autres licences et taxes de faible montant. Le voyageur peut les ignorer en toute sécurité, à l'exception de ceux qui servent d'entrée à une foire commerciale ou à un établissement. Malgré tout, les Cormyréens sont beaucoup moins taxés que les citoyens de nombreux pays et cités-États, et ce pour une raison fascinante !

### La grotte de cristal

Depuis des siècles, les Obarskyrs ont réussi à taxer légèrement leurs sujets tout en échappant à l'influence des familles de nobles et de marchands les plus riches en ne s'endettant pas auprès d'eux. La raison en est une source privée de richesse fabuleuse. Quelque part dans le Cormyr se trouve la légendaire Grotte de Cristal, une caverne naturelle dont les parois sont tapissées de saphirs - une épaisse couche de cristaux étincelants, peut-être la plus grande concentration de pierres précieuses de tout Faerun !

La caverne a été découverte par Amble Obarskyr, cousin de Ring Pryntaler. En dehors d'Amble, de [[Vangerdahast Aeiulvana]] et de tous les rois légitimes depuis lors, seules six personnes l'ont vue au cours des années qui se sont écoulées depuis. Ces six chanceux étaient tous des dragons pourpres spécialisés dans l'extraction minière qui ont été amenés dans la caverne par des moyens magiques afin de garder son emplacement secret. Leur tâche consistait à extraire des masses de cristal lorsque la Couronne avait besoin de faire appel à ses richesses.

Il est connu - ou peut-être faussement avancé par les gens de la Cour - que la Grotte se trouve quelque part sous des terres appartenant directement à la Couronne et qu'elle fait partie d'un réseau de cavernes hantées par un fantôme gardien ou une sorte de liche. Ces dernières années, la caverne aux gemmes n'a été accessible que par une porte. L'emplacement de l'autre extrémité de ce transport est secret, bien que des rumeurs persistantes le situent quelque part dans les caves du palais de [[Suzail]], dans une pièce dissimulée derrière un tableau coulissant, une tapisserie ou un mur orné de sculptures.

Les Obarskyrs ont toujours veillé à dépenser leur richesse en saphirs avec modération, proposant des pierres à la vente dans le Bief de Vilhon, à [[Eauprofonde|Waterdeep]], à Amn et sur d'autres marchés éloignés, afin de maintenir leur valeur à un niveau élevé. Cependant, l'existence de la Grotte explique les rangées de saphirs qui ornent les fourreaux des quatre épées d'État de la Cour.

### Les épées d'État

Quatre lames sont vénérées au Cormyr et entretenues avec soin à la Cour. Les voleurs doivent être avertis que les sorciers de guerre peuvent les localiser et que le vol d'une épée attire une succession de Cormyréens sinistres et déterminés, prêts à tout pour la récupérer ! Ces lames sacrées sont Ansrivarr, Symylazarr, Orblyn et Rissar.

Ansrivarr est la lame ancienne et abîmée de la lignée d'Obarskyr. Elle symbolise le royaume du Cormyr lui-même. Symylazarr, également connue sous le nom de source d'honneur, est l'épée sur laquelle tous les nobles jurent fidélité à la Couronne et avec laquelle tous les chevaliers sont adoubés. Orblyn, le tranchant de la justice, est utilisé pour exécuter les nobles reconnus coupables de crimes capitaux et pour détecter les mensonges lors des séances du tribunal. Les personnes qui témoignent doivent le faire avec les mains sur la lame nue d'Orblyn, qui clignote à chaque mensonge prononcé en raison de sa capacité permanente à détecter les mensonges. Le Rissar est la petite lame ornée de bijoux avec laquelle tous les vœux de mariage royal sont prononcés. Les époux la serrent contre eux pendant qu'ils prononcent leurs vœux. La pointe de Rissar sert également à faire couler le sang dans tous les vœux de sang prononcés à la Cour, comme le serment de loyauté à la Couronne que prononce chaque sorcier de guerre. La rumeur veut que les gouttes de sang que les sorciers de guerre assermentés versent lors de cette cérémonie soient soigneusement conservées dans des fioles par [[Vangerdahast Aeiulvana]], qui, selon la légende, peut exercer à distance une magie mortelle sur les sorciers de guerre traîtres grâce à ces précieuses gouttelettes !

Lorsqu'elles ne sont pas utilisées, les quatre lames reposent sur des socles recouverts de velours, sous des dômes de cristal, chacun dans une chambre séparée de la cour royale de [[Suzail]], et le public peut les admirer gratuitement. Les épées ne sont déplacées de ces quatre grandes chambres que lorsqu'elles sont utilisées ou lorsque des personnes de sang royal sont décédées. (Ces nobles sont déposés sur les biers normalement réservés aux épées). Les visiteurs sont invités à aller voir ces monuments. Les enfants s'approchent des lames exposées et chuchotent leurs souhaits (comme le font les amoureux non partagés) aux épées, car la légende du Cormyr veut que les lames entendent tout ce qui leur est dit en confidence et agissent pour aider ceux qui sont vraiment dignes de cœur.

### Le caractère du royaume

Au Cormyr, les voyageurs trouveront un peuple heureux, voire romantique, largement satisfait de son sort. Un célèbre dicton cormyrien, prononcé pour la première fois par Baerauble, Haut Mage du Cormyr, en est la meilleure illustration. Comme [[Vangerdahast Aeiulvana]], Baerauble était un sorcier qui a sauvegardé le royaume sous les règnes de plusieurs Obarskyrs. Ce dicton est désormais inscrit sur sa tombe et a été adopté dans l'usage quotidien par le peuple du Cormyr :

*Les dieux ne nous accordent pas à tous
Le manteau brillant du héros.
Faites ce que vous pouvez,
Et ce sera suffisant*


## Stonelands

Totalement impropre à l'agriculture, le sol y est sec et largement composé d'argile. En outre, la surface de la terre est presque recouverte de rochers de toutes tailles. Certains sont même aussi gros que des cottages, et ils sont éparpillés partout.

Contrairement à d'autres régions rocheuses qui sont d'une beauté saisissante, les Stonelands sont laids. Les rochers sont de couleur uniforme, la terre semble malade et la couverture nuageuse, apparemment omniprésente, obscurcit les levers et les couchers de soleil. Un seul type de créature pourrait s'approprier un tel endroit : les pilleurs de frontières. Le terme "pilleurs de frontières" s'applique collectivement aux nombreuses espèces de monstres intelligents, aux tribus de voyous humains et demi-humains, ainsi qu'à d'autres créatures et groupes malfaisants et maléfiques qui infestent la région.

La plus célèbre de ces organisations est le Zhentarim, le Réseau noir. Les Zhentarim utilisent les Stonelands comme base d'opérations, contestant constamment le contrôle des Cormytes sur la région. Une rumeur récente fait peser une menace particulière si elle est avérée : les Zhentarim utiliseraient des porteurs d'abeilles fous pour défricher le terrain. Les Red Ravens et les réguliers cormyréens ont mis en place des patrouilles nocturnes exceptionnellement puissantes afin d'empêcher un contemplateur fou de pénétrer dans le camp et de désintégrer tous ceux qu'il aperçoit. Cependant, ces patrouilles n'ont repéré aucun porteur de sort, et encore moins un escadron de porteurs de sort sous contrôle zhentarim.

La crypte légendaire des guerriers est un trésor qui attire les aventuriers les plus raisonnables dans les Stonelands. Bien que son emplacement approximatif soit inconnu, elle a attiré de nombreuses expéditions dans ces terres lugubres.

Un autre visiteur fréquent des Stonelands est un combattant solitaire nommé Emperel (CG hm F16), qui erre souvent seul dans ces étendues pour vaincre les êtres maléfiques qui y habitent et les empêcher de trouver la grotte qui abrite les Seigneurs qui dorment. Emperel espère trouver leur lieu de repos, les détruire et piller leur grotte, empêchant ainsi la réalisation de la prophétie selon laquelle ces hommes maléfiques se réveilleront et balaieront Cormyr dans la ruine.

## Le vaste marais

Le siège du pouvoir Cette étendue de marécages est tellement ignorée qu'elle n'a même pas de nom propre. Elle sépare le Cormyr et le Sembia, mais aucun des deux royaumes ne revendique de territoire à l'intérieur du marais, et aucun n'y a fait d'expéditions sérieuses.

Toutes sortes de créatures immondes ont élu domicile dans le vaste marais. Les plus nombreuses sont sans doute les hommes-lézards, les trolls, les hobgobelins et les gnolls, et les plus menaçantes sont les dragons noirs, les beholders et les catoblépas.

Si les légendes sont vraies, le résident le plus célèbre du Vast Swamp est le Seigneur du Crépuscule de Sessrendale (voir la version révisée du cadre de campagne FORGOTTEN REALM, A Grand Tour of the Realms).

Comme personne ne s'aventure jamais dans le marais, on ne sait pas avec certitude ce que recèlent ses recoins les plus sombres et les plus isolés.


## Terres agricoles

Les fermes constituent la force fondamentale du royaume et l'une des principales forces qui façonnent sa topographie. L'agriculture est responsable de la réduction de la surface forestière du Cormyr. En effet, les terres situées entre la forêt centrale du Cormyr et la forêt de Hullack étaient autrefois entièrement recouvertes d'arbres. Aujourd'hui, ces terres sont principalement constituées de fermes et de pâturages.

# Cités majeures

## Système d'évaluations des commerces

Le prix n'est pas toujours proportionnel à la qualité du service rendu.

| Qualité | Prix | Taverne | Auberge |
| ---- | ---- | ---- | ---- |
| Horrible | 💰 | 🍺 | 🛏️ |
| Passabe | 💰💰 | 🍺🍺 | 🛏️🛏️ |
| Moyen | 💰💰💰 | 🍺🍺🍺 | 🛏️🛏️🛏️ |
| Bon | 💰💰💰💰 | 🍺🍺🍺🍺 | 🛏️🛏️🛏️🛏️ |
| Excellent | 💰💰💰💰💰 | 🍺🍺🍺🍺🍺 | 🛏️🛏️🛏️🛏️🛏️ |

## [[Suzail]]  
## [[Marsember]]

## [[Arabel]]

## [[Tilverton]]

# Petites villes
## La côte

La partie la plus anciennement habitée et la plus pastorale du Royaume des Forêts est la zone agricole côtière située entre la rivière Starwater et le vaste marais. Au fil des ans, différents peuples ont appliqué le terme "côte" à différents endroits. Je l'ai défini comme étant tout le Cormyr au sud de la Voie de la Manticore (la route terrestre reliant le Cormyr à la Sembie) entre la Starwater et le Darkflow.

Les habitants de la côte sont un mélange de fermiers et de pêcheurs, tant d'eau douce que d'eau salée. Les palourdes et les anguilles tirées de la Starwater par les pêcheurs d'eau douce sont considérées comme des mets délicats dans ce pays, bien que la plupart des visiteurs les trouvent trop fades ou trop poissonneux à leur goût. La piraterie et la contrebande sont depuis longtemps des activités discrètes dans la région. Bien que les bateaux de la marine patrouillent le long de la côte, il existe de nombreuses plages, criques et anses isolées où les contrebandiers peuvent s'installer.

Les visiteurs sont informés qu'il peut être fatal de rencontrer des contrebandiers à l'œuvre. Ne vous promenez pas à proximité de ces endroits à moins d'avoir une bonne raison. Si les contrebandiers ne vous attrapent pas, les patrouilles du Dragon Pourpre risquent de vous soupçonner d'être un contrebandier et d'attacher des espions pour surveiller chacun de vos pas dans le royaume. Cela peut mettre un frein aux négociations commerciales, qu'il s'agisse d'accords avec des marchands ou de rencontres avec des dames qui se moquent des soirées. Et cela peut vous valoir une note permanente "à surveiller" dans les dossiers de ces soldats. Considérez-vous comme averti.

### Hameaux

La côte est une campagne vallonnée composée de nombreux bosquets, de champs entourés de gravats et de souches, et de chemins de terre sans nom qui mènent à de petits hameaux, vallées et villages insignifiants que je n'ai pas abordés en détail dans ce livre. À l'intention des voyageurs, voici quelques notes sur certaines de ces communautés négligées :

#### [[Battlerise]]
#### [[Blustich]]
#### [[Dreamer's rock]]
#### [[Gorthin]]
#### [[Kallamarn]]
#### [[Moonever]]
#### [[Nesmyth]]
#### [[Ongul's Water]]
#### [[Smuggler's Stone]]



### Village

#### [[Bogbrook]]
#### [[Dawngleam]]
#### [[Gladehap]]
#### [[Kirinwood]]
#### [[Monksblade]] 
#### [[Wheloon]]
#### [[Wormtower]]

## Les Heartlands

Le cœur du Roi de la Forêt est la Forêt des Rois et les villages et villes qui l'entourent. La Forêt des Rois est une vieille, profonde et belle forêt d'arbres anciens recouverts de mousse, de ravins profonds et cachés, de cerfs magnifiques et d'un bois de chauffage inépuisable. La plupart des gens imaginent l'immensité verte de la Forêt des Anneaux lorsqu'ils pensent au Cormyr. Sa présence fait du Cormyr ce qu'il est : entre autres choses, l'un des plus beaux royaumes de tout Faerûn.

Aucun écrivain de voyage ne saurait trop parler de l'immense et glorieuse forêt des Anneaux qui recouvre presque entièrement les terres du cœur. Elle est suffisamment vaste pour qu'on y passe sa vie à se promener et abrite de nombreuses communautés de satyres, de lutins, de korred, et même d'[[Elfes]] et de [[Halfelins|halflings]] dont il n'est pas question dans ce guide, ni dans aucun autre guide humain. Au moins un de ces territoires, situé non loin à l'est de [[Waymoot]], le royaume dryade d'Aloushe, se considère comme un royaume indépendant et souverain. Sa reine, Radanathe, l'a dit à [[Vangerdahast Aeiulvana]] lorsque ses sorts de surveillance l'ont découverte et qu'il lui a lancé un défi de longue haleine.

La légende cormyréenne abonde en récits de ruines croulantes et oubliées, enfouies sous la verdure et la moisissure des profondeurs de la forêt des Anneaux, et certains manoirs de nobles d'antan ont certainement été retrouvés au fil des ans. Qui sait quels secrets les terres du cœur peuvent encore receler ?

### Petits villages

La plupart des lieux nommés dans les Terres du Cœur méritent une entrée complète dans ce livre, mais il y en a certains que j'ai négligés par manque de place. Pour les voyageurs, voici quelques notes sur certaines de ces communautés :
#### [[Gray Oaks]]
#### [[Hilp]]
#### [[Minroe]]
#### [[Zundle]]
#### [[Aunkspear]]

### Points d'interets
#### Le gouffre [[Plungepool]]
#### [[L'Auberge de Blisterfoot]]

#### [[Dhedluk]] (dead-LUKE)
#### [[Espar]]
#### [[Eveningstar]]
#### [[Immersea]]
#### [[Jester's Green]]

> [!warning] A traduire ci-dessous
#### [[Knightswood]]
#### [[Mouth o' Gargoyles]]
#### [[Stag Steads]]
#### [[Tyrluk]]
#### [[Waymoot]]

## The East reaches

An ancient Faerûnian saying runs: Every realm has a frontier, no matter how crowded or civilized. The east reaches are Cormyrs present frontier, and, some sages insist, its future. Others say the true fron- tier, the lands that Cormyr will look to after the east reaches are crowded and settled, is the west reaches. Still others give that honor to the Stonelands and Goblin Marches, seeing Cormyr ulti- mately as a realm stretching from the Far Hills to the Thunder Peaks, bounded on the north by Anauroch and on the south by everything on the south shore of the Lake of Dragons that Westgate cant hold against the troops of Cormyr.

### An East Reach Overview

Il y a un dicton dans les régions de l'est : "Nous n'avons qu'un lac à Cormyr, mais il est grand". Cette référence à l'immense Wyvernwater est, bien sûr, fausse. Le Cormyr compte de nombreux lacs et étangs trop petits et trop éloignés pour figurer sur la plupart des cartes. En fait, il est difficile de s'éloigner du bruit de l'eau qui coule ou s'écrase sur le rivage dans le Royaume des Forêts. Cependant, la Wyvernwater domine et divise l'est du royaume entre la région sud, plus habitée et pastorale, située entre la Wyvernwater et la Voie de la Manticore, et la région nord, plus sauvage et frontalière. C'est dans cette région du nord que le Cormyr devrait s'étendre dans les années à venir, en remplissant les territoires non colonisés entre [[Tilverton]] et [[Arabel]]. Pour que cette expansion soit heureuse et prospère, deux grandes régions doivent être apprivoisées : La forêt de Hullack, une cachette idéale pour les brigands et les monstres prédateurs, et les Stonelands.

Les dragons habitent également les Pics du Tonnerre. Une importante faction de sorciers de guerre, dirigée par [[Vangerdahast Aeiulvana]], considère que l'apprivoisement d'un vol de dragons est un élément essentiel de la sécurisation des régions orientales du royaume.
Ils veulent créer une force de frappe aérienne/une force de patrouille de mages armés de baguettes à dos de dragon. Un objectif plus réaliste et immédiat est d'attraper et d'apprivoiser certains des hippogriffes que l'on trouve en grand nombre dans les Pics du Tonnerre. Les hippogriffes sont plus nombreux près de la source de l'Immerflow, où des mines perdues se trouvent dans plusieurs hautes vallées. Ces mines ont été abandonnées par les humains et les [[Nains]] il y a des dizaines d'années à la suite d'attaques vicieuses de clans de hobgobelins qui se cachent toujours dans la région.

Les ressources naturelles peuvent encore attirer les intrus et les Cormyréens dans les régions orientales du Cormyr. Les Pics du Tonnerre sont connus pour contenir de nombreux minerais précieux et quelques gisements de pierres précieuses. Les épices ateris et bentilan peuvent également être récoltées le long de la côte est, dans les contreforts des pics du tonnerre et des cornes de tempête. Les baies de bentilan valent 2 sp par livre ; les bourgeons d'ateris, de courte durée, ne rapportent qu'environ 3 cp par livre. De plus, les arbres des profondeurs de la forêt de Hullack renferment de futurs mâts et poutres de toit qui prennent de plus en plus de valeur à mesure que les monstres rendent l'exploitation des parties intactes de la Cour des [[Elfes]] de plus en plus périlleuse.

### Petits villages

Les rêves mis à part, il est clair que les étendues orientales situées juste au nord du Wyvernwater se peuplent rapidement et que des endroits comme [[Redspring]] pourraient bientôt devenir prometteurs. La terre est un pays de collines ondulées, avec des forêts de broussailles et des ajoncs qui poussent à profusion. De petits ravins abritent de minuscules ruisseaux qui descendent jusqu'à la Wyvernwater. Autrefois, les wyvernes étaient nombreuses dans la région (d'où le nom du lac), mais elles ont été largement exterminées il y a des siècles. Pourtant, d'autres dangers subsistent. Des monstres de toutes sortes s'attaquent à la région depuis les Stonelands et la forêt de Hullack. Ils ont été renforcés ces dernières années par des brigands et des bandes d'[[orcs]] et de gobelins sponsorisés par les Zhentarim du Darkhold.

En raison de ces dangers, les villages de la région ont tendance à être petits et à s'empiler. Bien que les établissements de cette région soient peu nombreux et puissent être d'une importance cruciale pour un voyageur perdu ou harcelé, j'ai laissé de côté dans ce livre une discussion importante sur plusieurs des endroits les moins remarquables. À titre de référence pour les voyageurs, voici quelques notes sur certaines de ces communautés.


#### [[Bospir]]
#### [[Ghars]]
#### [[Griffon Hill]]
#### [[Halfhap]]
#### [[Hillmarch]]
#### [[Redspring]]
#### [[Slingdyke]]
#### [[Sunset Hill]]
#### [[Yeoman Bridge]]
#### [[Hultail]]
#### [[Juniril]]
#### [[Thunderstone]]
#### [[Tilverton]]
#### [[Castle Crag]]
#### [[Castle Kilgrave]]

#### [[Noktil]]


## The West Reaches

Cet arrière-pays montagneux du royaume de Cormyr (comme l'appelait un sage il y a longtemps) est souvent négligé par les Cormyréens et les voyageurs.

voyageurs. Le visiteur qui ne s'aventure pas jusqu'à l'ouest du royaume rate une grande partie de la beauté du royaume de la forêt. Ses prairies et ses forêts de pins enveloppées de brume sont exquises, mais souvent mortelles. Malgré la force grandissante de Cormyrs, ce pays reste un pays de monstres.

La cartographie des Stonelands et des Storm Horns permet à quelques groupes d'aventuriers de confiance de bénéficier d'une source de revenus régulière. Cependant, de nombreuses vallées et hautes prairies des Cornes de l'Orage restent inexplorées ou cartographiées aujourd'hui, malgré le travail assidu des sorciers de guerre spécialisés dans la scrutation et des aventuriers engagés pour suivre ce qu'un mage a vu de loin.

### Waystops et Holdings

Les établissements dans les Cornes d'Orage sont rares. Chacun d'entre eux peut être crucial pour la survie des voyageurs, en particulier s'ils sont traqués par des brigands ou des bandes d'[[orcs]], mais cela ne fait pas de ces lieux des endroits très intéressants à visiter ou dignes d'être décrits en détail dans ce livre. Quelques-uns de ces lieux sont des étapes vitales, mais ils ne sont pas plus beaux ou mieux équipés qu'ils ne doivent l'être. Ces endroits sont mentionnés brièvement dans cette section pour les voyageurs qui essaient de rester en vie :

#### [[Eagle Peak]]
#### [[Hutduth]]
#### [[High Horn]]
#### [[Old Axe]]
#### [[Skull Crag]]
#### [[Greatgaunt]]
#### [[Hornshield]]
#### [[Wyvernhunt]]





# Histoire du Cormyr

La Maison d'Obarskyr a unifié le petit territoire connu sous le nom de Cormyr, qui était basé autour d'une petite ville fortifiée, [[Suzail]], et de quelques avant-postes. Cette ville est devenue le siège du pouvoir du royaume du Cormyr.

La maison d'Obarskyr est à l'origine de la lignée de rois qui s'étend jusqu'à aujourd'hui et au souverain du Cormyr : Le roi [[Azoun IV Obarskyr|Azoun IV]]. Le roi [[Azoun IV Obarskyr|Azoun]] est le 71e de sa lignée.

Au début, le règne du Cormyr fut difficile. En effet, il est arrivé que le roi soit contraint de gouverner non pas depuis son trône de [[Suzail]], mais de s'installer dans l'un des avant-postes, comme [[Arabel]] ou [[Marsember]]. Les intrigues, les rébellions et d'autres facteurs ont tous contribué aux changements de lieu de résidence du roi.

## Le roi perdu

Un exemple de rébellion a été le bref règne de Gondegal, également connu sous le nom de "roi perdu".

En 1352 (l'année du dragon), Gondegal a tenté d'établir son propre royaume au sein du Cormyr. Gondegal voulait être roi et considérait que la seule façon d'y parvenir était de prendre des terres par la force et de s'installer comme souverain.

Gondegal utilisa [[Arabel]] comme base d'opérations et commença par recruter des mercenaires dans tout le Cormyr et dans ce que l'on appelle aujourd'hui les Marches des Gobelins et les Stonelands. En échange de leur service militaire, Gondegal promettait à ses soldats tout le butin qu'ils pourraient trouver en chemin, et à ses commandants des titres de noblesse et des parcelles de terre.

Gondegal mena de nombreux raids de type guérilla dans tout le Cormyr et connut un certain succès dans sa quête initiale du pouvoir. Les forces de Gondegal portèrent sa bannière jusqu'aux Montagnes du Désert, à l'est, au-delà de Wyvernwater, jusqu'aux Vastes Marais (capturant [[Immersea]], [[Hultail]], [[Thunderstone]] et [[Wheloon]]), à l'ouest, jusqu'aux fermes autour d'[[Eveningstar]] (bien qu'[[Eveningstar]] elle-même ait résisté au siège de Gondegal), et au nord-est, jusqu'à Tilver's Gap.

Les troupes de Gondegal, bien que mercenaires, se sont suffisamment bien comportées pour s'emparer d'une partie importante des terres et causer beaucoup de misère dans les villes qu'elles occupaient. Les troupes ont également pris Gondegal au mot et ont pillé tout ce qui leur tombait sous la main, laissant de nombreuses villes et fermes en ruines et de nombreux morts.

La chute de Gondegal est due à deux erreurs concomitantes. Tout d'abord, il a promis à ses mercenaires tout le butin qu'ils pourraient trouver. Cela a épuisé les villes qu'ils ont mises à sac, les rendant inutiles comme points de ravitaillement pour les opérations ultérieures des troupes. Deuxièmement, les troupes de Gondegal frappaient soudainement et se déplaçaient rapidement. Si Gondegal a pu s'emparer d'autant de territoires, c'est parce qu'il a pu réagir plus rapidement que les forces résidentes du Cormyr, les Dragons Pourpres.

Cependant, cela signifiait que les représailles des Dragons Pourpres se produiraient en masse, une fois qu'ils seraient en mesure de se regrouper, de se conduire comme une unité à part entière et de faire venir des renforts d'autres pays. Une grande partie de l'armée étant stationnée à [[High Horn]] à l'époque, il était très difficile de rassembler suffisamment de troupes pour défier Gondegal sur le terrain. Le Cormyr avait été préparé à une attaque extérieure, mais pas à un ennemi intérieur.

De plus, Gondegal a bouleversé l'équilibre des forces dans la région, et les autres royaumes de la région, Sembia, Daggerdale, [[Tilverton]] et d'autres vallées se sont unis pour aider à vaincre le renégat. Gondegal réussit à établir un trône à [[Arabel]]. Ce règne n'a duré que huit jours, et Gondegal n'est resté que cinq jours à [[Arabel]] en tant que souverain de son royaume improvisé.

Finalement, les Dragons Pourpres et la puissance combinée des autres royaumes marchèrent contre Gondegal. Des avancées simultanées commencèrent à partir de [[High Horn]], High Dale, Thunder Gap et [[Tilverton]] (ses forces survivantes avaient rapidement repris leur ville après que Gondegal s'en soit emparé).

Lorsque les Dragons pourpres pénétrèrent dans les territoires occupés, ils furent accueillis par des images de destruction et de désespoir. Les troupes de Gondegal s'étaient enfuies, pillant autant qu'elles le pouvaient avant de battre en retraite, dans l'espoir de trouver du butin ailleurs. En fait, une grande partie des troupes de Gondegal s'était simplement rendue et avait offert de rejoindre les Dragons Pourpres en échange de nourriture et d'un abri.

Les forces de Gondegal se sont effondrées face aux Dragons en marche. Tout au long de cette avancée simultanée, il n'y a pas eu une seule bataille majeure et aucune bataille n'a duré plus d'une heure ou n'a coûté plus de 100 vies. La plupart des troupes renégates ont décidé de se battre uniquement parce qu'elles ne voyaient pas d'autre option, choisissant de mourir au combat plutôt que de retourner chez elles dans le déshonneur.

Les Dragons pourpres, menés personnellement par le roi [[Azoun IV Obarskyr|Azoun IV]], marchèrent sur [[Arabel]] en s'attendant à une bataille rangée ou à un long siège de la forteresse de Gondegal. Au lieu de cela, les Dragons pourpres n'ont rencontré aucune résistance. Gondegal s'était enfui, probablement pendant la nuit ou peut-être même un jour ou deux auparavant, et avait laissé ses troupes livrées à elles-mêmes. Les troupes mercenaires de Gondegal n'avaient aucune raison de se battre pour [[Arabel]]. Elles ne se battaient que pour l'or, et la source de cet or avait fui [[Arabel]]. Les Dragons Pourpres occupèrent [[Arabel]] sans verser une goutte de sang.

## La terre en paix

Le pays est officiellement en paix depuis de nombreuses années, depuis que Rhigaerd a renversé les derniers pilleurs de frontières. Cependant, les forces cormyriennes ont pris part à de nombreuses actions dans les régions voisines, et la nation a récemment rassemblé ses forces pour occuper [[Tilverton]] sur les marches des Dalelands et pour mener une croisade contre les grandes hordes tuiganes qui envahissent les royaumes depuis l'est.

> [!quote] Un esprit a noté : 
> *"Oui, le pays est en paix, mais l'armée doit rester occupée."*

Outre les actions d'envergure, les patrouilles cormyriennes se livrent souvent à des escarmouches avec des bandits sur les routes du nord et de l'ouest et se battent actuellement contre des [[orcs]] et d'autres créatures au nord et à l'est du Cormyr, dans le fossé de Tilver et le fossé de l'Ombre. Ces deux régions sont menacées par des pillards maléfiques qui menaceront le Cormyr lui-même s'ils parviennent à envahir [[Tilverton]]. Le Cormyr a construit une forteresse, [[Castle Crag]], pour défendre le royaume contre les attaques venant de cette région, et entretient la [[High Horn|Haute Corne]] pour se protéger des attaques venant de l'ouest.

## Un royaume en expansion

Le Cormyr a commencé par être une cité-état composée de [[Suzail]] et de quelques communautés environnantes. Depuis, le Cormyr s'est considérablement agrandi.

Son premier grand effort d'expansion s'est porté sur ce que l'on appelle aujourd'hui la Forêt du Roi. Cette forêt, qui était à l'époque bien plus grande que sa taille actuelle, était infestée de monstres, d'un repaire de brigands et d'une multitude d'autres menaces pour l'habitat humain.

Grâce aux efforts concentrés de [[Suzail]] et des communautés voisines, la forêt a été débarrassée des monstres et rendue habitable. Les gens attirés par le gibier et le bois riche ont fondé de petites communautés qui existent encore aujourd'hui.

La couronne créa des points forts avec des garnisons pour protéger les frontières du Cormyr. Deux de ces endroits furent connus sous le nom de [[Castle Crag]] et [[High Horn]].

[[High Horn]] fut le premier et sa construction prit le plus de temps. Situé dans un col à 1 000 pieds d'altitude, [[High Horn]] posait un problème d'ingénierie difficile : construire les tours et les murs du complexe et aménager le terrain montagneux environnant. La construction du château et de la route qui y mène et le traverse a pris près d'une décennie.

[[Castle Crag]], une structure plus petite et plus simple située sur un terrain plus clément, a pris moins de temps à achever. Ces avant-postes représentaient la plus grande expansion des forces cormyriennes depuis très longtemps.

Pendant la construction de ces avant-postes, les paysans cormyriens commencèrent à cultiver les terres bordant la Wyvernwater. Ce territoire n'était revendiqué par aucun autre royaume (Sembia, un choix possible, ne revendiquait des terres que jusqu'au Vast Swamp) et l'expansion cormyrienne dans cette région était inévitable. La migration a été graduelle et les quelques communautés le long de la Wyvernwater sont orientées vers l'agriculture.

Un effort concentré est en cours pour débarrasser la région des monstres et créer un lieu propice à l'habitation, à l'instar de la Forêt du Roi.

## Expansion future

Le Cormyr s'étend régulièrement vers l'est et le nord-est. Cela signifie que la Forêt de Hullack et les régions qui l'entourent, ainsi que celles situées entre la Forêt et [[Tilverton]], seront de plus en plus étroitement contrôlées par le Cormyr et deviendront de plus en plus propices à une vie sûre. Au fur et à mesure de sa croissance, le Cormyr a commencé à se tourner vers la forêt de Hullack pour combler ses besoins croissants en ressources.

L'acquisition récente de [[Tilverton]] signifie que le Cormyr se tournera vers les Stonelands et peut-être les Marches des Gobelins comme prochain effort sérieux après la Forêt de Hullack. Les Marches des Gobelins seront probablement d'une importance secondaire par rapport aux Stonelands, qui sont plus proches de [[Tilverton]] et présentent un plus grand risque pour la sécurité de cette région.

L'une des principales difficultés pour dompter ces terres est qu'elles sont terriblement indisciplinées et que les efforts actuels n'ont pas été couronnés de succès. Seul un effort sérieux de conquête militariste permettra de contrôler ces régions. Ce type d'activité risque d'attiser la colère des Zhentarim, des habitants de Daggerdale et de Sembia. Les Dales, y compris [[Shadowdale]], seront inquiétés si le Cormyr et les royaumes susmentionnés entrent en guerre, car les Dales deviendront un champ de bataille. Pire encore, ni le Cormyr ni son ennemi dans une telle guerre ne pourraient résister à l'envie de revendiquer les champs de bataille gagnés comme territoire conquis.

La côte qui longe le lac des Dragons, entre [[Marsember]] et Urmlaspyr, verra probablement de plus grandes communautés se développer. L'augmentation du nombre de navires naviguant sur le lac entraînera une hausse de la demande de ports. De plus, il sera peut-être plus nécessaire d'avoir un port plus proche des royaumes situés au-delà du Neck dans le Lac des Dragons, c'est-à-dire un port plus proche de villes comme Westgate et Urmlaspyr. Le Cormyr devrait envisager la création d'un port plus proche du golfe afin de protéger les navires cormyriens des activités des pirates.

# Société Cormyte

## L'état d'esprit des Cormytes

Les citoyens du Cormyr sont avant tout satisfaits de leur royaume et convaincus que leur système de gouvernement est le meilleur. Cela a donné aux Cormyriens la réputation d'être élitistes et de croire que les autres royaumes sont inférieurs au leur. Dans une certaine mesure, cette croyance est fondée sur des faits.

Les Dales, les Vastes, les Heartlands occidentaux et la Côte des dragons, par exemple, sont trop désorganisés pour apporter des changements durables dans leurs royaumes. Si l'un d'entre eux s'organisait sous l'égide d'un seul dirigeant et adoptait le système du Cormyr, à savoir un roi fort, une armée centrale puissante et des citoyens satisfaits, il pourrait devenir un État plus puissant.

Les Cormyréens sont des citoyens responsables qui prennent à cœur les problèmes du royaume et participent aux affaires de la communauté. Chaque ville du Cormyr possède un sens aigu de la communauté qu'il est difficile de briser.

Cette unité est l'une des plus grandes forces du Cormyr. Cette unité est également évidente dans le dévouement consciencieux de la classe noble envers ses dirigeants et son gouvernement. Les nobles considèrent leur rôle au Cormyr comme un devoir envers leurs concitoyens plutôt que comme un droit au pouvoir hérité (et abusif).

Les Cormyréens sont également fiers de leur niveau de civilisation. Ils respectent les lois du pays avec compassion et diligence, mais pas au point de laisser les criminels en liberté ou d'inciter les prisonniers à craindre pour leur vie lorsqu'ils entrent en prison.

## Douanes

Certaines coutumes cormyréennes sont courantes, d'autres sont plus qu'inhabituelles. Pour se fondre dans la masse et se faire accepter, le visiteur doit les apprendre et s'efforcer de les respecter. (Voir "Milices locales" à la page 58 pour savoir comment les visiteurs peuvent se familiariser avec les lois et les coutumes cormyréennes).

- Les roturiers des deux sexes s'inclinent devant les membres de la famille royale. Il s'agit en fait d'une loi que les Cormyréens appliquent aux visiteurs, quels qu'ils soient ou quelle que soit la personne royale. Les Cormyréens respectent beaucoup leurs dirigeants, et ils veulent imprimer ce respect à tous ceux qui visitent leur royaume.
- Les enterrements sont suivis de veillées. Les Cormyréens considèrent la mort comme la fin d'un voyage agréable dans un royaume merveilleux, ce qui n'est pas loin de la vérité. Certes, les pratiques funéraires varient d'une religion à l'autre, mais dans tout le Cormyr, on croit qu'une sorte de veillée doit suivre l'enterrement, que le défunt doit être pleuré par les vivants, que son esprit vive ou non. Mais en même temps, la vie au Cormyr doit être célébrée et les festivités qui accompagnent une veillée funèbre servent à rappeler à tous les participants la chance qu'ils ont de faire partie du Cormyr.
- Les chats sont les yeux et les messagers des dieux. Le respect du Cormyr pour les chats remonte à des temps immémoriaux. Les chats sont vénérés au Cormyr comme aucun autre animal, et cette vénération s'étend à toutes les croyances religieuses. Les chats sont sacrés et ne doivent jamais être tués. On dit également que le fait d'élever un chat peut inciter les dieux à intervenir en sa faveur en cas de tragédie. C'est pourquoi de nombreux citoyens du Cormyr possèdent au moins un chat, et les chats sont autorisés à courir dans la maison et ne sont jamais gardés en cage. Il convient de noter que la modification d'un chat est considérée comme une grave offense. Couper les oreilles, la fourrure ou surtout la queue est un motif d'ostracisme (pour le coupable, pas pour la victime !) dans certaines villes. Il ne faut pas non plus altérer la capacité de reproduction d'un chat, car les dieux détermineront le nombre de chats dans le Cormyr. Il est certain qu'il serait très difficile d'élever des chats si on leur permettait de courir en liberté et de se reproduire à volonté. Heureusement, en ce qui concerne les conditions de vie des humains, les chats ont de nombreux prédateurs naturels qui maintiennent la population à un niveau suffisamment bas pour que les chats n'interfèrent pas trop avec les conditions de vie, en particulier dans les grandes villes.
- Les femmes désireuses de trouver un compagnon portent des foulards violets. Il s'agit d'une autre coutume ancestrale dont l'origine est inconnue. Selon une explication moderne, lorsqu'une femme désire un partenaire, elle porte la couleur de la bannière du Cormyr pour rappeler aux hommes leur obligation envers le royaume, à savoir prendre un partenaire et augmenter la population du Cormyr. Il est certain que toutes les femmes ne souscrivent pas à cette coutume, et qu'elle est surtout utilisée par les femmes qui se considèrent comme jeunes et aventureuses. Les amoureux offrent souvent des foulards violets en signe d'affection.
- Les invités respectent toujours les règles de la maison. Lorsqu'il est invité dans la maison d'un ami, l'invité doit s'assurer qu'il ne perturbe pas la routine quotidienne de son hôte. Les Cormyréens estiment que la maison est l'un des lieux les plus importants et que son entretien est primordial pour assurer le bonheur d'une famille. Les invités ne doivent donc pas faire de choses qui interfèrent avec le mode de vie de la famille d'accueil.
- Il est interdit de chasser sur les terres d'autrui. La population de gibier est parfois rare dans certaines parties du Cormyr, et la couronne réglemente étroitement la chasse, en particulier dans la Forêt du Roi. La violation de cette coutume équivaut à une trahison de la confiance entre voisins et entraîne un ostracisme de bas niveau. (Les gens ne traverseront peut-être pas la rue pour éviter le contrevenant, mais il est probable qu'ils ignoreront sa présence). Dans certains cas, des individus ont pu se racheter en offrant un banquet à leur ville et en autorisant d'autres personnes à chasser sur leurs terres.
- L'utilisation de devises étrangères est mal vue. Les Cormyréens doivent utiliser la monnaie de leur propre royaume et ne pas compter sur la monnaie d'autres royaumes, peut-être moins importants. L'introduction de monnaies étrangères est une façon subtile de s'infiltrer, en donnant à l'autre royaume un rôle dans la vie quotidienne du Cormyr. Cela ne doit pas être toléré, et les visiteurs qui arrivent au Cormyr sont rapidement priés par les commerçants de convertir leur monnaie en monnaie cormyte. Le commerce de la monnaie se fait presque exclusivement chez un bijoutier ou dans un lieu officiel tel que le bureau de l'herald local, car eux seuls disposent de l'équipement nécessaire pour tester, peser et évaluer correctement la légitimité de la monnaie étrangère et déterminer sa valeur par rapport à la monnaie cormyte. [[Suzail]], [[Marsember]], [[Arabel]] et [[Tilverton]], les centres commerciaux du Cormyr, sont des exceptions notables à cette coutume. Leurs économies basées sur le commerce dépendent de la monnaie extérieure au Cormyr ainsi que de la monnaie royale. Chacune de ces villes possède une grande bourse, permettant aux étrangers de se promener dans le Cormyr sans commettre l'impair de payer avec des pièces étrangères.

## Divertissement

Les Cormyréens sont des gens civilisés et, pour cette raison, ils n'aiment pas les sports sanglants comme le font les citoyens d'autres royaumes. Vous ne trouverez donc pas d'arène au Cormyr. Au lieu de cela, les divertissements tournent autour des festivals. Il y a des festivals pour toute une série de fêtes et de célébrations d'anniversaires royaux. Cet amour des festivals s'étend à toutes les religions, et les Cormyréens participent souvent à des festivités célébrant des événements qui ne relèvent pas de leur propre foi.

Les activités des festivals concernent généralement l'ensemble de la communauté, en particulier dans les petites villes, chacun assumant des tâches telles que les décorations ou la préparation des repas. Les personnes capables de créer des décorations élaborées sont très vénérées dans la société cormyte, car elles contribuent à un festival comme personne d'autre ne peut le faire. Dans les petites villes, il y a généralement une personne connue sous le nom de "décorateur", qui supervise toutes les décorations du festival. Certaines villes soutiennent financièrement le décorateur afin qu'il puisse travailler à plein temps sur de nouvelles créations.

## Law and Order

Les lois et leur application sont à la base de la grandeur du Cormyr. Pour un Cormyréen, ce sont les lois, conçues par le roi et appliquées par ses Dragons Pourpres et autres milices, qui ont permis de dompter les étendues sauvages du Cormyr et de donner à la région une existence organisée et paisible.

### Lois nationales

Un certain nombre de lois sont communes à l'ensemble du Cormyr. Naturellement, certaines de ces lois sont appliquées plus que d'autres, et chaque ville diffère dans son traitement des contrevenants. Certaines imposent des amendes, d'autres bannissent les contrevenants de leur territoire. Voici quelques lois nationales :
- Les roturiers des deux sexes courbent la tête devant la royauté.
- Les visiteurs s'inclinent devant le seigneur local.
- Les aventuriers armés qui vont en paix portent des "peacestrings" autour de la poignée de leur épée, ce qui empêche (en théorie) de la dégainer rapidement. Il s'agit surtout d'un geste symbolique, car ils n'empêchent pas à proprement parler de prendre rapidement les armes. Une embuscade contre un groupe ayant des liens de paix ne serait pas beaucoup plus réussie qu'une embuscade contre ceux qui n'ont pas de liens de paix.
- Tout le monde doit se soumettre à une fouille par la milice sur demande.
- Les devises étrangères ne peuvent être échangées que par les entreprises autorisées à le faire. Cette mesure vise à empêcher l'introduction de devises étrangères dans la population, ce qui pourrait entra"ner une dévaluation de la monnaie du Cormyr.

### La Cour Juridique

L'une des plus grandes réussites du Cormyr est son système judiciaire. De tous les systèmes juridiques de Faerün, c'est celui du Cormyr qui fonctionne le mieux. La question de savoir s'il s'agit ou non du meilleur système pour ses sujets est sujette à débat, mais le système fonctionne aussi bien dans la pratique que sur le papier lors de sa création.

Le système judiciaire fonctionne de la même manière que dans les autres royaumes. Le seigneur ou le noble local juge et condamne les contrevenants à des peines. Les nobles peuvent demander à être jugés par le roi ou par un jury de leurs pairs (d'autres souverains ou des sorciers de guerre chevronnés). S'ils font appel du verdict, ils doivent s'adresser à un jury composé d'une douzaine de roturiers choisis personnellement par le roi.

Cependant, le Cormyr est inhabituel à deux égards. Tout d'abord, l'accusé n'est pas considéré comme coupable ou innocent jusqu'à preuve du contraire. Au contraire, le suspect doit "répondre" aux accusations et l'accusateur doit les "justifier". Deuxièmement, il existe une procédure d'appel. Un propriétaire foncier (qui paie donc des impôts au roi) a le droit de faire appel du jugement auprès d'une instance supérieure dans la chaîne de l'autorité légale.

Les chefs de milice sont le plus souvent utilisés comme accusateurs. Dans les petites villes, cela signifie que l'accusateur est aussi le juge. Certaines villes ont la réputation d'être de mauvais endroits où l'on peut être accusé de crimes graves.

Le royaume ne fournit aucune facilité à l'accusé. C'est à l'accusé qu'il incombe de plaider sa cause devant le juge et de le persuader qu'il doit être déclaré non coupable.

## La cour royale

La force vive du Cormyr réside dans ses dirigeants. Sans eux, le Cormyr ne serait pas l'entité organisée qu'il est.

[[Suzail]] compte environ 30 petits châteaux abritant des familles nobles. Ces châteaux entourent l'enceinte du roi et forment une ville d'élite à l'intérieur d'une ville. En plus de ces châteaux, il y a la "Cour royale", qui est une grande structure de bâtiments interconnectés abritant des nobles en visite d'autres localités du Cormyr, ainsi que certains membres officiels de la Cour royale. Un noble peut avoir trois résidences ou plus : une à la Cour royale, un château proche de celui du roi et une résidence dans une autre ville dont il peut être le seigneur.

Il existe 25 grandes familles nobles, qui ont tendance à se marier entre elles. Cela complique parfois la lignée royale. Presque tous les membres des grandes familles nobles peuvent prétendre au trône. Si le roi et ses héritiers immédiats venaient à mourir subitement, il y aurait presque certainement un conflit pour déterminer l'héritier légitime, malgré le fait que des registres généalogiques méticuleux soient tenus.

Les nobles naissent, on ne les fabrique pas. Les exceptions à cette règle sont les seigneurs locaux, qui sont des personnes nommées par le roi pour gouverner une ville ou un groupe de villes au nom du roi.

La personne nommée à ce poste est généralement un membre des familles nobles et quelqu'un en qui le roi a confiance, mais il arrive que la personne nommée soit quelqu'un que les habitants de la ville ont recommandé ou qui est le chef de la ville par défaut, peut-être après être devenu la personne la plus influente d'une nouvelle ville, par exemple. (C'est l'une des façons pour les marchands de devenir membres de la classe noble au Cormyr).

Un seigneur local doit être un noble. Par conséquent, lorsqu'il choisit un seigneur local, le roi lui accorde un titre de noblesse (s'il n'en possède pas déjà un). Quel que soit le titre ou le pouvoir du noble, cette personne est toujours connue comme le seigneur de sa ville. Quels que soient le pouvoir et l'influence que Myrmeen Lhal peut acquérir ou perdre au fil des ans, elle sera toujours connue comme le Seigneur d'[[Arabel]] jusqu'à ce qu'elle n'occupe plus cette fonction. (Le titre n'indique pas le sexe de la personne ; les hommes et les femmes sont tous appelés "Seigneur").

Le roi nomme également des nobles à diverses fonctions au sein de la cour royale. Il s'agit généralement de postes gouvernementaux. Les postes les plus importants sont ceux de conseiller de la cour, où un noble a l'oreille du roi et peut réellement influencer l'histoire du Cormyr par sa sagesse (ou, rarement, par ses petits objectifs personnels).

Lorsqu'un noble ou un seigneur local trahit la confiance du roi ou de ses collègues nobles, il n'est pas déchu de son titre. (Cela signifierait que le roi a pris une mauvaise décision en accordant le titre en premier lieu, et ne laissez jamais dire qu'un roi du Cormyr prend de si mauvaises décisions). Au lieu de cela, cette personne est envoyée pour remplir une tâche obscure au nom du roi. Il s'agit généralement d'une tâche militaire à la frontière, comme passer l'hiver à [[High Horn]] avec les Dragons Pourpres ou veiller à l'entretien de la marine impériale à [[Marsember]] pendant l'été.

## Relations entre les classes

Le Cormyr a la réputation d'être plutôt snob parmi les autres royaumes. La perception est que les citoyens du Cormyr pensent que leur royaume est meilleur que les autres royaumes en raison de leur système de gouvernement.

Ce sentiment de supériorité du royaume se retrouve dans la structure des classes. Voici une brève explication de la façon dont chaque classe perçoit les autres. Pour plus de détails, voir les chapitres "La classe dirigeante", "Les gens du peuple" et "Les militaires".

### Les nobles

Les nobles ont généralement le sentiment d'être supérieurs à ceux qui leur sont "inférieurs". Cependant, l'origine de ce sentiment a moins à voir avec la naissance et le droit divin qu'avec la responsabilité de la position de la noblesse et son importance dans la société cormyrienne.

Un noble peut dire : "Je suis né dans cette situation. Bien que ma chair ne soit pas meilleure que celle d'un fermier, ma responsabilité envers mes sujets et mes collègues nobles me rend plus important que ce fermier."

Les nobles remplissent diverses fonctions dans la société cormyte, en particulier les seigneurs locaux. Leur responsabilité première est de réaliser les visions et les objectifs du roi. Cela s'étend aux fonctions quotidiennes et place donc les nobles à la tête de pratiquement toutes les activités du royaume.

Les nobles occupent tous les postes de direction. Toutefois, si un roturier devait assumer une fonction importante dans la société cormyte, il serait intégré à la cour royale en tant que noble.

Par conséquent, les nobles ne fréquentent que les salles du pouvoir et ne voient que rarement les gens qu'ils gouvernent. Les sorciers de guerre chevronnés et les jeunes nobles qui aiment chasser et explorer leur royaume font exception à cette règle.

Cet état de fait a provoqué une véritable fracture dans la société cormyte. Les nobles considèrent généralement les roturiers comme des personnes qui ne serviront pas à grand-chose. C'est pourquoi les préoccupations des roturiers ne reçoivent pas autant d'attention que celles des nobles.

De nombreux nobles du Cormyr, en particulier les personnes âgées et les femmes, passent presque tout leur temps à [[Suzail]], où chaque famille noble possède une grande résidence aussi proche que possible du palais. La plupart des nobles passent leur vie à [[Suzail]] ou dans leurs propres domaines et ne voient pas beaucoup la campagne. Cela les empêche de se rendre compte par eux-mêmes de la situation réelle du royaume. Ils s'appuient sur les informations fournies par les seigneurs locaux. Ce sont les nobles qui sont "avec le peuple" du Cormyr et qui sont les plus fiables pour témoigner de la situation du royaume. Cela creuse le fossé entre les nobles et la population en général et accro"t l'importance des seigneurs locaux.

### Les seigneurs locaux

Il existe une sous-classe qui s'écarte des règles habituelles pour les nobles. Il s'agit des seigneurs locaux qui gouvernent les villes et les villages au nom du roi.

Ces individus sont en contact quotidien avec les gens qu'ils gouvernent et sont intimement liés à eux à tous les niveaux. Même si le seigneur local réside dans un donjon séparé des sujets par des murs et des conventions sociales, toutes ses décisions affectent les habitants de la ville, dont les actions affectent à leur tour le seigneur.

En outre, les seigneurs locaux sont responsables de l'entretien des routes, du renseignement sur les forces hostiles et du maintien de la paix dans les villes et les villages.

La tâche la plus importante des seigneurs locaux est de collecter les impôts pour le roi. Dans cette tâche, certains seigneurs sont naturellement plus fervents que d'autres, mais tous se rendent compte qu'ils doivent gouverner leurs villes avec sagesse pour que les citoyens soient en mesure de payer les impôts que le roi attend. Le taux d'imposition général pour chaque citoyen est de 1 sp par an. En tant que collecteurs d'impôts du roi [[Azoun IV Obarskyr|Azoun]], chaque seigneur peut garder jusqu'à 40 hommes d'armes et jusqu'à six capitaines (typiquement des rangers connaissant bien la campagne autour de la ville).

Une tâche mineure à laquelle les seigneurs locaux doivent veiller est l'entretien d'un cheval rapide à l'usage des messagers du roi. Ce cheval n'est jamais utilisé que par un messager du roi ou, en cas d'urgence, par le roi lui-même.

Les seigneurs locaux qui veulent conserver leur pouvoir doivent être populaires auprès des citoyens. Il est arrivé plus d'une fois que les citoyens d'une ville chassent par la force un seigneur qui ne veillait pas à leurs intérêts.

En même temps, certains nobles méprisent les seigneurs locaux pour leur implication dans les "petites affaires des gens du peuple".

### Les gens du peuple

Toute personne qui n'est ni noble ni seigneur local est considérée comme roturière.

Les nobles accompagnent le roi dans [[Suzail]] et le conseillent sur ce qu'il faut faire. Les seigneurs locaux mettent en œuvre les décisions du roi et, à la fois, soutiennent le roi et protègent le peuple.

Les gens du peuple, cependant, sont la véritable force du royaume. Ils forment les Dragons Pourpres, les milices et les fermiers qui nourrissent le royaume.

La tradition du Cormyr, fortement soutenue par [[Azoun IV Obarskyr|Azoun IV]], veut que tous les roturiers puissent s'adresser librement à n'importe quel noble, ou au roi lui-même, sur n'importe quel sujet de préoccupation, et qu'ils s'attendent à être entendus et à recevoir une réponse aussi polie que s'ils s'asseyaient eux-mêmes sur le trône des Dragons Pourpres.

# La classe dirigeante : La monarchie et la noblesse

Le roi [[Azoun IV Obarskyr|Azoun IV]] (LG hm F20) a régné sur le Cormyr pendant 71 générations.

## La famille royale

Le roi [[Azoun IV Obarskyr|Azoun IV]] est le fils de Rhigaerd II et de Tanalusta [[Truesilver]], tous deux décédés. Il est né en 1307 DR, cinq ans après sa sœur Sulesta, elle aussi décédée.

[[Azoun IV Obarskyr|Azoun]] allie l'apparence d'un roturier à un comportement royal. Homme trapu aux cheveux bruns grisonnants et à la barbe fournie, [[Azoun IV Obarskyr|Azoun]] a l'esprit vif et le sourire facile, et le rire n'est jamais loin de ses lèvres. Malgré cette apparence, [[Azoun IV Obarskyr|Azoun]] est prudent et pratique dans son rôle de dirigeant, et ses goûts de luxe n'ont pu être cultivés que grâce à un revenu royal.

[[Azoun IV Obarskyr|Azoun]] est rarement seul, souvent en compagnie de l'un de ses proches conseillers et presque toujours en présence de ses gardes du corps personnels, six combattants de 8e niveau. Les biens les plus précieux du roi sont sa vaste collection d'épées magiques et les objets magiques qu'il porte sur lui, notamment des anneaux et des bracelets qui lui confèrent une immunité contre les attaques. Il est également réputé pour posséder un sort lui permettant de se téléporter en cas de grave danger.

La reine d'[[Azoun IV Obarskyr|Azoun]] est Filfaeril Selazair, de quatre ans sa cadette. Ils ont eu trois enfants : Foril, le fils qui est mort à l'âge de 2 ans, et deux filles : Tanalasta, née en 1334, et Alusair Nacacia un an plus tard. Tanalasta est une proche conseillère du roi. Tanalasta est une aide précieuse pour le roi, accomplissant de nombreuses tâches officielles en son nom. Elle dédaigne le mariage et rejette tous les courtisans.

Déterminée à se forger sa propre vie, la rebelle Alusair s'est enfuie de la cour royale du Cormyr. Elle vécut de nombreuses aventures et revint au Cormyr plus avisée des coutumes de Faerun que bien des aventuriers. Alusair a brandi l'épée lors des guerres de Tuigan, se montrant si avide de combats et si capable dans la mêlée que beaucoup au Cormyr voient en elle un futur chef des Dragons Pourpresó ou même du royaume tout entier. Parmi les roturiers et les Dragons Pourpres, elle n'est dépassée que par [[Azoun IV Obarskyr|Azoun]] en termes de respect.

[[Vangerdahast Aeiulvana]], le magicien royal du roi et chef du Conseil des mages, n'est pas un parent de sang mais fait quasiment partie de la famille. Les deux sont très proches et le roi ne prend aucune décision sans consulter son mage. [[Vangerdahast Aeiulvana]] est loyal envers [[Azoun IV Obarskyr|Azoun]] et Cormyr. [[Vangerdahast Aeiulvana]] a élevé [[Azoun IV Obarskyr|Azoun]] et a été le tuteur de ses deux filles.

Au début de son règne, [[Azoun IV Obarskyr|Azoun]] a renoncé à parcourir son royaume sous un déguisement, ce qu'il avait fait dans sa jeunesse en tant que membre d'un groupe d'aventuriers connu sous le nom d'Hommes du Roi. La campagne pour vaincre Gondegal (voir p. 32) a fait prendre conscience au roi qu'il s'était éloigné de ses sujets, et lorsque la campagne s'est terminée, [[Azoun IV Obarskyr|Azoun]] a repris ses incursions secrètes dans les villes et les villages du Cormyr.

Grâce à ces excursions, [[Azoun IV Obarskyr|Azoun]] connaît ses sujets bien mieux que la plupart des souverains de Faer˚n. Il est sensible à leurs besoins et à leurs préoccupations, et il lui arrive souvent d'adapter la politique de l'État pour corriger les maux qu'il découvre au cours de ces escapades. [[Azoun IV Obarskyr|Azoun]] est déterminé à faire du Cormyr le royaume le plus sûr et le plus pacifique possible.

Pour que ces incursions à partir de [[Suzail]] soient couronnées de succès, le roi sollicite l'aide d'Alusair et de Vanger- dahast. Alusaïr fait en sorte que les affaires du roi soient réglées pendant un certain temps en combinant des interruptions régulières de l'activité avec des affirmations selon lesquelles le roi est malade, a une affaire de famille à régler ou n'est pas disponible pour le reste de la cour pour d'autres raisons.

Pendant ce temps, [[Vangerdahast Aeiulvana]] utilise la magie pour changer la forme du roi et lui donner la forme qu'il souhaite. En général, le roi prend la forme d'un aventurier. Il s'échappe de [[Suzail]] la nuit et pénètre dans la campagne en "homme libre".

Pendant son séjour, il se contente de visiter les lieux qu'il souhaite voir de ses propres yeux et d'évaluer la situation sur place. Par le passé, il s'est rendu jusqu'à [[Tilverton]] et [[High Horn]], pour y observer la scène militaire, et à [[Marsember]] lorsque l'activité des pirates était en hausse.

Lorsque le roi effectue de tels voyages, il le fait parfois à l'aide d'un anneau magique qui lui permet de se téléporter aux endroits qu'il désire. Il utilise presque toujours l'anneau la nuit pour réduire le risque que quelqu'un le voie se téléporter. En cas d'urgence, le roi se téléporte à [[Suzail]], quelle que soit la personne qui le voit faire.

Jusqu'à présent, le déguisement du roi n'a pas été percé. Mais des rumeurs circulent au sein de la cour royale sur la façon dont le roi effectue ces voyages au-delà des murs de la ville et dans la campagne. Pour étouffer ces rumeurs, le roi a pris soin de demander à quelqu'un d'établir un alibi pour ses absences. Sa femme et ses filles participent le plus souvent à cette entreprise. Cependant, le roi préfère que ses nobles croient qu'il acquiert sa connaissance intime du Cormyr en faisant des voyages incognito en dehors de [[Suzail]] plutôt que de connaître son réseau d'espions opérant à l'intérieur du Cormyr - la seule autre façon d'expliquer comment le roi est capable de voir à travers les tentatives de tromperie de certains nobles (sauf à [[[[Eveningstar]]|[[Eveningst]]ar]], où la plupart des villageois connaissent leur roi comme un ami personnel).

En tant que souverain, le roi s'est montré très compétent, surtout depuis l'incident de Gondegal. Il y a eu un autre épisode militaire, bref, au cours duquel il a organisé la croisade contre la horde des Tuigans en 1360 J.-C. Le roi a de nouveau dirigé personnellement ses troupes. Le roi a de nouveau dirigé personnellement ses troupes et, lorsque le sang a coulé, il s'est engagé dans la mêlée et a défié le chef de l'ennemi en combat singulier, qu'il a remporté.

## Les familles nobles

De la lignée originelle de la noble famille régnante du Cormyr, il ne reste que le roi [[Azoun IV Obarskyr|Azoun IV]], ses deux filles et ses cousins au troisième degré, le duc Bhereu et son frère Thomdor. Le roi partage avec ces deux hommes une détermination à toute épreuve. Ce sont des hommes costauds, moustachus, pour qui l'épée, l'armure et la selle sont des choses familières. Bhereu est le grand maréchal du royaume, le commandant des Dragons Pourpres et un soldat endurci. Sa loyauté envers la couronne ne peut être ébranlée, même par la magie (les sorciers ont essayé). Lorsque le Cormyr est en paix, il voyage fréquemment entre [[High Horn]], [[Castle Crag]] et la Citadelle de [[Suzail]], gardant ses troupes alertes et satisfaites. Lorsqu'il chevauche, rien n'échappe à son regard gris, calme et uniforme.

Thomdor siège à la Cour royale, où il supervise la collecte des impôts des principales villes du Cormyr. Thomdor semble aimer travailler avec les chiffres et c'est un bon gestionnaire qui exerce son autorité comme il se doit.

Un irritant constant pour Thomdor est Sarp Barbe-Rouge, le seigneur de [[Wheloon]]. Les registres de Barbe-Rouge sur le nombre de personnes vivant dans son domaine sont notoirement vagues. En conséquence, le montant des impôts que Barbe-Rouge paie à la couronne fluctue. Thomdor pense que Barbe-Rouge a des intentions honorables ; il n'écrase pas l'argent pour lever sa propre armée privée ou quoi que ce soit de ce genre. C'est juste que Barbe-Rouge tient mal ses comptes.

## Nobles importants

Voici quelques personnages importants du Cormyr, des personnes qui jouent un rôle dans le gouvernement de la nation.

### [[Vangerdahast Aeiulvana]]
### [[Alaphondar]]

## Autres familles nobles

Il existe de nombreuses familles nobles dans le Cormyr. Voici une brève description des plus importantes d'entre elles.

### [[Bleth]]
### [[Cormaeril]]
### [[Crownsilver]]
### [[Dauntinghorn]]
### [[Emmarask]]
### [[Hawklin]]
### [[Huntcrown]]
### [[Huntsilver]]
### [[Illance]]
### [[Marliir]]
### [[Rowanmantle]]
### [[Silversword]]
### [[Truesilver]]
### [[Wyvernspur]]

## Seigneurs du Cormyr

Le roi gouverne par l'intermédiaire de seigneurs nommés, un dans chaque ville, et par la fidélité de la noblesse terrienne et des riches seigneurs marchands. La noblesse terrienne est nombreuse et métissée, de sorte que la plupart peuvent revendiquer une ou deux gouttes de sang royal dans leurs veines. Les seigneurs marchands sont les propriétaires de caravanes et d'entreprises les plus riches de l'époque et changent au gré de la fortune.

Chaque seigneur local est chargé de défendre les fermes locales, de rendre la justice du roi, de maintenir la paix, d'être les yeux et les oreilles du roi et (surtout) de collecter la dîme pour le roi et pour lui-même (1 sp/tête/an). Le seigneur doit également entretenir un cheval en bonne santé, rapide et de la meilleure qualité pour les messagers du roi (qui voyagent vite et loin, ce qui les oblige à changer de monture à chaque arrêt).

Chaque seigneur a droit à un maximum de 40 hommes d'armes, plus un maximum de six guides/capitaines (généralement des rangers). Ces derniers peuvent faire office de garde de la ville. Les gardes volontaires de la ville sont connus sous le nom de Guet, et le seigneur peut les exempter de la taxe si leurs services ont été précieux.

Les relations entre la noblesse terrienne et les seigneurs locaux désignés sont généralement bonnes, bien que de nombreuses familles établies traitent les serviteurs locaux de la couronne comme de simples laquais royaux, qu'il faut diriger ou flatter selon les besoins.

Les noms des seigneurs locaux et des hérauts (leurs assistants) sont indiqués pour chaque ville et village.


# Les gens du peuple

Si vous n'êtes pas un noble, un seigneur local, un membre de l'armée, un mage ou un aventurier, vous êtes généralement considéré comme un roturier.

## Paysans

Les fermiers du Cormyr constituent sans doute le groupe de personnes le plus stable de Faerun. Le Cormyr lui-même est conservateur et civilisé, et l'agriculture, la plus grande occupation du Cormyr, est le fondement de ce conservatisme. Le fermier typique du Cormyr mène une vie simple, cultivant des terres généralement assez éloignées de toute ville d'importance. Les paysans cormyriens sont plus loyaux envers la couronne et plus unis entre eux que les paysans d'autres régions.

### Loyauté

Les paysans sont extrêmement loyaux envers le roi du Cormyr. Ils se portent volontiers volontaires pour rejoindre les Dragons Pourpres en cas d'urgence, comme ce fut le cas lorsque Gondegal menaça de briser le Cormyr. S'il existe une plus grande loyauté dans leur vie, c'est envers leur famille et leur communauté. Le fermier du Cormyr, bien qu'il vive souvent loin d'une ville, est très fier et s'intéresse à ce que sa ville natale peut accomplir avec son aide.

### Unité

Les fermiers se soutiennent mutuellement dans leurs besoins et leurs intérêts, comme aucune autre guilde ou classe ne le fait. Leur existence est si fragile et dépendante du climat économique et politique, ainsi que de la météo, qu'ils s'unissent pour des questions d'intérêt personnel.

Par conséquent, lorsqu'un seigneur local ou un noble de [[Suzail]] tente de promulguer une loi ou un décret préjudiciable à un seul fermier, tous les fermiers s'opposent d'une seule voix. En général, le bien-être des seigneurs et des nobles locaux dépend de la réussite des fermiers locaux, aussi agissent-ils rarement à l'encontre des souhaits des fermiers une fois que la position de ces derniers est connue.

Sarp Redbeard de [[Wheloon]] est un seigneur populaire parmi les fermiers. Il agit souvent indépendamment de [[Suzail]] et se range généralement du côté des fermiers. De nombreux paysans vivent dans le domaine de Barbe-Rouge.

### Festivals

Le festival de la ville est au cœur de la vie d'un fermier. Il y a de nombreux festivals tout au long de l'année dans toutes les villes du Cormyr, dont beaucoup célèbrent l'agriculture ou un de ses aspects, comme la récolte.
Cependant, pour un fermier, un festival n'est pas seulement l'occasion de faire la fête, mais aussi de parler avec d'autres fermiers de questions d'intérêt commun, de nouvelles techniques et, bien sûr, du temps qu'il fait.

Bien qu'un festival soit une excellente occasion de se réunir, les festivals sont souvent le seul moment où les agriculteurs se rassemblent. Cela peut entraver les efforts visant à réagir rapidement à des situations telles que les inondations ou les feux de broussailles.

## Les artisans

Le Cormyr a une longue tradition d'artisans, respectés parce qu'ils sont doués par les dieux du talent de transformer les matériaux du monde en produits utiles ou décoratifs (ou les deux, dans les cas les plus raffinés).

Plusieurs villes du Cormyr sont des centres d'artisanat particuliers. Il y a une grande concentration d'artisans à [[Wheloon]], qui est connue pour ses artisans qui produisent des bateaux, des paniers, des voiles et des pots d'argile de qualité. [[Gray Oaks]] est réputé pour ses excellents artisans du bois.

Chaque ville possède généralement au moins une guilde d'artisans. Les guildes veillent aux intérêts de leurs membres, en luttant contre les taxes et en essayant d'améliorer les conditions de travail, les fournitures et les opportunités de vente.

Les guildes n'ont pas été particulièrement puissantes au fil des ans au Cormyr. Ici, les guildes ressemblent surtout à des organisations fraternelles bienveillantes : des groupes de personnes qui pratiquent le même métier et qui rejoignent l'organisation pour l'interaction sociale et la possibilité d'améliorer leur expertise. La plupart des chefs de guilde sont satisfaits de savoir que leurs organisations donnent à leurs membres un sentiment de camaraderie et un lieu où ils peuvent perfectionner leur art parmi leurs pairs. Le concept de "syndicat" est pratiquement inconnu au Cormyr.

Presque inconnu, parce que les guildes de la construction - maçons, tailleurs de pierre, menuisiers, etc. - ont en effet découvert le degré d'influence qu'elles peuvent exercer sur la politique locale. Ces guildes veillent généralement avec passion à leurs propres intérêts et savent manipuler les situations à leur avantage.

## Marchands

La classe la plus puissante en dehors des nobles, les marchands sont l'énergie qui fait tourner les roues de l'économie et du progrès au Cormyr.

Dans de nombreuses sociétés où il y a une classe noble dirigeante et une classe inférieure "commune", une classe de marchands s'élève pour devenir aussi puissante que les nobles. C'est le cas au Cormyr, où les marchands sont devenus très puissants et leurs richesses éclipsent certainement celles de certaines familles nobles.

Ce qui distingue le marchand cormyrien des autres, c'est que chaque marchand est d'abord un citoyen du Cormyr et ensuite un marchand.

Cette loyauté envers le royaume signifie qu'un mer- chant s'inclinera presque toujours devant les intérêts supérieurs des nobles et du roi en particulier. Il ne lui viendrait pas à l'idée de mettre en péril le Cormyr pour ses propres intérêts. Une partie de cette loyauté découle certainement de l'appréciation des marchands pour l'environnement commercial favorable entretenu par leurs dirigeants.

Si les nobles et les marchands entretiennent de bonnes relations, il n'en va pas de même au sein de la classe marchande. Il n'y a pas de concurrence plus forte qu'entre deux marchands cormytes.

### Les marchands en politique

Bien que les nobles soient au sommet de la pyramide du pouvoir, les marchands exercent une influence considérable, qui ne cesse de croître.

Un exemple de l'influence des marchands se produit lorsqu'une maison de marchands voit une famille noble en difficulté. Cette famille peut avoir subi de lourdes pertes ; par exemple, une catastrophe naturelle peut avoir ruiné les terres agricoles de la famille, rendant les revenus fiscaux nettement inférieurs à ce qui était prévu. Une maison de marchands interviendra souvent et proposera secrètement de compenser la perte de recettes fiscales en échange d'un certain contrôle en coulisses d'un poste détenu par un membre de la famille en difficulté.

La plupart des interventions de ce type concernent l'attribution d'espaces aux entrepôts dans les villes fortifiées (sauf à [[Suzail]], où le Lord Magister est apparemment incorruptible) et d'autres questions de ce genre.

### Les marchands et l'expansion des cormytes

L'effort le plus récent pour apprivoiser la Forêt de Hullack et ouvrir une nouvelle voie de ressources a commencé par une expédition de marchands.

Les marchands sont les meilleurs indicateurs des besoins de Cor- myr en termes de ressources telles que le bois et le métal. Personne d'autre, pas même les militaires, ne consomme autant que toutes les maisons marchandes réunies.

Par conséquent, lorsque les maisons marchandes commencent à chercher sérieusement à obtenir plus de ressources, la couronne s'en aperçoit, car cela signifie que l'armée et les autres agences officielles ne tarderont pas à connaître des pénuries.

La denrée la plus rare est la terre agricole. Il y a un besoin constant de terres agricoles, et les mer- chants reconnaissent que les terres agricoles sont un atout précieux. Elles représentent non seulement un approvisionnement régulier en nourriture et les revenus qui en découlent, mais aussi des revenus locatifs et des impôts pour la Couronne. Plus on paie d'impôts, plus on a d'influence sur la couronne.

Les compagnies marchandes financent le plus grand nombre de groupes d'exploration et d'aventure. Les expéditions d'exploration servent à recueillir des informations sur un lieu susceptible d'être cultivé et acquis.

### Expansion vers la mer

Les contacts du Cormyr avec les autres royaumes sont principalement dus à l'activité et à l'influence des marchands. Ce sont les cargaisons d'ivoire en provenance de contrées lointaines qui ont attiré l'attention du Cormyr sur les affaires au-delà de ses frontières. Malheureusement, la présence de navires marchands cormytes dans le lac des Dragons a augmenté l'activité des pirates, rendant le lac plus dangereux.

De nombreuses rumeurs affirment que les pirates du lac sont en fait des navires marchands concurrents déguisés. Il n'y a aucun moyen d'étayer ces rumeurs sans capturer un navire pirate et interroger le capitaine, ce qui n'a pas encore confirmé ces rumeurs.

Les navires de la marine impériale escortent parfois les navires marchands dans leurs allers-retours vers le Neck. Ayesunder [[Truesilver]], directeur du port de [[Marsember]], décide quels navires marchands doivent être escortés, et on a accusé ses choix d'être souvent motivés par des considérations politiques.

## Folk of Cormyr

Les personnes citées ici sont loin d'être les seuls personnages importants du Cormyr. En effet, Volo a évité autant que possible les maisons nobles et les membres de la cour royale et s'est concentré, comme à son habitude, sur les personnes susceptibles d'intéresser les voyageurs, les voyous et les aventuriers. Seules quelques-unes de ces personnes lui ont accordé l'heure du jour, de sorte que ce qui apparaît ici peut être considéré comme une liste très incomplète de noms qui comptent dans le Cormyr d'aujourd'hui.

Avec l'aide d'Elminster, les niveaux probables et autres statistiques de jeu de ces êtres ont été estimés, et des détails personnels supplémentaires ont été ajoutés. Ces informations étant récentes, les statistiques publiées ici ont la priorité sur les informations publiées antérieurement. Les personnes sont classées par ordre alphabétique de leurs prénoms, car de nombreux habitants du Cormyr n'ont pas de nom de famille. Les surnoms et les titres sont ignorés lorsqu'il s'agit de classer un nom par ordre alphabétique.

![[AMBRATHA SUREN]]  
![[ARGUL MARAMMAS]] 

![[ASHEYRON THE LEARNED]] 

![[BAERELUS THE BOLD]]

![[BARANDOS HAWKLIN]]

![[BASKOR TRANTH]]

![[BLENTRA WHAELBUCKLER]]

![[DELTHRIN THE DEADMASTER]]

![[DRAGUTH ENDROUN]]

![[DUNMAN KIRIAG]] 

![[ELESTRA BLAEBUR]] 

![[ENDARTHAR of Wildwoods]] 

![[FILANI of Tantras]] 

![[FILFAERIL STORMBILLOW]] 

![[GAHLAERD MOSSMERE]]

![[IYRYTHARNA DANTRAS]]

![[JESTRA]] 

![[LASPEERA NAERINTH]] 

![[MAERUN STOUTBOLD]]

![[MAXER HLARR]]



![[MELLOMIR of Arabel]]

![[MYSCHANTA HALARRA]]

![[ORBRIL of Skull Crag]]

![[PERAPHON THOND]]

![[RULDAN NYSGART]]

![[SASZESK]] 

![[SZWENTIL ILLEON]]

![[THEAVOS THONTAR]]

![[THENTLAS]]

![[TONGRETH of Marsember]]

![[TSHARLURA of Blackthorne]]

![[UNGATHROS of Mistrim]]

![[VALANTHA SHIMMERSTAR]]

![[VINDALA CHALANTHER]]

![[WENDEIRA ILLATHOS]]

# Les militaires

Pour faire respecter la parole royale, le Cormyr dispose d'une importante armée permanente, qui a considérablement augmenté au cours de la dernière décennie. Plus de 12 000 Dragons Pourpres (appelés ainsi en raison de leur bannière) sont en garnison dans les principales villes et fortifications. Une marine impériale de 25 navires patrouille le lac des Dragons, la garde du palais compte 150 guerriers d'élite entraînés, et la nation entretient une force montée de 500 guerriers entraînés à l'épée et à l'arc, dirigée par 30 chevaliers de la cour royale. La plupart de ces unités d'élite sont des vétérans de la croisade contre la Horde et sont membres de l'Ordre de la Voie Dorée, une récompense militaire commémorant ces batailles. Mais l'unité la plus meurtrière de l'armée est celle des redoutables sorciers de guerre, une unité de magiciens reconnaissables à leurs robes noires et violettes.

## Les dragons pourpres

Le grand maréchal du royaume, le duc Bhereu, commande l'armée permanente du roi.

### Tactique

Tout au long de l'histoire du Cormyr, l'armée a mené peu de batailles rangées. D'un point de vue historique, les Dragons Pourpres utilisent des tactiques de guérilla, en frappant rapidement des zones ou des concentrations ennemies sensibles et en se déplaçant rapidement vers un autre endroit.

De nombreux adversaires des Dragons Pourpres utilisent des tactiques similaires. Le duc Bhereu croit fermement qu'il faut garder ses forces aussi mobiles que possible pour éviter que ses hommes ne tombent dans une embuscade ou ne soient débordés. Le duc Bhereu considère qu'une armée permanente qui combat à l'ancienne, avec des champs de bataille préétablis et des lignes d'hommes soigneusement organisées pour se faire face, est une invitation au désastre.

Avant que Bhereu n'ait établi sa réputation, ses tactiques ont été remises en question et jugées peu honorables. Les résultats de la tactique - les avantages du faible taux de pertes et l'efficacité et la rapidité avec lesquelles les objectifs sont atteints - ont fait taire toutes les critiques concernant le respect des règles ancestrales de la guerre.

### Missions

La mission de l'armée du roi [[Azoun IV Obarskyr|Azoun]] est simple : défendre le Cormyr. La réalisation de cet objectif est cependant complexe.

### Stonelands

La menace la plus importante qui pèse sur les frontières du Cormyr vient des Stonelands, une zone de terres rocheuses, de vallées escarpées, de plateaux et d'autres terrains confus et hostiles. Cette topographie constitue une cachette idéale pour les bandits, les monstres et autres êtres malfaisants.

Depuis des décennies, les pillards des Stonelands harcèlent les intérêts des Cormytes. Les caravanes qui empruntent la route entre [[Tilverton]] et [[Castle Crag]] sont particulièrement menacées.

La garnison de [[Castle Crag]] garde le col des Gnolls contre les raiders frontaliers venant des Marches des Gobelins, mais ne peut pas faire grand-chose pour protéger le trafic sur la Chevauchée de la Lune.

Le Cormyr a occupé [[Tilverton]] en 1357 J.-C., a déclaré [[Tilverton]] comme protectorat et y a stationné 850 Dragons Pourpres.

Ces troupes effectuent désormais régulièrement des patrouilles dans les Stonelands afin de débarrasser la région des monstres et des bandits. Jusqu'à présent, les résultats sont mitigés. Il y a toujours des raids sur les caravanes et on signale encore des forteresses de monstres dans les Stonelands, mais il ne fait aucun doute que l'activité des bandits organisés a diminué de façon sub-stantielle. Cette situation pourrait toutefois changer à l'avenir, car les Zhentarim et d'autres tentent d'organiser les éléments criminels des Stonelands contre les Dragons Pourpres.

### Marches des gobelins

Cette région située au nord du Cormyr constitue une menace pour la sécurité des Cormytes depuis les débuts du royaume. Aujourd'hui, les Marches des Gobelins ne sont plus que l'ombre de la menace qu'elles représentaient autrefois.

Il y a longtemps, les marches étaient remplies des troupes d'un empire gobelin organisé qui menait des raids réguliers jusqu'au sud de [[Suzail]], qui était alors un groupe de bâtiments presque sans défense.

Au fur et à mesure que le Cormyr s'est développé, il est devenu plus efficace pour repousser les raids des gobelins. Avec la création de [[Castle Crag]], le Cormyr mit fin aux raids gobelins loin au sud du Cormyr. [[Castle Crag]] devint le site militaire le plus important du Cormyr.

Au fil du temps, le désert d'Anauroch s'étendit, perturbant la vie de l'empire gobelin. L'empire commença à se désagréger et les factions émigrèrent vers d'autres régions ou se dissipèrent. L'importance de [[Castle Crag]] diminua au fur et à mesure que la menace gobeline s'estompait.

Aujourd'hui encore, [[Castle Crag]] se dresse en sentinelle contre les raids des bandes de gobelins ou d'autres démihumains. Le château abrite environ 500 dragons pourpres et un détachement de sorciers de guerre.

Cette force a empêché la progression de toute tribu gobeline jusqu'à présent, mais des problèmes se profilent à l'horizon pour Crag. Les Zhentarim recrutent des bandes de gobelins pour les mettre au service des Zhentarim contre d'autres tribus des Marches des Gobelins et contre des groupes de raiders. Si cette armée devenait suffisamment puissante et organisée, elle constituerait une menace sérieuse pour le Cormyr.

### [[High Horn]]

Les pillards frontaliers étaient autrefois un problème constant. Ils arrivaient par l'ouest, en passant par un col dans les montagnes de Stormhorn, et attaquaient des villes comme [[Tyrluk]], [[Eveningstar]] et même [[Arabel]].

La [[High Horn|Haute Corne]] a été construite pour empêcher ces raids. Il s'agit d'un vaste complexe de murs et de bâtiments pouvant abriter la moitié de l'armée permanente du Cormyr. Environ 400 dragons pourpres y sont stationnés, en plus des sorciers de guerre et d'autres forces mal placées.

Depuis la fondation de [[High Horn]], les raids frontaliers à travers les Stormhorns ont pratiquement cessé.

### Maintenir la paix

Une des fonctions importantes des Dragons pourpres est d'assurer la paix dans tout le royaume.

Cela signifie que l'intérieur du Cormyr doit rester à l'abri des raids, afin qu'une compagnie marchande ou un fermier puisse voyager en toute sécurité et rentrer chez lui avec des bénéfices intacts.

À cette fin, les Dragons Pourpres ont connu un grand succès. Certes, les Dragons Pourpres ne peuvent pas être partout à la fois, et il y a toujours la menace d'une attaque aléatoire de bandits quelque part dans le Cormyr, mais le royaume a la réputation d'offrir des voyages sûrs dans l'ensemble.

Les Dragons Pourpres sont également chargés de prévenir les insurrections internes. Il n'y a eu qu'un seul cas où les Dragons Pourpres ont dû réprimer une insurrection, lorsqu'ils ont mis fin à la révolte de Gondegal sans effusion de sang.

### Aventuriers du Cormyr

Le maintien de la paix à Cor- myr passe par la surveillance des "francs-tireurs" pour s'assurer qu'ils ne créent pas d'ennuis.

Les Dragons Pourpres sont particulièrement attentifs aux groupes de personnes qui errent dans la campagne avec leurs propres armes et leurs propres projets. Les groupes d'aventuriers sont peut-être les plus dangereux, car ils ont leurs propres missions, viennent souvent de contrées lointaines et se soucient peu du bien-être du Cormyr.

La coutume qui consiste à attacher une corde à la poignée et au fourreau de son épée est en fait une loi appliquée par les Dragons Pourpres. Si les Dragons Pourpres aperçoivent des personnes portant des armes qui ne sont pas liées à la paix, ils les arrêtent et les informent de la "coutume" du Cormyr. Si les individus armés ont été engagés par une compagnie autorisée à engager des mercenaires, ils peuvent porter des armes non liées mais doivent présenter une preuve de leur emploi et de leur employeur (généralement un parchemin portant la marque de la compagnie et le nombre d'individus engagés en tant que groupe, ainsi que le nom du chef du groupe).

Les Dragons Pourpres sont autorisés à emprisonner les contrevenants et à saisir leurs biens. Notez que les aventuriers char- tés sont autorisés à porter des armes non liées dans le Cormyr. (Voir p. 63 pour plus d'informations).

### Forêt de Hullack

Les Dragons Pourpres ont la lourde responsabilité de nettoyer la forêt et de débarrasser la région des monstres. Une fois cette tâche accomplie, les habitants du Cormyr pourront exploiter la forêt et ses ressources en toute sécurité. Bien sûr, la forêt de Hullack est vaste et les dragons pourpres ne sont pas censés la défricher entièrement, mais ils sont chargés de défricher suffisamment de terrain chaque année pour permettre au Cormyr d'utiliser une partie des ressources de la forêt.

Les Dragons Pourpres ne sont pas seuls dans cette entreprise. Un certain nombre de compagnies marchandes souhaitent trouver leurs propres sources de bois frais. Ces compagnies ont engagé des aventuriers pour nettoyer des zones spécifiques infestées de monstres.

## La marine impériale

La mission première de la marine impériale est de protéger les navires cormyréens qui traversent le lac des Dragons pour aller et revenir du "Cou", le goulet qui relie le Cormyr à d'autres parties du monde par le biais de ce lac.

Le commerce d'épices et d'autres marchandises est très rentable pour le Cormyr et vaut certainement l'investissement dans la construction et la navigation des navires. Pour protéger ces navires des pirates, le Cormyr a stationné 12 navires de guerre dans son port le plus actif, Marsem- ber. A tout moment, il y a plus de navires de guerre amarrés à [[Suzail]], mais la plupart d'entre eux sont là pour protéger les familles nobles ou le roi personnellement.

Patrouiller le long de la côte du lac est la mission la plus courante de la marine impériale. Ayesunder [[Truesilver]] est le commandant de ces forces et est généralement considéré comme le chef de la marine cormyréenne. Il n'a cessé de faire pression sur le roi pour obtenir davantage de navires et de guerriers des mers afin de pouvoir patrouiller plus efficacement sur le lac. Malheureusement, l'attention militaire du roi s'est portée sur les Stonelands et les Marches des Gobelins.

## Milices locales

Chaque ville, aussi petite soit-elle, possède une milice chargée de maintenir la paix et d'assurer une défense d'urgence contre les attaques extérieures. Chaque bannière de milice est composée pour moitié du Dragon Pourpre et pour moitié de la bannière de la ville, divisée par fess (ver- tiquement). Normalement, c'est le seigneur de la ville qui commande sa milice.

Un aspect inhabituel des milices cormyréennes est que la plupart d'entre elles exigent que leurs membres sachent lire. L'écriture est facultative, mais chaque milicien doit être capable de lire les bulletins, les ordres, etc. de son seigneur local et de ses commandants. En outre, il y a toujours au moins une personne capable d'écrire dans tout détachement de milice qui quitte la ville.

Les aventuriers et les compagnies d'aventuriers non enregistrées constituent une menace importante pour les petites villes. Afin de prévenir les dommages et les ennuis causés par des comportements contraires à la loi, presque toutes les villes du Cormyr ont au moins un milicien à la frontière de la ville. Cette personne, généralement appelée "Intro- duceur", est chargée de présenter la ville et ses lois à ceux qui ne savent pas lire. L'Intro- duceur précise également que les comportements tapageurs causant des dommages à la propriété (qu'ils soient délibérés ou accidentels) entraîneront des peines d'emprisonnement et des amendes.

Au sein de la ville, les miliciens patrouillent dans les rues, surveillant tout particulièrement la principale cause de troubles : les voyageurs qui traversent la ville. La pire chose qu'un groupe ou une compagnie d'aventuriers puisse faire est peut-être d'amener des forces hostiles dans la ville.

Face à cette situation, les milices imposent généralement aux aventuriers de se mettre au service de la défense de la ville. La milice assigne alors aux aventuriers la tâche la plus dangereuse afin de minimiser les pertes locales.

Parfois, un village a la chance d'avoir un mage résident. Ces individus, en particulier ceux qui possèdent des magies ou des pouvoirs combatifs, sont automatiquement considérés comme faisant partie de la milice. Les sorciers de guerre qui se sont retirés pour poursuivre leurs propres objectifs sont des exemples typiques de "sorciers de ville". Il en existe un nombre surprenant, et même le plus petit hameau peut avoir un sorcier puissant quelque part.

# Le mage cormyte

Les mages sont respectés dans le Cormyr, considérés non pas comme des monstres mais comme des individus qui ont suivi un entraînement difficile pour apprendre les voies du magicien. Ils sont en quelque sorte de fins artisans, mais le matériau qu'ils sculptent est l'énergie magique.

Tout Cormyréen qui a vu un mage de guerre à l'œuvre sait à quel point les mages sont importants pour la vie quotidienne et la sécurité au Cormyr. En fait, lorsque les Cormyréens pensent aux mages, ils les associent généralement aux forces de l'ordre, qu'il s'agisse des mages de guerre ou de la milice locale.

## Les sorciers de guerre

Depuis la fondation du royaume, les mages ont joué un rôle important à Cor- myr, que ce soit dans la guerre ou dans d'autres domaines. Les mages les plus loyaux envers la couronne signent un accord avec le roi et prêtent un serment secret qui implique un sort de geas, devenant ainsi des mages de guerre. Ces mages font partie intégrante de l'armée du Cormyr, et ils sont respectés et craints dans tout le pays.

Seul [[Vangerdahast Aeiulvana]], magicien royal et président émérite du collège des mages de guerre, en connaît le nombre. En tant que chef, il préside les réunions des sorciers de guerre. En son absence, c'est [[LASPEERA NAERINTH|Laspeera]] (NG hf W14) qui le remplace.

Outre ces deux-là, le sorcier de guerre le plus connu est [[MAXER HLARR|Maxer]] (NG hm W (In) 11), qui a vaincu quatre dragons attaquant [[Suzail]], ce qui lui a valu le titre honorifique de "défenseur de [[Suzail]]" de la part du roi [[Azoun IV Obarskyr|Azoun]].

[[VALANTHA SHIMMERSTAR]] (CG hf W13) est également très connue. Elle a acquis sa renommée et sa notoriété, non pas grâce à ses exploits militaires, mais grâce à son chant magnifique et à sa propension à faire des bêtises lors des festivals et autres rassemblements.

### [[Vangerdahast Aeiulvana]] observe

[[Vangerdahast Aeiulvana]] surveille attentivement les activités de tous les mages du Cormyr. Tous les mages, à partir du niveau de thaumaturge (5e niveau), doivent se faire enregistrer auprès de la couronne.

L'enregistrement consiste à communiquer son nom, son sigil, sa demeure et ses allées et venues à [[Vangerdahast Aeiulvana]]. Il tient une énorme bibliothèque de noms de mages résidant au Cormyr et s'efforce de tenir ces listes à jour, même lorsque les mages oublient d'actualiser leur inscription. [[Vangerdahast Aeiulvana]] dispose d'un réseau d'espions, magiques ou non, pour surveiller les plus puissants des sorciers.

Pour vérifier l'exactitude de ses informations, [[Vangerdahast Aeiulvana]] effectue des visites surprises chez des mages puissants. Cela choque parfois les magiciens chevronnés qui se sont retirés pour vivre en reclus et qui n'avaient pas l'intention d'essayer de garder des secrets pour le magicien royal.

L'éventualité de telles visites s'est avérée un moyen de dissuasion efficace pour les mages qui pourraient faire passer leurs propres intérêts avant ceux du Cormyr.

## Le Conseil des Mages

[[Vangerdahast Aeiulvana]] dirige le célèbre Conseil des Mages, un groupe qui conseille le roi sur les questions relatives à la magie et aux menaces magiques au sein du royaume. Le roi fait aussi parfois appel au conseil pour faire des recherches sur une question particulière et trouver les informations dont le roi a besoin pour prendre une décision.

### Histoire

Le Conseil des mages a vu le jour au début du Cormyr lui-même. Lorsque [[Suzail]] et les communautés voisines s'établissaient en tant que groupe cohésif, elles étaient gênées par les attaques continuelles de toutes sortes de créa- tures provenant de ce que l'on appelle aujourd'hui la Forêt du Roi.

Les hommes d'armes n'étaient pas une protection suffisante. Le Cormyr naissant avait besoin de l'aide de la magie pour combattre ces bêtes.

Tous les mages connus furent alors rassemblés et ils élaborèrent un plan d'attaque n'utilisant que la magie, sans aucun fantassin. Leurs efforts furent couronnés de succès et le groupe de mages devint connu sous le nom de Sorciers de guerre, une composante permanente du Cormyr.

Les mages de guerre furent appelés à accomplir d'autres tâches pour le Cormyr. Ils devaient notamment créer des objets magiques pour le roi, mener des recherches et participer à l'exécution de divers sorts de guérison. Ils étaient également fréquemment appelés à combattre.

C'est pourquoi l'ensemble des mages fut divisé en deux groupes, le Conseil des Mages et les Sorciers de Guerre.

Aujourd'hui, les deux groupes sont essentiellement connus comme un seul et même groupe, mais [[Vangerdahast Aeiulvana]] et ses assistants sont connus comme le Conseil des Mages parce qu'ils combattent rarement directement autre chose que des mages voyous ou des monstres ou menaces extrêmement puissants.

Mage de guerre est un terme utilisé pour les mages qui se battent aux côtés des Dragons Pourpres, défendant les intérêts de la couronne au quotidien.

## Attitudes à l'égard des mages et de la magie

En raison de leur rôle important dans la défense du Cormyr, les mages jouissent d'un grand respect et d'une grande admiration de la part de la population. Mais en raison de leur grand pouvoir et de son caractère mystérieux pour le commun des mortels, les sorciers de guerre et les autres magiciens inspirent également une grande crainte dans le pays.

Si le Conseil des mages peut contrôler ses propres mages de guerre et mages voyous et renverser le cours des batailles, quelles sont les limites de ses pouvoirs ? Même si le Conseil des mages surveille tout le monde, qui surveille le Conseil ? Et qu'est-ce qui empêche un groupe de mages plus puissants de venir au Cormyr et de détruire le Conseil ?

Ces scénarios font craindre que les mages ne deviennent les prochains dirigeants du Cormyr. Certains craignent que les mages soient mécontents de leur rôle de conseil et de soutien et qu'ils décident de prendre une part plus directe à la direction du pays.

De plus, s'il y a quelque chose qui attire des adversaires puissants, c'est bien un mage. Malheur à la communauté qui héberge un mage attaqué par une puissance ancestrale.

Une dernière crainte est la tendance des mages à préserver apparemment leur corps. N'avez-vous jamais remarqué que certains d'entre eux ne semblent pas vieillir du tout ? Certains craignent que l'utilisation de la magie ne perturbe l'équilibre naturel du corps et de l'esprit d'une personne.

## The Sword Herald

L'un des sujets les plus fascinants et les plus méconnus de toute étude du folklore du Cormyr est celui des hérauts de l'épée. Volo a fait de telles spéculations à propos de ces gens plutôt mystérieux qu'Elmin- ster a dit d'un ton sombre : "Nous allons arranger cela, ou ce livre sera renommé immédiatement : Volo Guide to the Effects of an Imprisonment Spell on the Victim, Written from Personal Experi- ence. Voici donc, en termes de jeu, ce qu'Elminster révélerait sur ce sujet. Il ne donne qu'un seul conseil : N'oubliez pas que vous n'êtes pas les premiers aventuriers enthousiastes à apprendre tout cela, et où sont passés tous ces prédécesseurs ?

Les hérauts de l'épée étaient des mages du Cormyr il y a bien longtemps. Ils étaient spécialisés dans la création de refuges extradimensionnels que seuls les nobles les plus riches, les marchands prospères, les prêtres et les sorciers les plus puissants pouvaient s'offrir. Ces refuges étaient d'une grande importance lorsque le Cormyr était une terre sauvage parcourue par des monstres et des rivaux et frappée par des intempéries auxquelles on n'avait pas le temps de construire des abris suffisants pour résister (à cause des guerres, des mauvaises récoltes ou autres). Finalement, ces refuges ont cessé d'être des cachettes pour les gens fuyant les intempéries ou les lames des ennemis. Ils étaient alors couramment utilisés pour stocker des objets de valeur et des trésors périssables, parce qu'à l'intérieur, il n'y a pas d'extrêmes de chaleur et de froid, ni de précipitations, ce qui réduit au minimum les risques d'altération de l'environnement.

Les refuges abandonnés ou oubliés qui ont été redécouverts abritent parfois des robes de chambre anciennes très élaborées qui sont aujourd'hui très recherchées à la cour.

Les hérauts de l'épée ont acquis le nom sous lequel l'histoire les connaît aujourd'hui parce que l'accès à l'un de leurs refuges ne pouvait se faire que si quelqu'un se rendait à un endroit secret particulier avec deux objets : un objet assez commun mais gardé secret par la famille, et une arme tranchante en métal que l'un des hérauts de l'épée avait touchée lors de l'enchantement. Les objets courants allaient d'une tasse d'eau ou d'une soupe de champignons à un os humain, un bois de cerf ou une feuille d'un arbre particulier. Les armes blanches étaient généralement l'une des 3 à 12 épées et/ou dagues que possédait la famille pour laquelle le refuge avait été construit. L'objet commun était toujours consommé lors du passage magique dans le refuge et, dans quelques cas, les armes ne pouvaient pas non plus passer dans le refuge et tombaient sur le sol à l'endroit où l'être activant entrait dans le refuge. Pour sortir de ces refuges, il suffit généralement d'entrer dans une zone spécifique, généralement au bout d'un couloir aveugle, et il n'est pas nécessaire de suivre un rituel ou d'utiliser des objets déclencheurs.

Les personnes entrant dans un refuge peuvent emmener avec elles un être vivant qui les touche, ainsi que tout ce qu'elles ou ce second être portent ou transportent. Généralement, les maisons nobles et les riches mer- chants emportaient des pierres précieuses, des pièces de monnaie et des documents légaux dans leurs refuges. Ce n'est que dans des circonstances désespérées que les propriétaires découvraient que ces refuges étaient des cachettes idéales pour les fugitifs de la justice et les cadavres gênants.

Les hérauts de l'épée sont morts ou ont disparu il y a des siècles, et de nombreux refuges sont aujourd'hui perdus ou leur emplacement précis a été oublié, bien que certains restent des secrets de famille étroitement gardés. (La Maison Cachée utilisée par Lord Tessaril Winter de [[Eveningstar]] est l'un d'entre eux). Selon l'ancienne loi, un roi du Cormyr et ses agents (par exemple, les sorciers de guerre) ne peuvent pas exiger de voir ou d'entrer dans un tel refuge, ni même forcer quelqu'un à confirmer l'existence d'un refuge. Cela ne les a pas empêchés d'employer des aventuriers affrétés et des citoyens privés pour découvrir de telles choses pour eux. C'est ainsi que de nombreux refuges sont équipés de pièges et/ou de gardiens. Les pièges sont généralement des défenses mortelles du passage principal du refuge, et sont souvent constitués de blocs de pierre articulés et de hérissons. Les gardiens vont des squelettes animés aux liches familiales. On dit que les Hérauts de l'épée ont laissé derrière eux une liste de tous leurs refuges, sous la forme d'une série de vers impénétrables (voir un exemple ci-dessous) qu'ils ont cachés dans tout le Cormyr, dans les couloirs du Palais du Dragon Pourpre, à la Cour Royale et dans les maisons privées. Le Héraut d'épée a également fabriqué de grandes clés - de petits objets dont les sages ne s'entendent pas sur la forme, qu'il s'agisse d'orbes, de baguettes ou de gantelets - qui ouvrent l'accès à tous les refuges du Héraut d'épée lorsqu'elles sont utilisées au bon endroit, même en l'absence de la lame ou de l'objet commun adéquat.  

Certains refuges ont été découverts par des aventuriers. La découverte la plus notable est celle du refuge de Dawninghunt en 1346 DR, qui s'est avéré contenir un coffre contenant plus d'un millier de grandes et splendides émer- aldes ainsi que quatre grands et volumineux livres de sorts et plusieurs objets de magie mineure, ainsi qu'une garde-robe de robes raffinées portées 200 ans plus tôt par Lady Rhyndaera Dawn- inghunt. Ces vêtements sont devenus une véritable mode à la cour lorsqu'ils ont été réintroduits par les nobles qui les avaient achetés aux aventuriers chanceux.

Le groupe d'aventurières de Selgaunt, les Yeux du Griffon d'Or (charte signée par [[Azoun IV Obarskyr|Azoun]] en 1341 J.-C.), a fait fortune grâce à la découverte et s'est retiré dans de luxueux domaines boisés près d'[[Espar]]. Ils ont gagné leurs richesses durement recherchées non seulement en vainquant un monstre gardien for- midable d'espèce inconnue, mais aussi en discernant le sens du verset suivant :

> [!Quote]
*La pleine lune sur Wyvernwater te touche,
Fier guerrier conquérant les trois bancs.
Là où l'acier plus petit indique un chemin,
Se tenir là où le guerrier solitaire peut se tenir.*

Ce verset fait référence à une statue de Ring Dhalmass qui se dresse toujours sur les rives de la Wyvernwater, près de [[Hultail]]. La statue représente le roi armé et cuirassé sur un cheval cabré dont les sabots se balancent sur trois bancs de pierre qui forment la base de la statue. Le roi brandit une épée au-dessus de sa tête et se dessine au clair de lune lorsque la pleine lune éclaire la région.

Le monarque sculpté porte également un poignard à la taille. Si l'on regarde vers l'extrémité pointue de l'épée, on aperçoit, à environ un kilomètre de là, un petit monticule rocheux connu sous le nom de Knights Stand, parce qu'un guerrier solitaire a jadis tenu tête à une bande d'[[orcs]]. Le monticule est également inondé par la lumière de la lune lorsqu'elle est pleine. Si l'on s'y tient avec la bonne lame et le bon objet (dans ce cas, une poignée d'herbe) ou l'une des grandes clés du Héraut d'épée, on peut voir un ovale de lumière dressé qui est la porte d'entrée de la Voûte de la Chasse à l'aube.

Une personne qui emprunte cette porte entre dans une petite pièce qui ne contient qu'une chaise, une table, un pot de chambre, une carafe d'eau bouchée, un lit de camp, une lanterne à bougie et beaucoup de poussière.

Les noms des ancêtres de Dawninghunt, ainsi que les dates de leur vie, sont inscrits sur de grandes pierres encastrées dans les murs, comme si ces ancêtres étaient enterrés derrière les pierres. Cependant, si l'on pose la chaise sur la table, une partie du sol de cette chambre disparaît pour laisser place à des escaliers qui mènent au caveau proprement dit : une grande pièce éclairée par un globe dérivant. Sa lumière infaillible est tombée sur une pile de coffres remplis de pièces, de gemmes et de barres d'argent et d'or, qui font maintenant partie de la richesse des Yeux du Griffon d'Or. Cette lueur brille encore sur les tombes de six Dawninghunts, dont le sage Harglast Dawninghunt, dont le cercueil est désormais entouré d'une cage de force (et de sorts de con- tingence qui déclenchent certains sorts d'alarme ailleurs, entre autres choses). Ces précautions ont été prises pour empêcher les aventuriers de l'interroger magiquement sur son domaine d'expertise : les objets magiques du Cormyr primitif !

Un autre verset des Hérauts de l'épée est devenu célèbre parce qu'il apparaît et disparaît de temps en temps (apparemment au hasard) au sommet d'un tombeau dans une crypte publique de [[Suzail]] :

> [!quote]
Glonder parcourt un long chemin
A travers les forêts sauvages et les marais féeriques,
Et à l'endroit de nombreux filets,
Glonder marche, mais d'abord il freine.

Pour comprendre cela, il faut savoir qu'il y a près de 300 ans, le mage Glonder a parcouru la Voie de Calantars en une nuit et un jour sinistres pour rencontrer et vaincre un dragon. Le seul endroit sur cette route où l'on peut trouver de nombreux filets est [[Immersea]], où les pêcheurs de brume utilisent de nombreux filets. De temps en temps, le fantôme de Glonder est aperçu dans [[Immersea]], se tordant les mains ou se précipitant, les mains levées, en train de lancer des sorts. Il faut donc trouver l'endroit où le fantôme apparaît pour la première fois lors de ses rondes nocturnes sporadiques, et y prendre la bonne lame et le bon objet pour trouver le chemin d'un refuge inconnu.

Ces instructions ont été élaborées par le bouffon Ubaldo il y a plus d'un siècle, mais personne ne sait quel est le bon objet commun, ni n'a la bonne lame, ni n'a discerné précisément l'endroit où le fantôme apparaît pour la première fois. Cependant, l'endroit où il apparaît doit être la cave d'une structure d'[[Immersea]], car le fantôme s'élève alors de la Voie de Calantars et se précipite dans une certaine allée. Se tenir debout avec une grande clé en main à l'endroit où Glonder surgit dans la rue s'est avéré inefficace.

On sait qu'il existe au moins huit grandes clés, mais on pense que beaucoup d'autres ont été cachées ou volées. La plupart des discussions sur l'aspect des clés portent sur ces clés manquantes, dont l'une est régulièrement mise en vente ou en location à Sembia. La tradition locale de [[Suzail]] insiste sur le fait que l'un des sceptres de la vaste tenue d'Obarskyr contient une grande clé. La tradition suzailaise veut également qu'une autre grande clé ait été confiée il y a longtemps à un habitant anonyme de la ville lors d'un bal masqué, afin que le royaume ait une chance de survivre si une magie maléfique s'emparait de l'esprit de son roi ou si des forces maléfiques déferlaient sur le pays avec des armées conquérantes. Le sage Tharondar d'[[Arabel]] (aujourd'hui décédé, mais ayant écrit bien après la disparition des Hérauts de l'épée) postule qu'il existe peut-être des clés moins importantes qui ouvrent plusieurs refuges, mais pas toutes. Comme beaucoup d'autres choses concernant le travail des Hérauts de l'épée, il ne s'agit que de pures spéculations.

Nous savons qu'il y eut au moins 17 Hérauts de l'épée, qu'ils n'étaient pas des hérauts officiels (bien qu'ils offraient à la noblesse du royaume le service de faire figurer un insigne d'armes choisi sur les murs de pierre et autres lieux permanents), qu'ils étaient de puissants sorciers qui conçurent de nombreux sorts jusqu'alors inconnus et aujourd'hui oubliés, qu'ils se livraient à des voyages planaires et à des querelles avec les sorciers rouges de Thay, et que le plus puissant d'entre eux était un homme du nom de Yimluth. Yimluth était un archimage d'au moins 26ème niveau et un werestag. Il pouvait prendre la forme d'un cerf ou d'un homme poilu à tête de cerf. En fin de compte, il n'a pas pu quitter l'une de ces formes bestiales, et il se cache toujours quelque part dans la forêt des Anneaux, s'il n'a pas été tué. (Il est également possible qu'il se déplace de refuge en refuge grâce à une puissante magie qui lui permet de sauter d'un lieu extradimensionnel à un autre.

Un groupe de bardes et de sages pense que Yimluth est maintenant au service de Mielikki ou de Silvanus afin d'atteindre le statut de demi-dieu ou qu'il est déjà un demi-dieu. Un autre groupe jure qu'il est dans une sorte de stase, attendant un appel désespéré du trône du Cormyr qui l'amènera à défendre le royaume au moment où il en aura le plus besoin. Comme le commente sèchement Elminster, il est clair que son véritable destin est inconnu.

Un autre Héraut d'épée dont on se souvient est Murald. Il aimait les jardins et les tapisseries. Au moins six peintures et tapisseries sur les murs de diverses chambres intérieures du Palais du Dragon Pourpre sont son œuvre. Elles sont également des portes vers différents lieux des royaumes. L'un de ces lieux est un pavillon de chasse quelque part au cœur de la Forêt des Anneaux, une autre représentation mène au versant est de la Tor de la Tombe des Demoiselles près de [[Eauprofonde|Waterdeep]], et une troisième est connue pour mener à une caverne refuge dans les Cornes de la Tempête quelque part au-dessus d'[[Espar]] qui est gardée approvisionnée en armes, en nourriture et en gardiens de l'horreur casqués.

Les objectifs, les identités et les destins ultimes des Hérauts de l'épée restent entourés de mystère. Tout ce que l'on sait, c'est qu'ils sont arrivés dans le royaume soudainement, mais sans faire d'histoires, qu'ils n'ont pas eu de conflit ouvert avec la Couronne ou les nobles, et qu'ils ont travaillé sur de nombreuses choses qui ont enrichi le royaume. A plusieurs reprises, ils ont jugé un individu ou une politique, essayant de convaincre le roi ou les nobles de voir les choses comme eux.

Ces assemblées impressionnaient tellement les gens de l'époque que, dans le langage courant de Cormyre, on utilise aujourd'hui l'expression "cour des pleines épées" pour désigner toute occasion fantaisiste, formelle ou très importante et solennelle.

Bien que les hérauts de l'épée semblent avoir disparu, certains croient que quelques-uns d'entre eux survivent encore. Une superstition populaire veut qu'ils continuent de guider ou d'influencer le royaume, sans être vus, aujourd'hui. Les mères et les vieilles femmes réprimandent parfois les enfants qui se conduisent mal en leur disant : N'oubliez pas que les Hérauts veillent ! De nombreux membres du personnel du Palais du Dragon Pourpre pensent que certains des fantômes qui hantent les cours et les garages de [[Suzail]] sont des Hérauts de l'épée ou leurs serviteurs, mais la vérité sur les Hérauts a jusqu'à présent échappé à [[Vangerdahast Aeiulvana]], et si Elminster le sait, il ne l'a pas dit.

# Magie au Cormyr

La magie au Cormyr est une chose vigoureuse et continue. Elle est aussi motivée aujourd'hui par l'orgueil, la com- pétition, les besoins de la guerre et l'ambition qu'elle l'était par la survie face aux dragons et autres ennemis monstrueux lorsque le pays était plus jeune. C'est un domaine qui dépasse largement le cadre d'un seul ouvrage et certainement le traitement plutôt (comme le dit Elminster avec aigreur) "gosh- wow" que la magie reçoit dans tous les ouvrages de Volo. Le Vieux Mage de Shadow- dale a cependant exigé que les pires distorsions et erreurs de Volo soient remplacées par cet appendice, juste pour que yell ait la moindre idée de ce qu'il raconte. Alors (soupir), c'est parti.

## Les portes du Cormyr

Les portails de téléportation permanents, ou portes, sont présents depuis longtemps dans le Cormyr. Les hérauts de l'épée (dont il est question dans l'annexe II) ont créé de nombreux portails spécialisés, et les familles royales et nobles ont, au fil des ans, utilisé de nombreuses méthodes pour acquérir leur propre trans- port magique privé. Un serviteur de Mielikki ou, si l'on en croit les fidèles, la déesse elle-même, a créé la Porte des Feuilles Bleues. Ce moyen de transport peu connu relie un arbre à feuilles bleues dans les jardins royaux de [[Suzail]] à un autre arbre à feuilles bleues qui se trouve à côté des eaux d'une source claire dans la forêt des Anneaux, juste au sud de [[Eveningstar]].

Un être qui touche l'un ou l'autre arbre et prononce un mot secret d'activation est transporté (téléportation sans erreur) vers l'autre arbre, avec tous les biens portés ou transportés et, s'il le souhaite, un autre être. Cette personne supplémentaire doit être touchée directement, mais n'a pas besoin d'être consciente ou même vivante.

Cette route a longtemps été utilisée par les sorciers de guerre, les messagers des rois et d'autres agents de la couronne pour voyager rapidement et sans trace à travers les terres de Cormyrs. [[Azoun IV Obarskyr|Azoun]] l'a utilisé toute sa vie pour rendre visite à Tessaril Winter à [[Eveningstar]]. Pendant le règne d'[[Azoun IV Obarskyr|Azoun]], [[Vangerdahast Aeiulvana]] a toujours envoyé des sorciers de guerre armés de divers sorts de traçage pour surveiller les deux arbres et voir qui allait et venait. Ces sentinelles ne défient jamais les utilisateurs et restent généralement invisibles.

Un itinéraire similaire, reliant neuf pierres dressées, enjambe le mur ouest du royaume, sautant d'une haute vallée à une hauteur rocheuse et à une caverne à flanc de falaise, le long des Cornes de la Tempête qui marchent sur le flanc ouest du Cormyr. On pense que ce réseau a été créé par une école ou une communauté de sorciers, aujourd'hui disparue, qui vivait isolée dans les montagnes et qui souhaitait disposer d'un moyen rapide d'entrer et de sortir de chez elle, sans avoir à escalader les montagnes.

Si l'on en croit la tradition locale et les rapports des sorciers de guerre, d'autres réseaux de portes inconnus existent dans la forêt de Hullack et dans les Stonelands. Le royaume forestier de Cormyrand en particulier, ses franges les plus sauvages et l'arrière-pays qui l'entoure ont longtemps été des territoires de prédilection pour les mages désireux de s'installer dans un isolement paisible et de travailler leurs arts magiques.

## Les sorciers du Cormyr

Au fil des siècles, la beauté pastorale du Cormyr a été adoptée par des centaines de puissants mages. Leurs cottages et leurs petites tours de mage, ou leurs ruines, se dressent au milieu des arbres sur de nombreux chemins de traverse ou sentiers boisés du royaume. [[Vangerdahast Aeiulvana]] désapprouve sévèrement les mages qui kidnappent ou expérimentent sur les bêtes et les êtres locaux, mais les autres mages sont laissés tranquilles tant qu'ils ne travaillent pas contre la Couronne. (Dans le passé, de nombreux nobles ont engagé des mages sans le sou pour les aider à renverser les Obarskyrs).

Certains des mages indépendants les plus remarquables résidant actuellement au Cormyr sont énumérés ci-après. Les détails de ces per- sonnages se trouvent dans l'annexe I. Elminster précise que cette liste est très incomplète. Elle a été compilée par Volo, et elle se concentre sur les mages qui ne se donnent pas la peine de parler ou qui peuvent se soustraire à la connaissance générale.

### [[Arabel]]

[[JESTRA]] (NG hf Tra18)  
[[MELLOMIR of Arabel]] (LN hm M27; Sage fields: history, prophecies, and divination)  
[[MYSCHANTA HALARRA]] (CG hf Abj14) 
[[THEAVOS THONTAR]] (LN hm M17)


### Vicinity of [[Espar]]

[[RULDAN NYSGART]] (NG hm M16)

### Vicinity of [[Eveningstar]]

[[TSHARLURA of Blackthorne|Tsharliira]] of Blackthorne (LG hf M14)

### Vicinity of [[Juniril]]

[[IYRYTHARNA DANTRAS|Iyrytharna]] Dantras (CG hf M16)

### [[Marsember]]

[[DELTHRIN THE DEADMASTER]] (NE hm Nec12) 
[[FILFAERIL STORMBILLOW]] (CG hf M16) 
[[TONGRETH of Marsember]] (LN hm M21) 
[[VINDALA CHALANTHER]] (NG hf Ill15)

### Vicinity of [[Marsember]]

[[UNGATHROS of Mistrim]] (NG hm M15)

### Vicinity of [[Skull Crag]]

[[ORBRIL of Skull Crag]] (CN hm M15)

### [[Suzail]]

[[ARGUL MARAMMAS|Argûl Marammas]] (LN hm M13)  
[[BASKOR TRANTH]] (NG hm M9)  
[[LASPEERA NAERINTH]] (NG hf M14)  
[[MAXER HLARR]], Defender of [[Suzail]] (NG hm Inv11)  
[[VALANTHA SHIMMERSTAR]] (CG hf M13)

### [[Tilverton]]

[[FILANI of Tantras]] (N hf M9; Sage fields: poli- tics & history of the Dragonreach, poli- tics & history of the Moonsea North)
[[GAHLAERD MOSSMERE]] (NG hm M12)

### Vicinity of [[Waymoot]]

[[ENDARTHAR of Wildwoods]] (CN hm M18)

## Les pupilles du Cormyr

Certains nobles, puissants mages et riches marchands du Cormyr possèdent sans aucun doute des protections. Les gardes sont des défenses magiques qui n'agissent que sur les êtres qui ne possèdent pas de jeton permettant le libre passage ou qui tentent de les franchir d'une manière non prouvée. Les gardes mises en place par les riches et puissants citoyens du Cormyr ont des effets très variés, et ces gardes ne sont pas abordées ici. La Couronne du Cormyr utilise cependant trois types de protections standard dans tout le royaume : la protection par l'anneau, la protection par le manteau et la protection totale. Les sorts sur lesquels reposent ces protections s'apparentent à la liste de sorts des sorciers de 7e niveau, décrite dans les précédents guides de cette série. Cependant, ces sorts sont des secrets d'État du Cormyr et n'apparaissent donc pas ici.

La rumeur court depuis longtemps que la famille Obarskyr possède un refuge privé où sont entreposés ses plus grands trésors et qui est gardé par ce que l'on appelle une garde de dragon. La garde du dragon est censée libérer une magie semblable à l'haleine d'un dragon, et comme l'haleine d'un dragon, elle peut s'étendre sur une grande distance le long des passages, ne permettant à personne d'échapper à ses effets. Mais à l'heure où nous écrivons ces lignes, ces rumeurs n'ont pas été confirmées.

### Anneau de protection

Le type de garde le plus faible est connu sous le nom de garde d'anneau, car un [[Anneau du dragon pourpre]] permet de le traverser, tout comme tous les jetons de passage listés ci-après pour les gardes plus puissantes. Si des êtres non autorisés tentent de franchir ce type de garde, ils reçoivent une légère décharge d'énergie. Ce choc est conçu pour détourner les oiseaux, les serpents, les chat- tles et toute autre forme de vie inintelligente, et il inflige 1 point de dégâts à tout personnage qui ne réussit pas son jet de sauvegarde contre le sort. Tout contact non autorisé avec la pupille déclenche une alarme sous la forme d'une lumière ou d'un son, selon ce qui a été déterminé lors de la création de la pupille. Le sort bloque également le passage de tous les sorts de 3e niveau ou moins, dont il absorbe l'énergie. Ainsi, un sorcier employant un sort de vol qui pénètre une garde telle que celles qui entourent les tours du Palais du Dragon Pourpre à [[Suzail]] perd sa capacité de vol et tombe.

### Garde de cape

Le type de garde intermédiaire est appelé garde de cape car une [[Cape de sorcier de guerre]] permet de la traverser, tout comme un anneau de commandeur et une [[Pierre de passage]] (mais pas un [[Anneau du dragon pourpre]]). Un contact non autorisé avec une garde de cape a les mêmes effets qu'un contact avec une garde d'anneau. De plus, toute créature intruse doit faire deux jets de sauvegarde supplémentaires, un contre les sorts et un contre la paralysie.

Si les jets de sauvegarde contre les sorts échouent, les intrus sont refroidis pour 6d6 points de dégâts (similaires aux dégâts d'une baguette de givre, en traitant tous les 1 obtenus comme des 2). Si ces jets de sauvegarde réussissent, la moitié des dégâts seulement est infligée. Si les jets de sauvegarde contre la paralysie échouent, les créatures sont également étourdies pendant 1d2 rounds et sont incapables de réfléchir ou d'agir volontairement. Notez que les créatures étourdies restent normalement dans la salle, subissant à nouveau les 6d6 points de dégâts de froid aux rounds où elles sont étourdies. Si les jets de sauvegarde contre la paralysie sont réussis, les intrus ne subissent aucun effet d'étourdissement.

Les intrus morts-vivants doivent également effectuer ces deux jets de sauvegarde. S'ils échouent tous les deux, ils sont désorganisés (détruits complètement). Si un seul échoue, les morts-vivants intrus subissent 5d4 points de dégâts. Si les deux réussissent, ces morts-vivants traversent la salle sans subir d'effets néfastes.

### Garde complète

Le type de protection le plus puissant est la protection intégrale. Les pouvoirs spécifiques de ces protections varient, mais toutes les protections complètes peuvent être traversées à l'aide d'un anneau de commandeur ou d'une [[Pierre de passage]], mais pas d'un [[Anneau du dragon pourpre]] ou d'une [[Cape de sorcier de guerre]].

Les effets de la violation d'une garde complète combinent les effets nocifs et d'avertissement des deux types de garde inférieurs, et la garde complète invisi- ble possède un bord extérieur souple d'environ 3 pieds de profondeur qui se durcit en une barrière semblable à un mur de force. Cette partie intérieure de la garde agit également comme un anneau de détournement de sort sur toute magie entrant en contact avec elle.

Dans certaines gardes complètes, comme celle qui encercle les chambres royales du palais de [[Suzail]], la partie intérieure solide ne se manifeste que lorsqu'on y entre, et elle n'existe pas pour quelqu'un qui sort de la zone gardée. Dans d'autres, comme celles autour de toutes les armureries du Dragon Pourpre, elle est absolue dans les deux sens.

## Objets magiques de la Couronne

Voici les détails de certains des objets magiques fabriqués et utilisés par les forces dirigeantes du Cormyr. Il est probable qu'il y ait de nombreux spécimens quasi identiques de ces objets en usage dans le royaume à tout moment. La possession d'un de ces objets par quelqu'un qui n'est pas un agent de la Couronne est un délit qui entraîne une arrestation immédiate et un interrogatoire très approfondi par des sorciers de guerre utilisant la magie de lecture des pensées ainsi que des questions approfondies. Les aventuriers sont informés que les seuls bluffs valables lorsqu'ils sont pris en possession de l'un de ces objets sont les suivants : Je suis un messager du roi, je suis un agent des sorciers de guerre, ou le roi (ou Vanger- dahast) me l'a donné pour une mission spéciale dont je n'ai pas le droit de vous parler, mais dans laquelle je suis engagé en ce moment même ! Les personnes qui utilisent ces défenses doivent être prêtes à fuir le Cormyr instantanément si elles les essaient sur quelqu'un qui a un rang supérieur à celui de première épée "*sergent*" dans les Dragons Pourpres, un apprenti sorcier de guerre novice ou un courtisan non royal !

Comme les autres entrées de cette annexe, la sélection présentée ici ne doit pas être considérée comme définitive. Elle ne comprend que les objets sur lesquels Volo a pu obtenir des détails, même s'il est vrai qu'il en a appris bien plus que le commun des citoyens du Cormyr ne pourra jamais en discerner. Les bracelets et la cape sont utilisés par les sorciers de guerre et parfois par les chefs des grandes familles nobles. L'anneau du dragon pourpre, le bâton et la lame sont utilisés par les dragons pourpres et généralement par les officiers, pas par les simples soldats. L'anneau de commandement et la pierre de passage, beaucoup plus rares, ne sont portés que par des courtisans importants, des officiers militaires de haut rang, des seigneurs locaux et des membres de la famille royale. Elmin- ster note que de nombreux objets volés de la magie de la Couronne ont été retrouvés dans des coffres peu profondément enterrés, enfouis dans des arbres creux ou cachés dans des greniers, des cryptes, des entrepôts et des caves d'auberge, et que d'autres sont découverts chaque jour dans le Cormyr.

[[Battlestar Bracers]]
[[BauLgroth's Blade]]
[[Commander's Ring]]
[[Purple Dragon Ring]]
[[Peacemaker's Rod]]
[[War Wizard Cloak]]
[[Passagestone]]


# Aventures et Aventuriers

Tous ceux qui souhaitent mener des aventures dans le Cormyr doivent savoir qu'aucun aventurier ne peut agir en tant que groupe sans avoir obtenu au préalable une charte royale.

L'application stricte de cette loi a commencé après que Gondegal a levé une force mercenaire à l'intérieur du Cormyr et a tenté de faire sécession du royaume. L'obligation d'obtenir une charte a pour but d'empêcher que ce genre d'activité ne se reproduise. Tout groupe de cinq personnes ou plus doit obtenir une charte.

## Chartes

Sans charte, les aventuriers peuvent être appréhendés par n'importe quelle force représentant le roi, y compris les Dragons Pourpres, les Sorciers de Guerre, et les

milice locale. Compte tenu de la nature pacifique du Cormyr et de la puissance de ces forces, il est souhaitable qu'un groupe d'aventuriers enregistre son nom et obtienne une charte. Cela peut se faire par l'intermédiaire du Lord Commander à [[High Horn]], du Warden of the Eastern Marches à [[Arabel]] (Baron Thomdor), ou du Chancel- lor ou Lord High Marshal à la Cour Royale à [[Suzail]], ainsi qu'auprès du roi.

Une bande d'aventuriers doit divulguer les noms de ses membres et son nombre dans la charte. Cela rend l'ajout de membres au groupe particulièrement difficile, c'est pourquoi ceux qui demandent une charte doivent être sûrs de l'intégrité de leur groupe avant de la demander. Si quelqu'un est ajouté, le groupe doit s'assurer que le nom du nouveau membre est enregistré dans [[Suzail]]. Les enregistrements des chartes sont mis à jour tous les mois. Quoi qu'il en soit, un groupe ne peut pas compter plus de 30 membres. Une fois qu'un groupe a reçu sa charte, les membres doivent porter l'insigne ou les armoiries du groupe en tout temps.

Les chartes coûtent 1 000 lions d'or, avec une taxe annuelle de 300 lions d'or due à la date anniversaire de la signature de la charte. Une taxe de retard de 20 lions d'or par jour est appliquée pendant 10 jours au maximum. Si la taxe n'est pas payée et que les frais de retard ne sont pas réglés dans les 10 jours suivant la date d'échéance, la charte est révoquée.

La révocation de la charte ne signifie pas seulement que le groupe n'a plus le droit de partir à l'aventure dans le Cormyr, mais aussi qu'il a décidé de s'opposer à la couronne en refusant délibérément de renouveler sa charte. Le groupe est considéré comme hors-la-loi et un mandat d'arrêt est émis contre ses membres. Une fois arrêté, le groupe peut encore payer la taxe et les frais de retard. Si les membres paient, leur charte est rétablie et le groupe peut reprendre ses activités. Dans le cas contraire, la charte est révoquée de façon permanente et le groupe ne peut pas se réunir en portant des armes.

Le Cormyr a tout intérêt à surveiller de près ceux qui parcourent la campagne en portant des armes et qui semblent n'avoir d'autre but que de partir à l'aventure, ce qui est un facteur d'agitation et de comportement chaotique s'il en est. Les Dragons Pourpres n'apprécient généralement pas les aventuriers en raison des perturbations qu'ils causent aux paisibles Cormyréens.

Toute personne ayant le pouvoir de délivrer une charte peut la révoquer à tout moment et pour n'importe quelle raison. Si un membre d'un groupe donné commet un crime, il est automatiquement rayé de la liste des noms inscrits sur la charte.

La charte ne donne aux aventuriers que le droit de porter des armes, mais pas celui de se comporter de manière incivile.

## Attitudes

Les habitants du Cormyr ont peu de respect pour le métier d'aventurier. En effet, le concept de prendre des armes et de parcourir de grandes distances dans le seul but de mettre sa vie en danger pour le simple espoir de gagner de l'argent est tout à fait étranger à la population.

Les aventuriers qui ne sont pas cormyréens sont considérés avec méfiance mais aussi avec curiosité. Les Cormyréens sont intrigués par le fait que quelqu'un vienne d'un pays lointain pour se rendre au Cormyr. Cela signifie que le Cormyr doit offrir quelque chose que la patrie de l'aventurier n'offre pas, et c'est une source de fierté.

## Aventures possibles

Le mélange de zones civilisées et de frontières sauvages du Cormyr offre de nombreuses possibilités d'aventures.

### Exploration

La Forêt de Hullack et les Terres Solides sont les deux principales régions du Cormyr qui sont explorées. Notez que les Stonelands sont une zone particulièrement violente, où les aventuriers sont susceptibles de tomber dans des embuscades. La forêt de Hullack est également connue pour être fortement infestée de monstres de toutes sortes.

Le [[Château Kilgrave]] est une excellente occasion d'explorer un ancien donjon. Le complexe situé sous les ruines est vaste et complexe, et plaira à tous ceux qui aiment résoudre les mystères des habitants d'un château mort depuis longtemps.

La chaîne de montagnes du Stormhorn est très prisée des aventuriers. Elle compte des centaines de montagnes, chacune ayant une histoire à raconter et des secrets à cacher.

Les pics du tonnerre offrent également un potentiel d'aventure, car cette chaîne a été moins explorée que celle du Stormhorn.

Les vastes marais attirent également les explorateurs désireux d'endurer les épreuves d'un voyage à travers des terres humides aussi difficiles.

### Protection

En plus de l'exploration, une autre source d'aventure est la lutte contre les pirates sur le Lac des Dragons. Cette activité peut être lucrative, et un groupe qui réussit gagnera l'amitié des fonctionnaires et des marchands cormyréens.

### Richesse

Les maisons de voyous de [[Tilverton]] sont des sources possibles d'or caché, mais les guildes de voleurs les protègent bien. Les canaux de [[Marsember]] peuvent contenir des trésors engloutis, mais l'eau peut provoquer des maladies.
