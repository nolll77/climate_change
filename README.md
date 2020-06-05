# climate_change

1 - INTRODUCTION
1.1 - Définition simple :
Le réchauffement climatique, aussi appelé réchauffement planétaire ou réchauffement global (en anglais Global warming) est un phénomène de transformation du climat qui se caractérise par une augmentation générale des températures moyennes en raison des activités humaines, modifiant durablement les équilibres météorologiques et les écosystèmes.
Plus précisément, lorsqu’on évoque le réchauffement climatique, cela s’agit d’étudier le phénomène d’augmentation des températures qui se produit sur Terre depuis plus de 170 ans, c’est à dire depuis le début de la Révolution Industrielle (1850). En effet, les températures moyennes ont augmenté plus ou moins régulièrement. En 2018, la valeur relevée se situait entre 1,0 et 1,5 degrés au dessus des valeurs moyennes de l’ère pré-industrielle.
1.2 - Définition scientifique :
Une des métriques principales permettant de mesurer le réchauffement climatique est l’effet de serre, on parle donc du réchauffement climatique “d’origine anthropique” (d’origine humaine). Il s’agit d’une forme de réchauffement climatique dont les causes ne sont pas naturelles mais économiques et industrielles.
Nombre de scientifiques étudient ce phénomène et tentent de comprendre comment les activités humaines provoquent ce réchauffement. Ces scientifiques sont regroupés au sein d’institutions telles que le GIEC (Groupe d'experts intergouvernemental sur l'évolution du climat ; IPCC en anglais : Intergovernmental Panel on Climate Change), la NASA, l’Organisation Météorologique Mondiale, et le CNRS entres autres.

2 - Présentation du sujet avec quatre études de cas pour décrire les conséquences du réchauffement climatique sur l’écosystème et la planète :
Cette analyse s’articulera autour de quatres études qui seront proposés sous la forme de problématiques à connotation climatosceptique auxquelles il s’agira d’apporter une réponse basée sur l’étude de la Data :
Il n’y a pas de changement car le réchauffement climatique est un mythe.
L’homme n’a aucun impact sur le réchauffement climatique.
Il s’agit d’un phénomène exagéré par les médias et n’aura qu’un impact mineur sur la vie sur Terre ; donc ce n’est pas grave.
Le réchauffement sera bientôt arrêté grâce à la technologie.

3 - Développement des quatre études de cas : 

3.1 - Étude de cas  n°1 : Le réchauffement climatique est-il un mythe ?
Dans ce première partie, l’étude portera sur les valeurs de la température terrestre et leurs variations sur deux échelles de temps. 
La première échelle est le consensus de recherches scientifiques se rapportant aux 400.000 dernières années. Durant ces 400.000 années, de nombreuses périodes de changements climatiques sont survenues, souvent influencées par la combinaison de phénomènes, comme les changements dans l’orbite terrestre, la dérive des continents, la variation de l’activité volcanique mais aussi d’autres phénomènes externes comme les changements dans l'intensité du soleil ou les impacts météoritiques. Ces variations astronomiques ont produit 4 principaux cycles de même équivalence, d’un peu plus de 100.000 ans chacun et pendant lesquels la température moyenne de la Terre était inférieure de 5° C par rapport à l’ère contemporaine.

