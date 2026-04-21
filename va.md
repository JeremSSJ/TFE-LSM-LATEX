Chapitre 4
La valeur temps de l'argent
valuer un projet revient à en comparer les coûts et les bénéfices. Souvent, ces flux
s'étalent dans le temps et l'on doit alors tenir compte de la valeur temps de l'argent.
Tous les projets examinés au chapitre 3 s'étalent, au maximum, sur une période d 'un an.
Mais, en pratique, la durée des projets est souvent beaucoup plus longue. Par exemple,
en 1993, Airbus a lancé l'idée d'un nouvel avion civil long-courrier de grande capacité
(jusqu'à 800 passagers). Le premier A380 n'a été livré qu'en 2007 et Airbus prévoit d'en
vendre pendant plusieurs décennies. Compte tenu de la durée sur laquelle s'étalent les
coûts et les revenus, comment les dirigeants d'Airbus ont-ils évalué la VAN d'un tel projet ?
L'objet de ce chapitre est d'expliquer comment calculer la VAN d'un projet lorsque les
flux sont étalés dans le temps. Il convient d 'abord de bien représenter la séquence de flux
en dressant l'échéancier. Il faut ensuite correctement transposer des flux dans le temps
grâce aux règles de capitalisation et d'actualisation. Il est alors possible de calculer la
valeur actuelle ou future d'une séquence de flux, et donc sa VAN. On peut utiliser ces
techniques pour évaluer n'importe quelle séquence de flux, autrement dit, n'importe
quel actif. Certaines séquences de flux suivent des schémas particuliers : c'est le cas
notamment des annuités et des rentes perpétuelles. Pour chacun de ces cas, il existe des
formules simplificatrices.
4,1. L'échéancier
Avant d'étudier la méthode pour comparer des flux sur plusieurs périodes, il convient
de préciser le vocabulaire employé. Il est possible de représenter graphiquement une
séquence de flux à I 'aide d 'un échéancier ou diagramme des flux (timeline). La construc-
tion d 'un échéancier est souvent la première étape dans la compréhension et la résolution
de problèmes financiers.
Pour illustrer la construction d'un échéancier, prenons le cas d'une banque s'appré-
tant à recevoir d'un emprunteur deux paiements égaux de IO 000 C, à la fin des deux
prochaines années. Ces informations sont représentées sur I 'échéancier suivant :
Date 0
Flux C) €
Aujourd'hui
2
10 000
10000 €
Début de
l'année 1
l'année 2

96
Partie Il - Temps, argent et taux d'intérêt
La date 0 est par convention la date d'aujourd'hui. La date 1 représente la fin de la
première période. L'espace entre la date 0 et la date I représente le temps qui s'écoule
entre ces deux dates — ici, la première année du prêt. À noter que la date I est à la fois la
fin de l'année 1 et le début de l'année 21.
Dans cet exemple, les flux reçus par la banque sont positifs. Dans la plupart des cas, une opéra-
tion financière implique des flux positifs (inflows) et négatifs (outflows). Lorsqu'une banque
prête IO 000 € à un de ses clients qui remboursera en deux versements de 6 000 € à la fin des
deux prochaines années, l'échéancier est, du point de vue de la banque :
Année 2
Date
Flux -10000E
6 000
2
6000 €
Le premier flux a lieu à la date 0, c'est-à-dire aujourd'hui. Il est précédé du signe moins
puisqu'il s'agit d'un flux négatif. Les deux flux égaux à 6 000 € sont des flux positifs.
L'échéancier peut etre utilisé pour représenter des flux se produisant à tout moment de
l'année ; il suffit pour ce faire de changer la définition de la longueur d'une période
(de l'année au mois).
Construction d'un échéancier
Problème
Les frais de scolarité d'une grande école de commerce sont de 10 000 € par an. La
scolarité dure deux ans. Les paiements doivent être effectués à parts égales à chaque
début de semestre. Quel est le diagramme de flux ?
Solution
Si l'on considère que le premier semestre débute aujourd 'hui, le premier versement
a lieu à la date 0. Les paiements suivants sont espacés d'un semestre. Le diagramme
de flux est :
Date O
Flux -SOOO€
-5000E
2
-5 000 €
3
-5000E
4
La plupart des diagrammes de flux de ce chapitre sont très simples, au point de paraitre
inutiles. Cependant, plus les problèmes se compliquent, plus le recours à un diagramme
de flux est nécessaire pour répertorier tous les flux, sans risquer d'en oublier.
C'est.à.dire qu'il n'y a pas de différence entre un flux versé 23 h 59 le 31 décembre de l'année N et un flux
versé à 0 h 01 le janvier de I •année N 4 1. bien qu'en pratique Ce ne soit pas tout à fait similaire. en raison
notamment de la fiscalité ; ce point est pour l'instant ignoré.


Chapitre 4 - La valeur temps de l'argent
4,2. Les trois règles du « voyage dans le temps »
Les décisions financières impliquent le plus souvent de comparer des flux se produisant
à différentes dates. Ces comparaisons doivent suivre trois règles.
Règle I : comparer les flux
Première règle : pour comparer des flux se produisant à différentes dates, il faut tenir
compte de la valeur temps de l'argent.
Cette règle traduit un des enseignements du chapitre 3 : seuls des flux exprimés dans
une méme unité peuvent étre comparés. Or, 1 € aujourd 'hui et I € demain ne sont pas
équivalents. Disposer immédiatement d'une certaine somme d'argent a plus de valeur
que de disposer de cette somme dans le futur : on peut placer l'argent dont on dispose
aujourd'hui, ce qui rapporte des intérêts. Pour comparer des flux à différents dates, il
faut donc les convertir dans la méme unité : autrement dit, il faut les transposer dans le
temps. Les deux prochaines règles régissent le « voyage dans le temps
Règle 2 : transposer des fux dans le futur
On dispose de 1 000 € aujourd'hui. On désire déterminer le montant équivalent à cette
somme dans un an. Si le taux d'intérêt est de IO % sur le marché, il est possible d'utiliser
ce taux d 'intérêt comme un taux de conversion (un taux de change) pour transposer les
flux dans le futur. En effet :
(1 000 € aujourd'hui) x (1,1 € dans un an pour I € aujourd'hui) = 1 100 € dans un an
De manière générale, si le taux d'intérêt annuel est r, il est possible de multiplier un flux
actuel de début d'année par le facteur de taux d'intérêt (l + r) pour le transposer en fin
d'année. On peut recourir à cette règle plusieurs fois d'affilée. Si on désire calculer la
valeur dans deux ans de 1 000 € reçus aujourd'hui et que le taux d'intérêt la seconde
année soit toujours de IO on obtient :
(1 100 € dans un an) x (1,1 € dans deux ans par euro dans un an) = 1 210 € dans deux ans
L'échéancier est ainsi :
2
1 000 1 100 1
1.10
1,10
Avec un taux d'intérêt de IO %, tous les flux (1 000 € à la date 0 ; 1 100 € à la date I ;
1 210 € à la date 2) sont équivalents. Ils sont cependant exprimés dans des unités diffé-
rentes, puisqu' ils se produisent à différents moments. Les flèches vers la droite indiquent
que les flux sont transposés dans le futur.
La valeur d'un flux transposée dans le futur est qualifiée de valeur future (ou valeur
à terme, ou valeur acquise). Dans l'exemple précédent, 1 210 € est la valeur future de
1 000 € dans deux ans. Le montant augmente quand on transpose des flux dans le futur.
La différence entre la valeur future d'un flux et le flux aujourd'hui exprime la valeur
97


98
Partie Il - Temps, argent et taux d'intérêt
temps de l'argent : en disposant de l'argent plus tôt, on peut le placer, en tirer des intérêts
et obtenir ainsi plus d'argent à l'avenir.
On remarque par ailleurs que la valeur future augmente de 100 € la première année
et de 110 € la seconde. La seconde année, les intérêts gagnés sont calculés sur les 1 000 €
de départ mais également sur les 100 € d'intérêts reçus à la fin de la première année.
Lorsque les intérêts portent eux-mêmes intérêts (ce qui est le cas dans cet exemple), on
parle d 'intérêts composés (autrement, on parle d'intérêts simples). Le procédé visant à
transposer des flux dans le futur est connu sous le nom de composition ou capitalisa-
tion des intérêts.
Deuxième règle : pour transposer un flux dans le futur, il faut le capitaliser.
Comment se modifie la valeur future si la transposition porte sur trois périodes ? Si l'on
considère que le taux d'intérêt la troisième année est toujours de IO h, en capitalisant le
flux initial de 1 000 € sur trois ans, on obtient :
1 OOOX (1 + x (1 + (1 + 1 000 x (1 + 1 331 €
Plus généralement, pour transposer un flux F dans n périodes futures, il faut le capita-
liser n fois. Si le taux d' intérêt r est constant, la valeur future dans n périodes (VF„) est :
Valeur future d'un flux
(4.1)
n fois
La figure 4.1 montre l'importance de la capitalisation dans l'accumulation de richesse.
Quand un individu place de l'argent sur un compte rémunéré et qu'il laisse les intérêts
s'accumuler, il touche des intérêts sur les intérêts des périodes précédentes. Au début,
les intérêts sur les intérêts sont faibles. Mais si l'on considère des périodes suffisam-
ment longues, les intérêts sur les intérêts se révèlent substantiels comme l'illustrent la
figure 4.1 et l'exemple 4,2.
La puissance de la capitalisation
Problème
Vous placez 1 000 € sur un compte rémunéré au taux annuel de 10 0,6, Quel est le
solde de ce compte dans 7 ans 20 ans ? 40 ans ? 75 ans ?
Solution
Il suffit d'appliquer la formule (4,1) :
dans 7 ans: 1 OOO€X (1 + 10 = 1948,72€
dans 20 ans : 1 OOO€X (1 + 10 6727,50€
dans 40 ans : 1 000 € x (l + IO
= 45 259,26 €


Chapitre 4 - La valeur temps de liargent
Dans 75 ans : 1 € x (1 + 10 = 1 271 895,37 e. En 7 ans, vous avezdoublé
votre capital. En 20 ans, celui-ci a été multiplié par 6,7. Que se passe-t-il les 20 années
suivantes ? La richesse obtenue par euro investi pendant 40 ans n'est pas le double de
celle obtenue en 20 ans, mais son carré (6,72, soit 45 € environ par euro investi). Une
croissance de ce type est qualifiée de croissance géométrique. Au bout de 75 ans,
vous êtes millionnaire !
99
e 000
7 000
6 000
s 000
4 000
3 000
2 000
1000
o
Intérêts sur les intérêts
Intérêts Sur le principal 1 000
Principal de 1 000 €
2
7
8 9 10 11 12 13 14 15 16 17 18 19 20
Année
Figure 4.1 - La capitalisation des intérêts dans le temps
La part du principal, des intérêts Sur le principal et des intérêts Sur les intérêts évolue au Cours du
temps. Ainsi, pour un taux d'intérêt de 10 le montant des intéréts sur les intérêts accumulés au
bout de IS ans dépasse le montant des intéréts sur le principal. Après 20 ans, pour un principal de
1 000 les intérêts sur les intérêts s'élèvent à 3 727,50 tandis que les intérêts sur le principal
S'élèvent à 2 000


100
Partie Il - Temps, argent et taux d'intérêt
Règle 3 : transposer des nux dans le passé
La troisième règle décrit comment transposer un flux dans le passé. Si l'on désire
connaitre la valeur aujourd'hui de 1 000 € à recevoir dans un an et que le taux d'interet
soit de IO il est possible de procéder comme au chapitre 3 :
(1 000 € dans un an)/ (1,1 € dans un an par euro aujourd'hui) = 909,09 € aujourd'hui
Pour transposer un flux dans le passé, il faut le diviser par le facteur d'intérêt, (1 + r),
avec r le taux d'intérêt. Ce procédé consistant à transposer dans le passé un flux (en
calculant la valeur aujourd'hui d 'un flux survenant dans le futur) est appelé actualisa-
tion (discounting).
Troisième règle : pour transposer un flux dans le passé, il faut l'actualiser.
Afin d 'illustrer cette règle, supposons qu'un agent anticipe de recevoir 1 000 € dans deux ans.
Si le taux d'intérêt annuel est de IO % pour les deux prochaines années, l'échéancier est :
1
2
+ 1.10
Avec un taux d'intérêt de IO %, tous les flux (826,45 C à la date O ; 909,09 € à la date 1 ;
1 000 € à la date 2) sont équivalents. Les flèches vers la gauche indiquent que les flux sont
transposés dans le passé, c'est-à-dire actualisés. La valeur des flux diminue quand on
les transpose dans le passé.
La valeur actuelle à la date 0 de 1 000 € dans deux ans est égale à 826,45 C. Pour le dire
autrement, si on place 826,45 € pendant deux ans au taux d'intérêt annuel de IO %, ce
placement aura une valeur future de 1 000 € (d 'après la deuxième règle) :
x 1,10
2
1,10
Si on reçoit les 1 000 € dans trois ans, avec un taux d'intérêt annuel de IO 96, on a :
0
751.31 €
2
3
1 ooo€
1,10
Autrement dit, la valeur actuelle d'un flux de 1 000 € dans trois ans est :
1 000 + 10 (1 + 1096) x (1 + 10 = 1 000/(1 + 10 = 751,31 €
Plus généralement, pour transposer un flux F jusqu'à un point n périodes avant qu'il
ne se produise, il faut l'actualiser n fois. Cela signifie qu'il faut diviser le flux F par
n facteurs de taux d'intérêt. Si le taux d'intérêt r est constant :
Valeur actuelle d'un flux
(4.2)


Chapitre 4 - La valeur temps de l'argent
Valeur actuelle d'un nux futur simple
Problème
On envisage l'achat d'une obligation. Ce titre donne droit à un flux unique de
15 000 € dans IO ans. Le taux d'intérêt, sur le marché, est de 6 Quelle est la valeur
de l'obligation aujourd'hui ?
Solution
Les flux de cette obligation sont représentés par l'échéancier suivant :
15
L'obligation a une valeur (future) de 15 000 € dans IO ans. Afin de déterminer sa
valeur aujourd 'hui, il faut calculer sa valeur actuelle :
VA 15000/ 1,061') 8 375,92 € aujourd'hui
Cette obligation vaut aujourd'hui nettement moins que le flux auquel elle donne
droit dans IO ans, en raison de la valeur temps de l'argent.
Application des règles du « voyage dans le temps »
Les trois règles du « voyage dans le temps » permettent de comparer et de combiner des
flux se produisant à différents moments. Si on envisage de placer 1 000 € aujourd'hui et
1 000 € à la fin de chacune des deux prochaines années et que le taux d'intérêt annuel
soit de IO quelle somme obtient-on dans trois ans ?
101
3
1000E
1000€
2
1000€
Il est possible d'utiliser les règles du « voyage dans le temps » de différentes façons pour
répondre à cette question. Tout d'abord, on peut transposer le placement de la date O à
la date l. Puisque les deux placements seront exprimés dans la méme unité, il sera alors
possible de les additionner pour trouver le montant total placé à la date 1 :
2
1000E
3
1000E
1 100 €
1,10
2 100€
Compte tenu des deux premières règles du « voyage dans le temps le placement total
à la date I est de 2 100 e. Ensuite, on transpose cette somme de la date I à la date 2, puis à
la date 3 :

102
Partie Il - Temps, argent et taux d'intérêt
1,10
1,10
2
1 ooo€
2 310 €
3310E
1,10
3
1 ooo€
1.10
1 000 €
1 100€
2 100€
1,10
Le montant total à la fin des trois ans est de 3 641 €- Ce montant est la valeur future des
trois placements de 1 000 € étalés dans le temps.
Une autre approche est possible : calculer la valeur future à la date 3 de chaque flux
considéré indépendamment des autres, puis les additionner.
2
1.10
1000€
3
1 331
1.10
1 210E
1,10
1,10
3641 c
Les deux méthodes donnent la méme valeur future. Lorsque les règles sont respectées,
le résultat est toujours le meme — quel que soit l'ordre dans lequel ces règles sont appli-
quées. Le tableau 4.1 résume les trois règles du « voyage dans le temps ».
Les trois règles du voyage dans le temps
Règle 2
Règle 3
Seuls des flux exprimés à une méme date peuvent étre comparés ou combinés
Pour transposer des flux dans le futur, il faut les capitaliser :
Valeur future d'un flux : VF, Fx (1 + rp
Pour transposer des flux dans le passé, il faut les actualiser :
Valeur actuelle d'un flux : VA F/(l +
Calculer la valeur future d'un
Problème
Reprenons le diagramme des flux précédent : placement de 1 000 € par an pendant
trois ans à partir d'aujourd'hui. Si le taux d'intérêt annuel est de IO %, de quelle
somme disposera-t-on dans trois ans ?


Chapitre 4 - La valeur temps de l'argent
103
Solution
1 ooo€
1000E
2
1000E
3
Il existe plusieurs manières de répondre à cette question. Outre les deux méthodes
considérées plus haut, on peut calculer la valeur actuelle de chaque flux (soit en
prenant les flux indépendamment les uns des autres, soit en cumulant leurs valeurs
actuelles à chaque étape) puis la transposer dans trois ans.
3
1 000 €
2
1000 €
826.45€
2 735,54 €
Placer 2 735,54 € aujourd'hui est équivalent à placer 1 000 € par an pendant trois
ans. La valeur future à la date 3 de ce placement est alors :
2
3
2 735.54 €
Le résultat obtenu, 3 641 C, est le mème que précédemment. Tant que les trois règles
du « voyage dans le temps » sont appliquées correctement, elles fournissent toujours
une seule réponse : la bonne !
4.3. Valeur actuelle et future d'une séquence de flux
Dans la plupart des projets d'investissement, les flux sont multiples et apparaissent à
différentes dates. Pour calculer la valeur actuelle ou future de ces projets, il convient
donc de généraliser ce qui précède aux cas d'une séquence de flux. Considérons une
séquence de flux : Fo à la date 0, F1 à la date l, et ainsi de suite, jusqu'à FN à la date N.
Fo
F,
La valeur actuelle de cette séquence de flux, pour un taux d'intérêt r, peut être calculée
en deux étapes. Tout d 'abord, on calcule la valeur actuelle de chaque flux, sans consi-
dérer les autres. Une fois ces flux exprimés dans la méme unité (en euros aujourd'hui),
on peut les combiner.

104
Partie Il - Temps, argent et taux d'interét
(14 rp
F
F1
(14 r)
2
F,
La formule générale permettant de calculer la valeur actuelle d'une séquence de flux est
donc :
FN
VA Fo + —
(1 + r) (1+r)2
Cette formule peut etre réécrite :
Valeur actuelle d'une séquence de flux
rt_o ( 1 +
(4.3)
(4,4)
L'opérateur signifie « somme des éléments individuels pour chaque date tt allant de 0
à N Notons que (l + l.
La valeur actuelle d 'une séquence de flux est donc égale à la somme des valeurs actuelles
des flux qui composent la séquence. Ainsi, par analogie avec un flux unique, la valeur
actuelle d'une séquence de flux est le montant que l'on doit investir aujourd'hui pour
produire la séquence de flux Fo, FI, a, FN.
La valeur actuelle d'une séquence de flux quelconque
Problème
Un étudiant a besoin d'argent pour s'acheter une voiture. Son père accepte de lui
prêter l'argent nécessaire. L'étudiant s'engage à rembourser le prét dans les quatre
ans et propose d'offrir à son père une rémunération égale au taux d'un placement
bancaire. Le jeune diplômé pense pouvoir verser 5 000 € dans un an puis 8 000 € par
an les trois années suivantes. Si le taux d 'intérêt est de 6 quelle somme I 'étudiant
peut-il emprunter à son père ?

Chapitre 4 - La valeur temps de l'argent
Solution
Les flux promis à son père par le jeune diplômé sont les suivants :
105
5000E
2
8 000
3
8000E
4
8000 €
Le montant du prét est équivalent à la valeur actuelle des flux promis par le fils :
VA = (5 000/ 1,06) + (8 000/ 1,062) + (8 000/ 1,063) + (8 000/ 1,064)
-4 716,98 + 7 119,97 + 6 716,95 + 6 336,75
- 24 890,65
Le père peut préter 24 890,65 € en échange des paiements promis. Ce montant est
inférieur à la somme des versements (5 000 + 8 000 + 8 000 + 8 000 = 29 000 C)
en raison de la valeur temps de l'argent. Pour le père, préter cette somme à son fils
plutôt que de la placer sur un compte rémunéré revient-il au même ?
• Si le père avait placé pendant quatre ans 24 890,65 € à la banque au taux de 6 %,
il aurait obtenu en fin de période : VF = 24 890,65 x = 31 423,87 € dans
quatre ans.
• Si le père prete l'argent à son fils et place sur un compte rémunéré les flux qu'il
reçoit de son fils au titre des remboursements, la valeur future disponible pour
le père est :
5000€
x 1.06
2
8000 €
5300 €
3
8 ooo€
4
8 000
x 1,06
22 098 € 23 423,88
x 1,06
31 423,88
Le père dispose bien de la même richesse finale, qu'il place son argent sur un compte
rémunéré ou qu'il le prête à son fils.
La dernière partie de l'exemple 4.4 illustre un point très général. Si on veut calculer la
valeur future d'une séquence de flux, on peut le faire directement (c'est le second cas de
l'exemple 4-4) ou calculer d 'abord la valeur actuelle et ensuite la transposer dans le futur
(premier cas). Chaque démarche respecte les règles du « voyage dans le temps » et donne
donc le même résultat. En généralisant, on obtient la formule suivante qui lie la valeur
actuelle et la valeur future dans n périodes d 'une séquence de flux.
Valeur future et valeur actuel le d'une séquence de flux
(4.5)

106
Partie Il - Temps, argent et taux d'interét
4.4. La valeur actuelle nette d'une séquence de flux
Un projet peut être représenté sur un échéancier comme une séquence de flux, où les
sorties d'argent (les dépenses et investissements) sont des flux négatifs et où les entrées
d'argent (les recettes) sont des flux positifs. La valeur actuelle nette (VAN) d'un projet,
telle qu'au chapitre 3, peut donc se calculer comme la valeur actuelle de tous les flux
présents et futurs associés à ce projet :
VAN VA (Bénéfices) — VA (Coûts) = VA (Bénéfices — Coûts)
La VAN d'un projet d'investissement
Problème
(4,6)
Un de ses amis propose à Clément d'investir dans un projet. Si Clément investit
1 000 € aujourd'hui dans le projet, il aura droit à 500 € à la fin de chacune des trois
prochaines années. Clément a, par ailleurs, la possibilité de placer de l'argent au taux
de 10 % par an. Clément doit-il investir dans le projet que lui propose son ami ?
Solution
Comme toujours, il faut commencer par construire l'échéancier. L'investissement
de départ est un flux négatif et les revenus ultérieurs sont des flux positifs.
-1 ooo€
500 €
2
500 €
3
500 €
Afin de savoir s'il convient, ou non, d'accepter le projet, il faut calculer la VAN de la
séquence de flux :
VAN = -1 000 + (500/1,1) + (500/1,12) + (500/1,13) = 243,43 €
La VAN est positive, ce qui signifie que les bénéfices actualisés excèdent les coûts. Il
faut donc accepter la proposition, car elle est équivaut à recevoir 243,43 € aujourd'hui.
Supposons que Clément emprunte 1 243,43 € aujourd'hui. Il peut utiliser 1 000 €
pour investir dans le projet que son ami lui propose ; il dispose en outre de 243,43 €
qu'il peut dépenser à sa guise. Quelle somme doit-il rembourser dans trois ans ?
Avec un taux d'intérêt de IO 96, le remboursement est de :
VF 1 243,43 x 1 655 € dans trois ans
Parallèlement, le projet proposé à Clément lui permet de bénéficier de 500 € à la
fin de chacune des trois prochaines années, qui peuvent être placés sur un compte
rémunéré. Dans trois ans, le solde du compte sera :
VF = (500 X 1,12) + (500 X 1,1) + 500 = 1 655 € dans trois ans
Clément peut utiliser cette somme pour rembourser le prêt et payer les intérêts
associés. Profiter de l'opportunité de placement permet donc à Clément de gagner
immédiatement 243,43 € sans aucun coût futur.

Chapitre 4 - La valeur temps de l'argent
Calculer la valeur actuelle
Les opérations d'actualisation et de capitalisation des flux peuvent étre réalisées à
l'aide de n'importe quelle calculatrice, mais il est souvent plus pratique d 'utiliser un
tableur, de type Excel (ou autre). Reprenons l'exemple 4,5.
107
I Tau'
4 Facteur dactualisaban
6 VAN
-t OOO.OO
1.000
-t oco.oo
243,43
500.00
454.55
2
500.00
01826
413,22
3
500,00
Les données du problème, à savoir le taux d 'actualisation et la séquence de flux, sont
renseignées dans les lignes I à 3. La ligne 4 permet de calculer le facteur d'actuali-
sation, I / (I + r)" pour chaque date (colonnes B à E). On multiplie ensuite chaque
flux par le facteur d'actualisation correspondant, pour obtenir les valeurs actuelles
ligne 5. Enfin, ligne 6, on additionne les valeurs actuelles pour obtenir la VAN.
Les formules sont les suivantes :
Facteur
5 VACFt)
6 VAN
=BYB4
-0304
=EYE4
-SOMME
On peut également calculer la VAN en une seule étape en utilisant la formule Excel
VAN(taux ;valeurl ;valeur2 ;.. Il est toutefois préférable de ne pas céder à la tentation et
de calculer la VAN étape par étape. Cela permet d'apprécier la contribution de chaque
flux à la VAN globale. En outre, I 'utilisation de cette formule est souvent source d
En effet, cette formule suppose que le premier flux est enregistré à la date I. Autrement
dit, s'il y a un flux à la date O, il ne faut pas oublier d'en tenir compte séparément. Par
exemple, dans I précédent, la formule de la VAN serait : 83 4
Un autre problème tient à ce que la formule Excel traite différemment un flux nul et
une cellule vide ; dans le dernier cas, Excel ignore en effet à la fois le flux et la période.
Dans l'exemple suivant, le flux à la date 2 a été supprimé : ligne 6, le calcul de la VAN est
correct ; en revanche, ligne 7, le calcul réalisé en utilisant la formule Excel considère que
le dernier flux, celui de la date 3, se produit à la date 2, ce qui est manifestement faux.
2
3
4
6
7
4.5.
Taux Cactuaisation
Période
Flux Ft
F acteur Cactualisatjon
5 VA(Ft)
VAN
VAN fonction Excel
c
1
-1 00000
500.00
1,000
0.909
-1 00000
454.55
-169,80
-13223 =B3+VAN BI 03:E3
D
2
0826
0,00
3
500.00
0751
375.66
Rentes perpétuelles, annuités et autres cas particuliers
Les formules développées jusqu'à maintenant permettent de calculer les valeurs
actuelles et futures de n' importe quelle séquence de flux. Mais, en pratique, lorsque les

108
Partie Il - Temps, argent et taux d'intérêt
flux s'étalent sur plus de quatre ou cinq périodes (ce qui est souvent le cas), les calculs
peuvent étre longs et fastidieux. Dans certains cas particuliers, il existe toutefois des
formules simplifiées.
Les rentes perpétuelles
Une rente perpétuelle (perpetuity) est un titre de dette qui prévoit le paiement régulier
d'intérêts mais pas le remboursement du capital ; une rente perpétuelle n'a donc théo-
riquement pas de terme. En pratique, elle s'achève lorsque l'emprunteur fait faillite ou
décide de racheter tous les titres en circulation sur le marché. L'émission de nouveaux
titres de rente perpétuelle est rare sur les marchés, mais comprendre la façon dont on les
évalue est très utile.
Une rente perpétuelle garantit à son détenteur, pour toujours, un flux fixe payé à inter-
valles réguliers. L'échéancier est donc2 :
(1+r)3 _ (1 +r)"
2
3
La valeur actuelle d'une rente perpétuelle composée de F flux constants, lorsque le taux
d 'intérêt est r, est :
F
F
Dans la formule, aucun flux n'est indicé puisque, par définition, tous les flux sont égaux
à E Comment est-il possible de calculer la somme d'une séquence infinie de flux ? Pour
ce faire, il faut remarquer que le facteur d'actualisation devient très grand à mesure
que n augmente, de sorte qu'un flux très éloigné dans le temps sera négligeable une fois
actualisé'.
Supposons que l'on puisse placer 100 € sur un compte bancaire rémunéré à 5 % par an à
l'infini. À la fin de la première année, la valeur acquise de ce dépot est de 105 € (100 € +
5 € d'intérêts), Supposons que l'on retire les 5 € d'intérêts. À la fin de la deuxième année,
le compte est de nouveau créditeur de 105 €- On retire de nouveau 5 €- En agissant ainsi
année après année, on peut retirer 5 € chaque année, et ceci à l'infini :
— 100 105 €
2
105 €
-100 €
3
105
-100 €---e
2,
3.
Sur le diagramme des flux, le premier flux n'est pas versé immédiatement, mais au terme de la première
période. On parle alors d 'intérêts posrcomprës. ou terme échu. Quand l'intérêt est payé en début de période,
on parle d ' intérêts précomptés, ou terme à échoir. En général et sauf mention contraire, les intérêts sont post-
comptés. Voir le chapitre 5 pour plus de détails.
En termes mathématiques, on parle de suite géométrique ; une telle suite converge si r > 0.


Chapitre 4 - La valeur temps de l'argent
En plaçant 100 € à la banque aujourd'hui, on crée donc une rente perpétuelle de 5 € par
an. D'après la Loi du prix unique, un mème actif doit avoir un prix identique sur tous
les marchés. La valeur actuelle d 'une rente perpétuelle de 5 € par an doit par conséquent
étre de 100 €.
Généralisons ce raisonnement. En plaçant P € sur un compte bancaire, il est possible
de retirer chaque année les intérêts, F = r x P, et laisser le principal, P, sur le compte. La
valeur actuelle de la rente perpétuelle qui paie un flux constant F chaque année est donc
égale à p ; autrement dit' :
Valeur actuelle d'une rente perpétuelle constante
VA (F perpétuel) = F/ r
(4,7)
En déposant F/r€ aujourd'hui, il est possible de profiter de (F/ r) x r = F € d'intérêts à
chaque période future, à l'infini.
Quelques exemples de rentes perpétuelles
Les entreprises émettent parfois des titres de dettes, qu'elles qualifient de rentes
perpétuelles mais qui n'en sont pas vraiment. Ainsi, en 2010, la banque HSBC a
émis pour 3,4 milliards de dollars de titres de dettes sous la forme d'obligations
(prétendument) perpétuelles. Ces titres n'ont pas de maturité fixée, mais la banque
se réserve la possibilité de rembourser son emprunt dans cinq ans et demi, raison
pour laquelle il ne s'agit pas réellement d 'une rente perpétuelle.
La plus ancienne rente perpétuelle qui paie aujourd'hui encore des intérêts a été
émise au XVIIe siècle par Hoogheemraadschap Lekdijk Bovendams, une entreprise
néerlandaise chargée de l'entretien des digues. Deux professeurs de l'université de
Yale, William Goetzmann et Geert Rouwenhorst, ont vérifié que ces obligations
versaient toujours des intérêts ; pour ce faire, ils ont acheté, le Ier juillet 2003, l'une
de ces obligations et ont récupéré 26 années d'arriérés d'intérêts. La rente verse
aujourd'hui 11,34 € d'intérêts chaque année.
Les rentes perpétuelles comptent, en fait, parmi les titres de dettes les plus anciens
de l'histoire. Elles existent depuis le XIIe siècle en Italie, en France* et en Espagne.
Au départ, elles ont été créées pour contourner les lois contre l'usure édictées par
l'Êglise catholique. Les rentes perpétuelles ne prévoyaient pas le remboursement du
principal ; elles n'étaient donc pas considérées comme des prêts par I 'Église.
En 1535, François Ier lance le premier emprunt public français qui prend la forme d 'une rente perpétuelle.
Au XIXe siècle. en France, les rentes perpétuelles d'État sont encore parmi les titres les plus négociés sur
le marché. Elles sont ensuite tombées en désuétude et, en 1988. les dernières rentes perpétuelles émises
par l'État ont été rachetées et retirées du marché. Voir I.-M. Vaslin (2007). Le siècle d'or dela rente
perpétuelle française dans Le Marché financierfrançais au xtxe siècle, vol. 2 (dir- G. Gal lais-Hamonno).
Publications de la Sorbonne.
4. La démonstration mathématique de ce résultat figure en annexe sur Internet. mais elle est beaucoup moins
intuitive.
109


110
Partie Il - Temps, argent et taux d'intérêt
Créer une rente perpétuelle
Problème
L'association des étudiants du master finance décide de créer un gala annuel et
souhaite mettre en place un plan de financement qui assure la pérennité de l'évé-
nement. Le coût annuel d'un gala est de 30 000 C. Les placements sont rémunérés
au taux de 8 %. Le premier gala est prévu dans un an. Quelle somme l'associa-
tion doit-elle placer afin de pouvoir financer l'organisation du gala chaque année
éternellement ?
Solution
L'échéancier est le suivant :
30000 c
2
30 000 €
3
30 000 €
Il s'agit d'une rente perpétuelle constante de 30 000 € par an. La somme que doit
placer I 'association correspond à la valeur actuelle de cette séquence de flux. Donc :
VA = F,'r = 30 000/0,08 = 375 000 C.
Si I 'association place aujourd'hui 375 000 € sur un compte rémunéré à 8 le gala
annuel pourra avoir lieu chaque année.
Actualiser plus que nécessaire
La formule de la rente perpétuelle est fondée sur le fait que le premier flux se produit
à la fin de la première période (à la date l). Il se peut toutefois que les flux de rentes
perpétuelles commencent plus tard. Il est tout de mème possible d'utiliser l'équa-
tion (4.7), mais en faisant attention à ne pas commettre une erreur relativement
courante,
Reprenons I 'exemple 4,7, celui du gala d'étudiants. Supposons que le premier gala a
lieu non pas dans un an, mais dans deux ans. Comment cela modifie-t-il la somme
à placer ?
L'échéancier est désormais :
2
30 000
3
30000 €
Il faut déterminer la valeur actuelle des flux, qui est égale à la somme qu'il convient
de placer aujourd'hui. Mais on ne peut pas appliquer directement l'équation (4.7),
car les flux ne suivent pas exactement ceux d'une rente perpétuelle telle qu'elle a été
définie : il n'y a pas de flux à la fin de la première période. Si on se place à la date I


Chapitre 4 - La valeur temps de l'argent
(et non à la date 0), le premier flux est bien versé au bout d'un an (à la date 2), puis
les flux suivants sont versés périodiquement : en se plaçant à la date 1, il est possible
d'appliquer directement la formule de la rente perpétuelle. D'après l'exemple précé-
dent, on sait qu'il faut placer 375 000 € à la date I pour financer les galas à venir.
Réécrivons ainsi l'échéancier :
111
2
30 000
3
30 000
La question est désormais de savoir combien on doit placer à la date 0 (aujourd'hui)
pour disposer de 375 000 € à la date 1. C'est un calcul de valeur actuelle :
VA 375 000/ 1,08 347 222 € aujourd'hui
L'erreur à ne pas commettre est d'actualiser deux fois 375 000 € en pensant que le
premier gala se déroule dans deux ans : la formule de la rente perpétuelle considère
que les flux démarrent une période après la date présente. Cette erreur concerne les
rentes perpétuelles, mais également les annuités et d 'autres cas particuliers abordés
dans ce chapitre.
Les annuités constantes
Une annuité est une séquence de N flux égaux se produisant à intervalles réguliers.
L'intervalle de temps séparant deux flux consécutifs est la période. Souvent la période
est d'un an, mais on utilise le terme d'annuité même lorsque la période est d'un
trimestre, d'un mois.
Lorsque tous les flux sont égaux, on parle d'annuité constante. La différence entre une
annuité constante et une rente perpétuelle est que le nombre de flux est limité pour
une annuité constante. La plupart des prêts automobiles, des prêts immobiliers et des
obligations sont des annuités constantes. Les flux d'une annuité constante peuvent être
représentés sur un échéancier :
Valeur actuelle d'une annuité constante. La valeur actuelle (VA) d'une annuité de
N périodes, avec un flux F constant (en fin de période) et un taux d 'intérêt r, est :
S. par extension, le mot annuité désigne les flux eux-mêmes, mais uniquement lorsque la période est d'un an ;
lorsque la période est d 'un mois on utilise le mot mensualité pour désigner les flux.

112
Partie Il - Temps, argent et taux d'intérêt
Lorsque le nombre de périodes N est grand, peut-on trouver une formule pour calculer
directement la valeur actuelle d'une annuité constante ? Considérons un placement de
100 € qui rapporte 5 % d'intérêt. À la fin de l'année, on dispose de 105 C. Comme avec
une rente perpétuelle, il est possible de retirer chaque année 5 € tout en laissant en
permanence 100 € sur le compte. Mais, contrairement au cas de la rente perpétuelle, le
compte peut être clôturé en retirant le principal ( 100 C), par exemple au bout de 20 ans.
Dans ce cas, les flux sont :
100€-----'
2
20
.----+ 105 €
-100 C
Avec un placement initial de 100 €, on crée une annuité de 5 € pendant 20 ans, auxquels
s'ajoute un flux de 100 € dans 20 ans. D'après la Loi du prix unique :
100 € = VA (annuité de 5 € pendant 20 ans) + VA (100 € dans 20 ans)
En réorganisant les termes, on obtient :
VA (annuité de 5 € pendant 20 ans) = 100 € — VA (100 € dans 20 ans)
100-(100/ 1,0520) 62,31 €
La valeur actuelle d'une séquence de flux de 5 € reçus à la fin de chaque année pendant
20 ans est donc de 62,31 Il est possible de généraliser ce résultat. Un agent place P €
sur un compte rémunéré et en retire à chaque période les intérêts, soit F = r x P €. Après
N périodes, il clôture le compte. Pour un montant initial P, il reçoit une annuité d'un
montant F à la fin de chaque période pendant N périodes, puis récupère le montant
initial p au bout de N périodes :
P = VA (annuité de F pendant N périodes) + VA (P à la date N)
Si l'on réorganise les termes, la valeur actuelle de I 'annuité constante est :
VA(annuité de F pendant N périodes) = P —VA (P à la période N)
(4,8)
Le paiement périodique F est égal aux intérêts de chaque période : F = r x P. Il est
possible de réorganiser l'équation (4.8), en remplaçant P par F/r :
Valeur actuelle d'une annuité constante6
VA(annuité de F pendant N périodes avec un taux d'intérêt r) F x — I
(4,9)
6. L'astronome Edmond Halley a été le premier à démontrer cette formule (OfCompound Interest. publication
posthume par H. Sherwin, Sherwin's Mathematical Tables, Londres, T. Page & Son, 1761

Chapitre 4 - La valeur temps de l'argent
Valeur actuelle d'une annuité constante
Problème
La loterie nationale propose à ses gagnants de recevoir soit un versement annuel de
I million d 'euros pendant 30 ans (le premier versement ayant lieu aujourd'hui), soit
15 millions d'euros immédiatement. Le taux d'intérêt est de 8 Quelle solution
retenir ?
Solution
La première solution offre 30 millions d'euros, mais échelonnés dans le temps. Il
faut donc calculer la valeur actuelle de cette séquence de flux :
113
1 million
1 million
1 million
1 million
Le premier versement ayant lieu aujourd'hui, le dernier paiement aura lieu dans
29 ans (pour un total de 30 versements). Le million d'euros versé aujourd'hui est
déjà en valeur actuelle. Il suffit donc de calculer la valeur actuelle des 29 flux futurs :
il s'agit d'une annuité constante de I million d'euros pendant 29 ans, donc :
VA (annuité de I million d'euros pendant 29 ans) = I million x
0,08
11,16 millions d'euros aujourd'hui
Ainsi, la valeur actuelle des flux est de I + 11,16 = 12,16 millions d'euros.
La seconde solution consiste à recevoir immédiatement 15 millions d'euros. Elle est
donc plus intéressante que la première, même si le montant versé est moitié moindre.
Cette différence est directement liée à la valeur temps de l'argent. Avec 15 millions
d'euros aujourd'hui, il est possible de dépenser immédiatement 1 million d'euros
et de placer les 14 millions restants au taux d'intérêt de 8 %. Cette stratégie permet
d'obtenir 14 millions x 0,08 1,12 million d'euros par an à perpétuité ! 11 est égale-
ment possible de dépenser immédiatement 15 — 11,16 3,84 millions d'euros et
de placer 11,16 millions d'euros pour obtenir 1 million d'euros par an pendant les
29 prochaines années.
Valeur future d'une annuité constante. Maintenant que l'on dispose d'une formule
simple permettant de calculer la valeur actuelle d'une annuité constante, il est facile
de calculer sa valeur future : pour connaitre la valeur d'une annuité constante dans
N périodes, il faut transposer sa valeur actuelle dans N périodes, c'est-à-dire capitaliser
la valeur actuelle pendant N périodes au taux d'intérêt r :


114
Partie Il - Temps, argent et taux d'intérêt
Valeur future d'une annuité constante
(VF annuité constante) VA x (1 +
Se constituer une épargne-retraite
Problème
(4.10)
Stéphanie a 35 ans et s'inquiète pour sa retraite. Elle décide d'épargner 10 000 € tous
les ans jusqu'à ses 65 ans. Le compte retraite est rémunéré à IO De quelle somme
Stéphanie disposera-t-elle le jour de ses 65 ans ?
Solution
L'échéancier est le suivant :
35
36
10000
37
10000 c
65
10000 €
La séquence des flux correspond à une annuité constante de 10 000 € pendant
30 ans. Il suffit de calculer la valeur future de cette annuité pour connaitre le solde
du compte lorsque Stéphanie aura 65 ans :
VF = 10000 x (1/0,1) x (1,130 - 1) = 10000 x 164,49 = 1,645 million d'eurosà 65 ans
Les rentes perpétuelles croissantes
Il s'agit d 'une séquence de flux versés à intervalles réguliers, à I 'infini, et dont le montant
croit à taux constant (c'est la raison pour laquelle on parle aussi de rentes perpétuelles en
progression géométrique). Une rente perpétuelle croissante avec un premier paiement F
et un taux de croissance g peut être représentée par l'échéancier suivant :
2
Fx(l+g)
3
4
Le premier flux se produit à la date 1. Ce n'est qu'à partir de la deuxième période que le
flux commence à augmenter. Le flux de la date n n'a donc augmenté que n — I fois. D'après
la formule générale de la valeur actuelle d'une séquence de flux, la valeur actuelle d'une
rente perpétuelle croissante s'écrit :
v 147 / 1163

Chapitre 4 - La valeur temps de l'argent
Supposons que les flux augmentent à un taux supérieur au taux d'actualisation (g r).
À mesure que n croit, les termes de la somme deviennent de plus en plus grands et la
somme tend vers l'infini. Cela signifie que le prix à payer pour cette rente doit lui-même
étre infini. par conséquent, il ne peut exister de rentes perpétuelles croissantes de ce type
dans la mesure où personne n'est en mesure de payer un prix infini.
Les seules rentes croissantes perpétuelles possibles sont celles pour lesquelles le taux de
croissance des flux est inférieur au taux d'intérêt (g < r), de telle sorte qu'à mesure que
n croit chaque terme de la somme est inférieur au terme précédent ; la somme est alors
finie.
Pour obtenir la formule de la valeur actuelle d'une rente perpétuelle croissante, on
recourt à la méme logique qu'avec des rentes perpétuelles constantes : il suffit de calculer
le montant à placer aujourd'hui pour créer cette séquence de flux. Comme les flux sont
croissants, le montant à retirer doit augmenter chaque année, Cela suppose que le
montant du placement augmente également chaque année. Cela est possible en plaçant
une partie des intérêts gagnés au cours de l'année écoulée.
Un agent souhaite bénéficier d'une rente perpétuelle croissante au taux de 2 % par an
à partir d'un placement de 100 €. Le taux d'intérêt annuel est de 5 96. À la fin de la
première année, il dispose de 105 € sur son compte. Il peut alors retirer 3 € et laisser sur
son compte 102 C, soit 2 % de plus que l'année précédente. À la fin de la deuxième année,
le solde du compte est de 102 x 1,05 = 107,1 €. Il est alors possible de retirer 3 € x 1,02 =
3,06 €, en laissant donc un solde de 107,1 — 3,06 = 104,04 e. Ce faisant, le montant laissé
sur le compte, tout comme le montant qui a été retiré, a augmenté de 2 % (102 x 1,02 =
104,04 C). L'échéancier est le suivant :
115
105 €
-102€
2
-104,04 €
-3G1,02
3
109,24
-106.12€
3,12€
- 3 G (1.02)2
Grâce à cette stratégie, il est donc possible de créer une rente perpétuelle croissante, de
premier flux 3 € et de taux de croissance annuel 2 La valeur actuelle de cette rente
perpétuelle croissante doit étre égale au coût initial, 100 €.
En généralisant, on montre que, pour augmenter chaque année au taux g le montant des
retraits, le solde du compte doit lui aussi augmenter au taux g. En d 'autres termes, au lieu
de réinvestir P la deuxième année, il faut réinvestir P x (l + g) — P + g P. Afin d'accroitre
le principal du montant g P, il faut limiter le retrait à F = r P— g P = Px (r —g).
2
P(r-g)
3
PCI +g/(l + r)
—po sgf(l
PCI (r-g)

116
Partie Il - Temps, argent et taux d'intérêt
D'après l'échéancier, après chaque période, on peut retirer F = p X (r —g) et disposer à
l'infini de flux croissants au taux g. Donc :
La valeur actuelle d'une rente perpétuelle de flux initial F croissant au taux g est égale
à P, le montant initial déposé à la banque. Donc :
Valeur actuelle d'une rente perpétuelle croissante
VA (rente perpétuelle croissante) = F/ (r — g)
(4,11)
Une manière de comprendre intuitivement cette formule consiste à se rappeler qu'avec une
rente perpétuelle constante il faut laisser sur un compte suffisamment d'argent pour que
les intérêts perçus soient égaux aux flux de la rente. Avec une rente perpétuelle croissante,
il faut laisser davantage d'argent sur le compte, car il faut financer la croissance des flux.
Combien faut-il laisser en plus ? Si la banque offre un taux d' intérêt de IO % sur les dépôts
et que l'on désire une croissance des flux (et donc du principal) de 3 % , la différence est de
IO % — 3 % = 7 Ainsi, la valeur actuelle de la rente perpétuelle ne correspond plus au
premier flux divisé par le taux d 'intérêt, mais au premier flux divisé par la différence entre
le taux d 'intérêt et le taux de croissance de la rente.
Se doter d'une rente perpétuelle (bis)
Problème
Dans l'exemple 4.7, le plan de financement du gala des étudiants ne tenait pas
compte des effets de l'inflation. En fait, il est plus prudent de prévoir que le coût du
gala augmente de 4 % par an. Quel doit être alors le montant du placement initial ?
Solution
1
30 ooo€
2
3
30000€*1.04 1.04
Le coût du prochain gala est de 30 000 C. Ce coût augmente de 4 % par an. Afin de
financer, pour toujours, le gala, il faut placer l'équivalent de la valeur actuelle d'une
rente perpétuelle croissante au taux de 4 %, soit (30 000 €) / (0,08—0,04) = 750 000 €
aujourd'hui. Il faut ainsi pratiquement doubler la somme placée au départ.
Les annuités croissantes
Il s'agit d'une séquence de N flux croissants versés à intervalles réguliers. L'échéancier
d'une telle annuité avec un flux initial F croissant au taux g à chaque période jusqu'à la
date N est :

Chapitre 4 - La valeur temps de l'argent
La valeur actuelle d'une annuité qui verse à la fin de chaque période un flux égal à F à la
117
date 1 puis des flux croissants au taux g pendant N périodes est :
Valeur actuelle d'une annuité croissante
1
VA-Fx—
(4.12)
L'annuité ayant un nombre fini de termes, l'équation (4.12) est vérifiée même si g > r'.
La démonstration mathématique pour parvenir à cette expression simple de la valeur
actuelle d'une annuité croissante est la méme que celle utilisée pour les annuités
constantes (annexe en ligne).
Se constituer une épargne-retraite (bis)
Problème
Dans l'exemple 4,9, Stéphanie envisageait d'épargner IO 000 € par an pour sa
retraite. Elle prévoit toutefois une augmentation de salaire de 5 % tous les ans
jusqu'à sa retraite, ce qui lui permettrait d'augmenter son capital. Aussi, décide-t-
elle d'augmenter ses placements chaque année de 5 %. De quelle somme Stéphanie
disposera-t-elle le jour de ses 65 ans, si son épargne est rémunérée au taux de IO % ?
Solution
Le nouveau plan d 'épargne est représenté par I 'échéancier suivant :
35
36
10 000 €
37
2
65
100000 (1.05P
Cet exemple représente une annuité de flux initial IO 000 € croissant au taux de 5 %
par an sur 30 ans. La valeur actuelle de cette annuité est :
VA=10000€x
- 0,05
- 10000 € x 15,0463 - 150 463 € aujourd'hui
La valeur actuelle de l'épargne-retraite de Stéphanie est de 150 463 Elle disposera
à 65 ans de
VF = 150 463 Cx 1,130
= 2,625 millions d'euros dans 30 ans
Stéphanie disposera de 2,625 millions à I 'âge de 65 ans grâce à son épargne-retraite.
Cette somme représente quasiment 1 million d 'euros de plus que si elle n'augmentait
pas ses versements chaque année de 5
7. l.•équation (4-12) nvest pas valable lorsque r g Dans ce cas, le taux d'intérêt et le taux de croissance se
compensent exactement. La valeur actuelle équivaut à recevmir tous les flux aujourd'hui : VA F x N/ ( I r).

118
Partie Il - Temps, argent et taux d'intérêt
La formule de l'annuité croissante est une formule générale à partir de laquelle il est
possible de déduire toutes les formules présentées dans cette partie : une rente perpé-
tuelle croissante peut être vue comme une annuité croissante avec N —è Si g < r, alors
(l + (l + r) < 1. Puisque N (l + g/ 1 + r)'V —+0. La formule d'une annuité crois-
sante quand N —+ est donc :
Il est aussi possible d'obtenir les formules de I 'annuité et de la rente perpétuelle constantes
en posant le taux de croissance g égal à O.
4.6. L'utilisation d'un tableur
Les calculatrices financières ou les tableurs, comme Excel ou Calc (le tableur gratuit et
open-source d'Open Office), disposent de fonctions qui facilitent les calculs financiers.
Le tableau 4.2 liste les principales fonctions relatives aux séquences de flux constants.
Formules Excel relatives aux séquences de flux constants
Variable
Taux dintérêt
Nom bte
de périodes
Valeur actuelle
Valeur future
Notation Fonction Excel
VA
TAUX
NPM
VPM
VA
Utilité
Calcule le taux d'intérêt par période d'une séquence de
flux constants et réguliers
Calcule le nombre de paiements d'une Séquence flux
constants et réguliers avec un taux d'intérêt constant
Calcule le montant du flux périodique d'une séquence
de flux constants avec un taux d'intérêt constant
Calcule la valeur actuelle d'une séquence de nux
constants et réguliers avec un taux cnntérêt constant
Calcule la valeur future d'une séquence de
Constants et réguliers avec un taux d'intérêt constant
Chacune des cinq variables du tableau 4.2 peut etre solution de l'équation de la VAN,
les quatre autres variables étant alors des données (inputs). Autrement dit, sachant la
valeur de quatre des paramètres, ces formules permettent de calculer la valeur de
la cinquième de sorte que la valeur actuelle de la séquence de flux soit nulle. Ces cinq
variables sont solutions de l'équation suivante :
VAN — VA + x
TAUX (1+ TAUX)NPM
vc
(1 + TAUX)NPM
(4.13)
La feuille Excel qui sert à résoudre I 'exemple 4.12 est disponible sur le site compagnon.
Il suffit de saisir quatre variables pour obtenir la valeur de la cinquième. La feuille de
calcul permet aussi de visualiser la séquence de flux (ligne 14) et la formule utilisée
(cellule H6).

Chapitre 4 - La valeur temps de l'argent
Calculer la valeur future avec Excel
Problème
Vous envisagez de placer 20 000 € au taux de 8 96. De quelle somme disposerez-vous
dans 15 ans ?
Solution
L'échéancier est le suivant :
15
PA - -20 000
VPM-O€
La valeur dans 15 ans d'un placement de 20 000 € au taux de 8 % se calcule avec
Excel grâce à la fonction VC : NPM, VPM, VA). Dans notre cas, les para-
mètres sont TAUX 8 NPM = 15, VPM = O, VA -20000. VA est négatif (c'est
le capital que l'on dépose à la banque), alors que VC (la valeur future) est positive
(c'est le capital que l'on peut retirer de la banque). Il est important de respecter les
conventions de signes : un signe positif signifie qu'il s'agit d'une rentrée d'argent, un
signe négatif une sortie d'argent. Excel donne immédiatement la réponse cherchée :
la valeur future est 63 443 €-
w•tr• des N. TAUX. VA F. VF deo zc« ci&ssous. et le
cinquième. Lo soluti•ee' que VAN
de 14.
; VA. F et VF sont Mardis près. change. paur
119
4
12
Sachant
Résoudre VF
VA
Flux
-20 000
-20 000
TAUX
1
0
VA
Formule Excel
63 443
83 443
83 443
On vérifie bien que 20 000 x 1,0815 = 63 443.
Calculer la valeur future avec Excel
Problème
Vous envisagez toujours de placer 20 000 € au taux de 8 mais vous décidez de
retirer 2 000 € à la fin de chaque année. De quelle somme disposerez-vous dans
15 ans ?

120
Partie Il - Temps, argent et taux d'intérêt
Solution
L'échéancier est désormais le suivant :
PA --20 VPM-2000€
2
2000 €
NPM- 15
2000
Les retraits peuvent être vus comme une annuité que l'agent reçoit à partir de son
compte bancaire. VA est négatif (dépot initial à la banque), V PM est positif (retraits
réguliers d'argent de la banque). La valeur future est calculée grâce à la même fonc-
tion que précédemment : NPM, VPM, VA), avec TAUX = 8 NPM = 15,
VPM = 2 000, VA —20 000. D'après Excel, il restera 9 139 € sur le compte après 15 ans.
Sachant
Résouare VF
TAUX
- -20 000
2000
Formule Excel
9139
=vcqoœ 'saxo
Vérifions ce résultat : 20 000 C, rémunérés pendant 15 ans au taux de 8 96, ont une
valeur future de 63 443 € (exemple 4.12). Si on utilise la formule de la valeur future
d'une annuité constante, l'emprunt de 2 000 € par an pendant 15 ans à 8 % a une
valeur future de :
(2 000 €) x (1/0,08) x - 1) = 54 304 €
L'agent dispose donc au bout de 15 ans de 63 443 — 54 304 9 139
4.7. Flux infra-annuels
Dans tous les exemples précédents, les flux se produisent à des intervalles d'un an.
Peut-on utiliser les mêmes méthodes lorsque les flux se produisent à une autre fréquence,
mensuelle par exemple ? Oui, tout ce qui précède reste valable, à condition toutefois
que toutes les données soient exprimées dans la même base. Autrement dit, pour une
fréquence mensuelle par exemple, le taux d 'intérêt doit lui aussi être mensuel, ainsi bien
sûr que le nombre de périodes.
Prenons le cas d'un compte sur livret rémunéré avec un taux d'intérêt mensuel de 2
Un dépôt de 1 000 € rapporte dans six mois : Fx (l + r)" = 1 000 x 1,026 = 1 126,16 e. La
logique est rigoureusement la mème que précédemment.
Jusqu'à présent, I 'objectifa été de calculer la valeur actuelle ou la valeur future d 'une séquence
de flux. Il arrive parfois, cependant, que la valeur actuelle ou future soit connue, mais pas
le taux d'intérêt, le nombre de périodes ou le montant des flux. Par exemple, lorsqu'on
contracte un prêt, on sait combien on désire emprunter, on connait le taux d 'intérêt, mais
pas, a priori, ce que l'on devra payer au total pour honorer le prêt. Autre exemple on peut
se demander combien de temps est nécessaire pour se constituer un certain capital, étant
donné le montant que I 'on est prét à épargner à chaque période et le taux d'intérêt. Dans ces
situations, la val •
allons voir da t
nnues. Nous
oblèmes.
v 153 / 1163 Q Q

Chapitre 4 - La valeur temps de l'argent
Évaluer une annuité avec des nux mensuels
Problème
Vous êtes sur le point d'acheter une nouvelle voiture, et on vous propose deux
options. Vous pouvez payer comptant 20 000 € ou emprunter cette somme contre un
remboursement de 500 € par mois pendant quatre ans. Si le taux d'intérêt mensuel
est de 5 % , quelle est la meilleure option ?
Solution
Il s'agit là d'une annuité constante de 48 termes (4 ans x 12 mois). La valeur actuelle
121
est alors :
VA (annuité de 500 € pendant 48 périodes) = 500 x —
0,05
On peut également utiliser un tableur :
= 21 290€.
1,005"
5
sachant
Résoudre VA
TAUX
48
-21
Formule Excel
40
4.8. Calculer les montants à payer
L'entreprise Alpha envisage d'acheter à crédit une machine d'une valeur de 100 000 €.
Sa banque est d 'accord pour lui accorder ce prêt, mais demande à être remboursée au
moyen de paiements annuels égaux pendant les IO prochaines années. Le taux d'intérêt
est de 8 Si le premier versement a lieu dans un an, quel est le montant du versement
annuel ?
Du point de vue de la banque, I 'échéancier est le suivant :
-100000 €
La banque prete 100 000 € aujourd'hui en échange de IO versements égaux durant la
prochaine décennie, et il faut déterminer le montant F de chaque versement. La valeur
actuelle des flux reçus par la banque doit être égale au montant du prêt consenti, compte
tenu du taux d'intérêt de 8 soit :
100 000 VA (annuité de F par an pendant 10 ans actualisée au taux de 8 %)
D'après la formule de la valeur actuelle d'une annuité :
IOOOOO-Fx—
0,08 1,0810
d'où : F = 100 000/6,71 = 14 903 Les 10 versements annuels s'élèvent donc chacun à
14 903 c.

122
Partie Il - Temps, argent et taux d'intérêt
On peut aussi utiliser un tableur :
Sachant
Résoudre F
10
TAUX
8.00%
100000
.14 903
Formule Excel
ttxxxn.
De manière générale, lorsqu'on désire calculer le montant des remboursements liés à
un prêt, il faut partir du fait que le montant emprunté (le principal) est égal à la valeur
actuelle des remboursements. En inversant la formule de I 'annuité constante, il est alors
possible d'établir le montant des remboursements.
Du point de vue de la banque, l'échéancier d'un prêt d'un montant P, remboursé en
N flux périodiques de montant F avec un taux d'intérêt r, est :
2
La valeur actuelle des versements est égale au montant du principal, donc :
P VA(annuité d'un montant F pendant N périodes) F x — 1 —
L'inconnue de cette équation est E Il faut par conséquent, pour résoudre I 'équation, I 'in-
verser afin d'obtenir le montant des versements à consentir à F en fonction du montant
du pret P, du taux d'intérêt r et du nombre de versements N :
P
(4.14)
Exemple 4.15 — Calculer les flux liés au remboursement d'un prêt
Problème
L'entreprise Biotech désire acquérir une nouvelle machine pour un montant de
500 000 €. Le vendeur exige un paiement comptant de 20 %. Pour le reste, il consent
un prêt sur quatre ans, à échéances mensuelles constantes. Le taux d ' intérêt mensuel
est de 0,5 Quelle somme l'entreprise devra-t-elle débourser tous les mois ?
Solution
Le prêt porte sur 500 000 € — 100 000 € = 400 000 € à rembourser sur 4 x 12 =
48 mois. L'échéancier, du point de vue du vendeur, est :
48
-400 000 €
F

Chapitre 4 - La valeur temps de l'argent
Si l'on utilise l'équation (4.14), le montant F de chaque remboursement est :
123
400 000
= 9 394 €
0,005
Il est aussi possible d'utiliser un tableur :
TAUX
(1,005)
Formule Excel
Sachant 48
Résoudre
O.SO% 00000
L'entreprise doit verser 9 394 € chaque mois pendant quatre ans pour rembourser le
prêt consenti.
La meme idée peut etre utilisée pour définir les remboursements d'un prét dont on
connait la valeur future et non la valeur actuelle. Franck et Claire vont prochainement
avoir un enfant et, par précaution, ils souhaitent épargner dès maintenant pour financer
ses études supérieures. Leur épargne est rémunérée 7 % par an. Combien doivent-ils
placer chaque année afin de disposer de 60 000 € quand l'enfant aura 18 ans ?
L'échéancier est le suivant :
-F
2
—F
18
+60 000 €
On cherche le montant de l'annuité constante dont la valeur future est de 60 000 € dans
18 ans. D'après la formule de la valeur future d'une annuité [équation (4.10)1 :
60000= VF (annuité) = Fx (110,07) x 1) = Fx 34
Donc F = (60 000/ 34) = 1 765 C. Les parents doivent épargner 1 765 € tous les ans pour
disposer de 60 000 € dans 18 ans, si le taux d'interet est de 7 % par an. Avec un tableur :
VA
sachant
18
TAUX
700%
6
.1 705
Formule Excel
007' o
4,9. Calculer le taux de rentabilité interne
Il arrive que la valeur actuelle d'un projet et le montant des flux soient connus, au
contraire du taux d'intérêt qui rend compatibles ces différents termes. Ce taux d'intérêt
est appelé le taux de rentabilité interne, ou TRI (Internal Rate of Return, IRR). Par défi-
nition, le taux de rentabilité interne est le taux d'intérêt qui annule la VAN.

124
Partie Il - Temps, argent et taux d'intérêt
Considérons un projet qui nécessite un investissement immédiat de 1 000 € et qui
rapporte 2 000 € dans six ans. L'échéancier est le suivant :
-1 000 €
2000 €
Quel est le taux d'intérêt r tel que la VAN de ce projet soit nulle ? Pour répondre à
cette question, il faut résoudre l'équation suivante :
2000 — 0
VAN - -1000+
Cela revient à chercher r tel que 1 000 € d'aujourd'hui ont une valeur future de 2 000 €
dans six ans. L'équation se réécrit
1 + (2 000/ 1 000)1/6 = 1,1225
Soit r = 0, 1225. Ce taux d'intérêt est le TRI du projet d'investissement : ce dernier dégage
une rentabilité annuelle de 12,25 % pendant six ans.
Lorsqu'il y a seulement deux flux, comme dans l'exemple précédent, il est simple de
calculer le TRI. Dans le cas général, on investit aujourd 'hui un montant P et on reçoit VF
dans N périodes ; donc : P x (l + TRI)N = VF, ce qui implique :
TRI avec deux flux = (VF/ - 1
(4,15)
Le calcul du TRI impose de partir de la rentabilité totale de l'investissement au bout de
N périodes (VF/ P) et de l'annualiser, en l'élevant à la puissance I / N. Il s'agit, de fait,
d'un calcul de taux annuel effectif (voir le chapitre 5 pour plus de détails).
Qu'en est-il lorsqu'il y a plus de deux flux ? C'est généralement plus compliqué, sauf
lorsqu'il s'agit d'une rente perpétuelle, comme le montre l'exemple 4.16.
Calculer le TRI pour une rente perpétuelle
Problème
Betsy, jeune diplômée, décide de fonder sa propre entreprise. Elle souhaite investir
immédiatement I million d'euros dans un projet qui devrait générer, dès la fin de
l'année prochaine, 100 000 € de bénéfices ; ce montant devrait ensuite croitre de 4 %
chaque année. Quel est le taux de rentabilité interne ?
Solution
Ce projet s'analyse ici comme une rente perpétuelle croissante au taux de 4 96.
L'échéancier est le suivant :
0
-1 000 €
1
100000E
2
1,04

Chapitre 4 - La valeur temps de l'argent
D'après l'équation (4. I l), la valeur actuelle est égale à F/ (r —g). L'équation à résoudre
est donc la suivante : 1 000 000 100 000/ (r- 0,04), soit : 100 000/ 1 000 000 +
0,04 0,14. Le TRI est donc de 14
Plus généralement, si on investit un montant Pen échange d 'une rente perpétuelle de flux
initial F croissante au taux g, alors le TRI s'obtient facilement par la formule suivante :
125
TRI d'une rente perpétuelle croissante = F/ P + g
(4.16)
Considérons un exemple plus complexe. Une entreprise désirant acheter un monte.
charge a le choix entre (a) un achat comptant au prix de 40 000 € ou ( b) quatre versements
annuels de 15 000 e. L'entreprise doit donc comparer le taux de l'emprunt proposé par le
vendeur à celui qu'elle pourrait obtenir d'une banque. Il faut par conséquent calculer
le taux d'intérêt implicite correspondant au crédit proposé par le vendeur, c'est-à-dire le
TRI de ce prêt. L'échéancier du prêt est le suivant :
40 000
-15000 €
2
-15000 €
3
-'5000E
4
-15000 €
Le prét proposé par le vendeur est une annuité comprenant quatre termes constants de
15 000 €. Cette annuité a une valeur actuelle de 40 000 € (car c'est ce que l'acheteur du
monte-charge économise s'il choisit l'achat à crédit). Annuler la VAN des flux revient à
égaliser la valeur actuelle des flux avec le prix d 'achat :
40000-15000x- 1-
La valeur de r solution de cette équation est le TRI, c'est-à-dire ici le taux d'intérêt impli-
cite de l'emprunt, Compte tenu de la forme de l'équation, il n'existe aucune manière
simple de la résoudre. Le seul moyen de déterminer r est de procéder par tâton nements,
en essayant différentes valeurs de r et en se rapprochant peu à peu du résultat.
En prenant comme point de départ r = IO 96, on trouve une valeur de l'annuité de :
15000x— 1
- (1,1)'
—47 548
8.
Avec des flux quer
déterminer r
interpolation
I, ale permettant de
Ableur) ou par
158
/ 1163

126
Partie Il - Temps, argent et taux d'intérêt
La valeur actuelle des versements est trop grande ; le taux d'intérêt doit étre plus élevé,
par exemple r = 20 % :
1
15000x— 1
-38831
(1,2)'
La valeur actuelle des versements est désormais trop faible. Le taux d'intérêt est donc
compris entre IO % et 20 %. Avec un taux de 15 les remboursements sont trop faibles ;
par conséquent, le taux est compris entre 15 % et 20 %. En réduisant progressivement
l'intervalle, on se rapproche de la bonne solution, jusqu'à essayer r = 18,45 % :
15
(M845 -
= 40000
Le taux d'intérêt du crédit proposé par le vendeur du monte-charge est de 18,45
L'entreprise doit comparer ce taux avec celui qu'elle aurait pu obtenir de sa banque, afin
de choisir le crédit le moins coûteux.
Calcul du TRI par interpolation linéaire
Un moyen rapide de calculer le TRI sans procéder à de trop nombreuses itérations
(et sans utiliser un tableur) consiste à procéder par interpolation linéaire, On sait
que le TRI est compris entre % = 10 % (VANI = 7 548) et (VAN2 169).
Or, par application du théorème de Thalès :
r -TRI VAN -O
5--5 - VAN,-VAN2
L'application de cette formule donne :
VANI - V'AN2
(20%-1096)
TRI = 1096+
= 18,65 %
7 548-(-1169)
ce qui est proche du résultat exact (18,45 %). En fait, l'approximation sera d'autant
meilleure que l'intervalle de taux d' intérêt sera petit.
Une autre façon de procéder, lorsqu'il s'agit d'une annuité, consiste à utiliser la méme
feuille Excel que l'on a utilisée jusque-là.
Formule Excel
sachant
Résoudre TAUX
TAUX
4
18.45%
40 000

Chapitre 4 - La valeur temps de l'argent
Calcul du TRI pour une annuité
Problème
Betsy a réussi à convaincre une banque d'investissement de financer le million
d'euros nécessaire au projet en échange de versements égaux à 125 000 € payables à
chaque fin d'année pendant 30 ans. Quel est le taux de rentabilité interne de l'inves-
tissement réalisé par la banque, si le crédit est remboursé comme prévu ?
Solution
L'échéancier du point de vue de la banque est :
127
-1 000000 €
125 000
125 000
30
125 000
L'échéancier est celui d'une annuité de 30 ans. Le TR est le taux qui annule la VAN :
125000
1000000-
Par approximations successives, ou en utilisant un tableur, on converge vers la solu-
tion : le TRI de l'investissement de la banque est de 12,09 06.
c
Formule Excel
sachant
Résoudre TAUX
6
TAUX
12
La fonction TRI
000 125
Il est aussi possible d'utiliser directement la fonction TRI d'Excel qui est de la
forme -TRI(VALEURS, ESTIMATION), avec VALEURS la série des flux et ESTIMATION
le taux utilisé pour la première itération. Par exemple :
I Période
2 FluxFt
TRI
2
3
-1 000
8.9% -TRI 2:E2
La fonction TRI est à utiliser avec prudence ! Les valeurs incluses dans la fonction
doivent inclure tous les flux du projet, le premier se produisant à la date 0 (à la diffé-
rence de la fonction VAN. 2). La fonction TRI ignore également les cellules vides. Par
ailleurs, la séquence de flux doit contenir au moins une valeur négative. Enfin, comme
on le verra au chapitre 7, la fonction TRI admet parfois plusieurs solutions, ou aucune.

128
Partie Il - Temps, argent et taux d'intérêt
4,10. Calculer le nombre de périodes
Il est aussi possible de calculer le nombre de périodes nécessaire pour quun capital initial
atteigne un certain montant compte tenu du taux d 'intérêt et des valeurs actuelle et future.
Daniel place IO 000 € sur un compte rémunéré à 10 % par an et souhaite savoir combien
de temps il doit attendre avant de disposer de 20 000 € :
2
'0.00% -10 000
-IO 000
L'inconnue est N :
VF- 10000€X 1,1N- 20000 €
20 000 €
(4.15)
Il est possible de procéder par tâtonnements successifs, comme pour le TRI : pour N =
7 ans, VF = 19 487 e, ce qui est inférieur à 20 000 €. pour N 8 ans, VF = 21 436 Il
faut donc entre sept et huit ans pour que le placement initial dépasse les 20 000 €. En
fait, environ 7,3 ans (soit un peu moins de sept ans et quatre mois) sont nécessaires. On
peut également trouver la réponse directement. En divisant chaque membre de l'équa-
tion (4.15) par IO 000 on obtient :
20 000/ 10 000 = 2
Pour résoudre cette équation, dans laquelle l'inconnue est à la puissance, il faut utiliser
une des propriétés de la fonction logarithme népérien : = x ln(y). Appliquée à la
formule précédente, cette propriété permet d'obtenir :
N = ln(2)
N 0,6931 /0,0953 - 7,27 ans
En utilisant un tableur, on obtient évidemment la mème solution :
B
C
4
5
6
T Aux
VA
VF
Formule Excel
Sachant
Résoudre N 727
La « règle des 72 ». Combien de temps faut-il pour qu'un capital double, compte tenu du
taux d'intérêt ? Autrement dit, combien d 'années faut-il pour que la valeur future d'un
placement de 1 € au taux d'intérêt r soit égale à 2 € ? On cherche N tel que :
Une approximation d'assez bonne qualité est : N = 72 Ir. Ainsi, avec un taux d'intérêt
de 9 il faut huit périodes pour qu'un capital double (1,098 = 1,99). L'approximation
donne : 72/9 8 ans.
La « règle des 72 » est à la fois simple et précise lorsque le taux d'intérêt est supérieur à
2 % (l'erreur est inférieure à une période).

Chapitre 4 - La valeur temps de l'argent
Nombre de périodes d'un plan d'épargne nécessaires à un achat immobilier
Problème
Julien épargne pour se constituer un apport personnel en vue d'un achat immobi-
lier. Il dispose déjà de IO 050 € et peut épargner 5 000 € à la fin de chaque année.
L'épargne est rémunérée à 7,25 % par an. Combien d 'années doit-il attendre avant
de disposer de 60 000 € ?
Solution
L'échéancier de ce problème est :
129
-10
-5000 €
-5 000
-s 000
+60 000 €
On cherche N tel que la valeur future de la séquence de flux (apport initial compris)
soit égale au montant désiré :
10 050 X 1,0725N + 5 X (1 /0,0725) X (1,0725N- 1) = 60 000
ce qui peut se réécrire :
1,0725N = (60000 X 010725 + 5 000/ 10050 X 0,0725 + 5 000) = 1,632
Grace aux propriétés de la fonction logarithme, il vient :
N 7 ans
Julien devra attendre sept ans avant de disposer de la somme désirée.

Résumé
1. Les trois règles du « voyage dans le temps » sont :
a. Seuls des flux se produisant au mème moment peuvent être comparés ou
combinés.
b. Pour transposer un flux dans le futur, il faut le capitaliser.
c. Pour transposer un flux dans le passé, il faut l'actualiser.
2. La valeur future dans n périodes d'un flux F reçu aujourd'hui est :
3. La valeur actuelle d'un flux F reçu dans n périodes est :
VA = F/ (1 +
4. La valeur actuelle VA d'une séquence de flux est :
(4.2)

130
Partie Il - Temps, argent et taux d'intérêt
VA-S
(4,4)
5. La valeur future VF n d'une séquence de flux à la date n de valeur actuelle VA est :
(4.5)
6. La VAN d'une opportunité d'investissement est égale à la valeur actuelle de ses
bénéfices moins ses coûts : VA (Bénéfices — Coûts).
7. Une rente perpétuelle (perpetuity) est un titre de dette qui prévoit le paiement régu-
lier d'intérêts mais pas le remboursement du capital ; une rente perpétuelle n'a
donc théoriquement aucun terme. Les flux d'une rente perpétuelle peuvent étre
constants ou croissants.
8. Une rente perpétuelle constante paie un flux constant F à chaque période jusqu'à
l'infini. La valeur actuelle d'une rente perpétuelle est :
(4.7)
9. Une annuité est une séquence de N flux égaux se produisant à intervalles réguliers.
L'intervalle de temps séparant deux flux consécutifs est la période ; celle-ci n'est pas
nécessairement égale à une année.
IO. En cas d'annuité constante, le flux F versé à la fin de chaque période pendant
N périodes est le méme.
La valeur actuelle d'une annuité constante est
-9
(1+r)
La valeur future d'une annuité constante à la fin de ladite annuité est :
(4.9)
(4,10)
11. En cas d 'annuité croissante, perpétuelle ou non, les flux croissent au taux constant g
à chaque période.
La valeur actuelle d'une rente perpétuelle croissante est :
La valeur actuelle d'une annuité croissante est :
(4.11)
(4,12)
12. Une séquence de flux mensuels (ou à toute autre fréquence) s'évalue exactement
selon la méme logique, à condition que le taux d'intérêt et le nombre de périodes
soient également exprimés en base mensuelle (ou dans la base correspondante).
13. Le flux de
cipal p s
tes, de prin-
V 163 / 1163

Chapitre 4 - La valeur temps de l'argent
(4.14)
14. Le taux de rentabilité interne (TRI) est le taux d'intérêt qui annule la VAN de l'op-
131
portunité d ' investissement.
Quand il n'y a que deux flux :
TRI avec deux flux = (VF/ - 1
Quand il s'agit d'une rente perpétuelle croissante au taux g :
TRI d'une rente perpétuelle croissante = F/ P + g
(4.15)
(4.16)