Fig. 1 : Évolution sur les 400.000 dernières années de la température moyenne en Antarctique. Le 0 de l’axe vertical de gauche correspond à la valeur actuelle. Cette variation de température est légèrement plus élevée que celle de la planète dans son ensemble. Le fait que les oscillations soient plus importantes à droite (donc récemment) tient à la meilleure précision des mesures quand on se rapproche de l’époque contemporaine (Source : https://cdiac.ess-dive.lbl.gov/).
La seconde échelle est un macro-zoom décrivant une période qui couvre les années 1890 jusqu’à l’année 2018. L’analyse dans ce laps de temps est permise grâce à des registres de températures détaillés qui existent depuis l’ère industrielle. En effet, c’est  à partir de cette époque que des mesures méthodiques furent consciencieusement rapportées à l’aide de thermomètres car le besoin d'étudier et de prévoir le temps se systématise avec le développement des transports maritimes et ferroviaires.
Cependant, le paramètre pris en compte n’est pas la température elle-même mais une "anomalie", c’est-à-dire un écart de température par rapport à une moyenne. Pourquoi ce choix ? Voici l’explication que donne la NOAA sur son choix d’utiliser des anomalies de températures plutôt que des relevés absolus : "Les températures absolues sont difficiles à utiliser pour plusieurs raisons. Certaines régions n’ont que peu de stations de mesure et des interpolations doivent être faites sur de vastes étendues. Dans les régions montagneuses, la plupart des observations proviennent de vallées inhabitées, ainsi l’altitude doit être prise en compte dans la moyenne des températures d’une région. Par exemple, un mois d’été peut être plus froid que d’habitude dans une région, à la fois au sommet d’une montagne et dans la vallée à proximité, mais les températures absolues seront très différentes d’un endroit à l’autre. L’utilisation des anomalies montrera dans ce cas que les températures sont en-dessous de la moyenne pour les deux endroits. Ainsi les grandes étendues sont traitées par anomalies et non par températures absolues. Les anomalies décrivent avec plus de précision la variabilité du climat sur une large zone que ne le feraient les températures absolues et permettent de comparer plus facilement les zones entre elles."
             
Fig. 2 : Jeu de données importé dans Python puis converti en Dataframe, indiquant les dix premières et les dix dernières années de la période du macro-zoom étudié.
Le jeu de données (en anglais Dataset) utilisé pour cette étude de cas provient de la Japan Meteorological Agency (http://www.jma.go.jp/jma/index.html). Dans le domaine des études de statistiques et de probabilités ainsi que de l’apprentissage automatique (Machine Learning), un jeu de données peut être représenté graphiquement par un nuage de points. 








Fig. 3 : Visualisation de  la température au cours du temps sous la forme d’un nuage de points avec la bibliothèque Matplotlib importée dans Python.

Suite à cette étape, on créer une modélisation qui prendra la forme d’une régression linéaire. Ce concept mathématique consiste à rechercher la droite permettant d’expliquer le comportement de la température en fonction du temps. 
Fig. 4 : Visualisation de  la température avec une droite de régression linéaire.
On remarque que les changements climatiques d'origine anthropique s’ajoutent aux changements d’origine naturelle mais se déroulent à une échelle de temps beaucoup plus rapide que ce que la Terre a connu jusqu’à maintenant. La vitesse et l’intensité des changements climatiques d’origine anthropique pourraient excéder la capacité d’adaptation de plusieurs systèmes naturels et humains.








Fig. 5 : Visualisation sous forme de Heatmap permettant de mettre en évidence la corrélation du Dataframe.
3.2 - Étude de cas  n°2 : L’activité humaine n’a pas d’impact sur le réchauffement climatique. 
Proposition d’éléments de réponses par l’analyse de 2 Datasets :
Dans cette seconde partie, l’étude portera sur les gaz à effet de serre. L’effet de serre est un phénomène naturel qui se manifeste sur les planètes munies d’une atmosphère comme la Terre. Lorsque la lumière du soleil parvient à la Terre, une partie est absorbée par l’atmosphère, une autre est réfléchie dans l’espace et le reste (environ 30% de l’énergie initiale) atteint le sol, ce qui permet de réchauffer la planète. Mais ces rayonnements sont ensuite renvoyés dans l’espace sous forme d’infrarouges, et l’atmosphère en piège une partie (environ 95 %) qui repartent sur la surface terrestre (5). C’est cet effet de capture de l’énergie solaire que l’on nomme l’effet de serre. Cet effet est bénéfique pour la vie sur la terre car sans lui, la température à la surface terrestre serait en moyenne de -18°C. Les gaz responsables de l’effet de serre sont surtout la vapeur d’eau, le CO2, l’ozone, le méthane et l’oxyde nitreux.
Le  1er Dataset étudié a été récupéré depuis le site https://www.data.gouv.fr/fr/datasets/ 











Fig. 6 : Émissions cumulées totale des principaux gaz à effet de serre d’origine humaine.

Le gaz contribuant le plus à l'accroissement de l'effet de serre responsable de ce réchauffement est le CO2. Le graphe ci dessus montre en effet que le CO2 représente aujourd'hui près de  63% des émissions de gaz à effet de serre d'origine humaine, bien loin devant le méthane et l'oxyde nitreux dont les émissions se sont également accrues pendant le 20e siècle. Ce réchauffement climatique associé à l'accroissement de l'effet de serre a plusieurs conséquences sur l’environnement.
Explications sur le forçage radiatif positif et le forçage radiatif négatif :
La Terre reçoit de l'énergie sous forme de chaleur, via les rayons du soleil. Certains facteurs, typiquement les gaz à effet de serre, ont tendance à absorber les infrarouges. Ainsi, plus ils sont présents dans l'atmosphère, plus on assiste à un réchauffement du climat. Le forçage radiatif des gaz à effet de serre est donc positif.
En revanche, les aérosols ont tendance à renvoyer les rayons solaires vers leur émetteur, ce qui provoque un refroidissement de la Terre. Dans ce cas, le forçage radiatif est négatif.
Si le bilan des forçages radiatifs est positif, la Terre a tendance à se réchauffer. C'est ce qu'il se passe en ce moment. Dans le cas contraire, elle refroidit.
 
Dans les figures ci dessous on importe un 2nd Dataset depuis le site https://data.world, il sera nettoyé afin d’afficher sous forme de courbes ce raisonnement.

Fig. 7 : Importation du Dataset et création de Dataframe sous Python.

Quatre paramètres sont importants pour définir l’effet d’un GES et son « efficacité ». Le premier paramètre est que pour être un GES, l’espèce considérée doit absorber le rayonnement IR émis par la surface terrestre, c’est-à-dire que la molécule doit avoir des modes de vibration qui absorbe ces longueurs d’ondes (voir l’article sur l’effet de serre). Par exemple, l’ozone tropopshérique (O3) est un GES mais l’oxygène (O2) n’en est pas un. Le second paramètre, une grandeur moléculaire intrinsèque à une espèce, est l’efficacité d’absorption de cette espèce (elle est notée a0)* : une molécule qui absorbe fortement et sur une gamme de longueur d’onde large aura un impact important sur le forçage radiatif. Le troisième critère est la concentration et la vitesse à laquelle la concentration d’un GES augmente : plus un gaz est présent en grand quantité, plus forte sera son absorption. Le dernier paramètre est la stabilité du GES : une molécule très stable (c’est-à-dire dont la demi-vie est longue), et qui donc persiste longtemps dans l’atmosphère, aura une contribution durable sur le réchauffement.











Fig. 8 : Sélection des paramètres à afficher, CO2, CH4, N20, CFC12, CFC11.

Le graphique obtenu montre la forte augmentation de CO2 et de méthane dans l’atmosphère. On voit également l’apparition de nouveaux gaz qui n’existaient pas dans l’atmosphère avant la période pré-industrielle et qui sont rejetés dans l’atmosphère par les activités humaines : chlorofluorocarbones (CFC), hydrochlorofluorocarbones (HCFC), hydrofluorocarbones (HFC), perfluorocarbones (PFC), l’ozone troposhérique.










Fig. 9 : Tracé de graphes des forçages radiatifs à effet de serre.
Enfin, pour conclure cette étude de cas, nous nous proposons de créer à partir du second Dataset un Dataframe principal composé de deux Dataframes concaténés. Le premier contenant les valeurs de temps (Year) et de taux de CO2, le second Dataframe contenant les anomalies de températures globales.




Fig. 10 : Création du premier Dataframe…





Fig. 11 : … création du second Dataframe qui sera concaténé avec le premier.

Pour obtenir la même période (de 1979 à 2015) sur les 2 Dataframes il faut Slicer le second.












Fig. 12 : Slicing sur le Dataframe.
Enfin nous obtenons le tracé du coefficient de corrélation entre la température et le taux de C02.










Fig.13 : Corrélation entre l’anomalie de température et le CO2.
On remarque ainsi que la quantité de CO2 dans l’air a très fortement augmenté au cours du dernier siècle, exactement comme la température. On peut donc suspecter le CO2 et les autres gaz à effet de serre d’être à l’origine du réchauffement climatique actuel.
3.3 - Étude de cas  n°3 : S’agissant d’un phénomène exagéré par les médias, ce n’est pas grave.
Depuis le début des années 1980, la quantité de glace sur terre diminue chaque année. Celle-ci se trouve à différents endroits sur la planète et sa fonte n’a pas les mêmes impacts sur le climat en tous lieux. Dans les hautes montagnes, la surface recouverte par la glace tend à diminuer et le manteau neigeux est présent sur un temps de plus en plus court chaque année. Toutefois, et c’est une remarque s’appliquant à de nombreux phénomènes environnementaux, ces évolutions ne s’observent pas de la même façon en tout point de la planète. Dans cette troisième partie, l’étude de cas portera sur la fonte des glaces et plus précisément sur la fonte de la banquise en Arctique et en Antarctique. Le Dataset avec lequel nous allons mener cette analyse se trouve à cette adresse : 
https://nsidc.org/data/search/#keywords=sea+ice/sortKeys=score,,desc/facetFilters=%257B%257D/pageNumber=1/itemsPerPage=25















Fig. 14 : Chargement de deux Datasets couvrant les périodes 1981 - 2018 : le premier Dataset concernant le pôle nord et le second dataset concernant le pôle sud.

Fig. 15 : Exemple de Dataviz pour afficher les valeurs de la fonte des glace en Arctique.
Au pôle Nord, l’océan Arctique est un vaste bassin d’eau froide recouvert de banquise et délimité par les côtes scandinaves, russes et canadiennes.
De l’autre côté du globe, le continent Antarctique est une terre utilisée uniquement par des scientifiques, loin de toute activité industrielle. Il mesure plus de vingt-cinq fois la France et est entièrement entouré des eaux de l’océan Austral.La calotte glaciaire antarctique repose majoritairement sur de la terre ferme, mais s’étend également sur la mer sous forme de banquise : 90% de la glace mondiale se trouve en Antarctique.

Fig. 16 : Graphiques représentant le recul de la banquise Arctique.
L’étendue moyenne annuelle de la banquise arctique a diminué au cours de la période 1979 - 2020 à une vitesse qui se situait très probablement entre 3,5 et 4,1 % par décennie (entre 0,45 et 0,51 million de km2 par décennie), et très probablement entre 9,4 et 13,6 % par décennie (entre 0,73 et 1,07 million de km² par décennie) pour le minimum d’été (glace pluriannuelle). La diminution moyenne de l’étendue moyenne décennale de la banquise arctique a été plus rapide en général en été que pour les autres saisons (degré de confiance élevé); l’étendue spatiale a diminué en toutes saisons et à chaque décennie successive depuis 1979 (degré de confiance élevé). À partir des reconstructions, on peut affirmer, avec un degré de confiance moyen, que, sur les trois dernières décennies, le recul de la banquise arctique en été était sans précédent et que les températures de surface de la mer en Arctique étaient anormalement élevées, au moins dans le contexte des 1 450 dernières années.
(Source : GIEC, 
https://www.ipcc.ch/site/assets/uploads/2018/03/WG1AR5_SPM_brochure_fr.pdf)
 
 
Fig. 17 : Graphiques représentant le recul de la banquise Antarctique.
La perte de glace moyenne de la calotte glaciaire de l’Antarctique a probablement augmenté, passant de 30 [-37 à 97] Gt an-1 au cours de la période 1992–2001 à 147 [72 à 221] Gt an-1 au cours de la période 2002–2011. On peut affirmer, avec un degré de confiance très élevé que ces pertes concernent principalement le nord de la péninsule Antarctique et le secteur de la mer d’Amundsen en Antarctique de l’Ouest.
(Source : GIEC, 
https://www.ipcc.ch/site/assets/uploads/2018/03/WG1AR5_SPM_brochure_fr.pdf)
 
3.4 - Étude de cas  n°4 : L’évolution de la technologie règlera les problèmes.
 
Dans cette quatrième et dernière partie, les différents modèles de climat que nous obtenons par l’intermède de ce dataset :
https://ds.data.jma.go.jp/tcc/tcc/products/gwp/temp/list/csv/year_wld.csv 
offrent la possibilité d'anticiper la façon dont le système climatique risque d'être modifié par l'activité humaine au cours du XXIe siècle. Les études s'appuient sur des scénarios qui explorent l'évolution du climat moyen et de sa variabilité en fonction de différents scénarios socio-économiques.

Fig. 18 : Projection du réchauffement jusqu’en 2020
Tous les modèles projettent une poursuite du réchauffement planétaire. Sur la fin du siècle, l'ampleur du réchauffement dépend fortement de l'évolution des émissions de gaz à effet de serre et donc des stratégies d'atténuation du changement climatique.
La réduction des émissions de gaz autres que le CO2 peut représenter un élément important dans les stratégies d’atténuation. À l’heure actuelle, les émissions de GES et les autres agents de forçage ont tous un effet sur le rythme et l’ampleur du changement climatique au cours des quelques décennies à venir, tandis que le réchauffement à long terme est essentiellement fonction des émissions de CO2. 
Fig. 19 : Régression polynomiale du réchauffement avec un scénario dur, en 2100 la température sera à +4°C
 
Il existe des possibilités d’adaptation dans tous les domaines, mais les modalités de mise en œuvre et le potentiel de réduction des risques liés au climat diffèrent selon les secteurs et les régions. Certaines mesures d’adaptation engendrent des co-avantages, des synergies et des contreparties considérables. Si les changements climatiques s’accentuent, les défis associés à un grand nombre d’options d’adaptation s’aggraveront.
 
 
 
Fig. 20 : Régression Facebook Prophet
Dernière projection avec la bibliothèque FB prophet basée sur sklearn permet de mieux prédire dans notre comparaison de scénarios jusqu’en 2120, avec cette méthode le réchauffement est estimé à +2,7°C
Conclusion	 	 	
On peut considérer l'Homme comme le grand responsable du réchauffement climatique que l'on connaît actuellement : il a en effet émis, depuis 1750, de grandes quantités de gaz à effet de serre qui ont engendré une augmentation de la température dans l'atmosphère d'environ 1°C, la nature ayant largement dépassé sa limite d'absorption de ces gaz.
Et le réchauffement de la planète n'est pas près de s'arrêter puisque l'on rejette encore, malgré les accords des COP, des gaz dangereux pour notre avenir. Les conséquences à court terme concernant notre génération, ne sont pas dramatiques : recul des littoraux, intensification des phénomènes extrêmes, bouleversement de l'agriculture, déplacement des espèces animales et végétales... Cependant la menace est bien réelle pour nos descendants : un réchauffement prolongé pourrait porter atteinte à la survie de l'espèce humaine !...
Ainsi, on peut dire que l'Homme représente une menace pour le climat, à cause de sa surproduction de gaz à effet de serre, et réciproquement, le climat représente une menace, à la fois pour l'homme et pour la nature, à travers les nombreux risques qui pèsent désormais sur notre planète.
