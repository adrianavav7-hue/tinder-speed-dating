# 📊 Speed dating Tinder - analyse des matchs

## 📌 Présentation du projet

Ce projet explore les facteurs qui influencent l’attraction et les décisions prises lors de rencontres rapides (speed dating).

Les données proviennent d’événements de speed dating organisés entre 2002 et 2004. Lors de ces événements, les participants avaient des rendez-vous de quatre minutes avec plusieurs personnes du sexe opposé. Après chaque rencontre, ils indiquaient s’ils souhaitaient revoir leur partenaire et évaluaient différentes caractéristiques.

## 🎯 Objectifs

L’objectif est d’identifier les facteurs associés aux décisions de revoir une personne et à l’obtention d’un match, en étudiant notamment :

- Les différences entre les critères valorisés par les femmes et les hommes.
- Le rôle des origines communes et de la religion.
- Le rôle des motivations des participants.
- L’influence des centres d’intérêt communs.
- L’influence éventuelle de l’ordre des rencontres sur les décisions.

## 📊 Données

Le jeu de données contient 8 378 observations et 195 variables. Chaque ligne représente une rencontre de speed dating. Les variables couvrent les caractéristiques des participants, leurs préférences, leurs évaluations de leurs partenaires et les décisions prises à l’issue des rencontres.

Les variables étudiées sont regroupées en plusieurs catégories :

**Identification et contexte des rencontres** 

iid : identifiant du participant.

pid : identifiant du partenaire rencontré.

gender : genre du participant.

age : âge du participant.

age_of_partner : âge du partenaire.

order : ordre de la rencontre au cours de l’événement.

dec : décision du participants.

match : indique si les deux participants ont mutuellement souhaité se revoir.

**Origine et préférences personnelles**

race : origine ethnique du participant.

samerace : indique si les deux participants ont la même origine ethnique.

imprace : importance accordée au fait que le partenaire ait la même origine ethnique.

imprelig : importance accordée au fait que le partenaire partage la même religion.

**Origine et préférences personnelles

race : origine ethnique du participant.

samerace : indique si les deux participants ont la même origine ethnique.

imprace : importance accordée au fait que le partenaire ait la même origine ethnique.

imprelig : importance accordée au fait que le partenaire partage la même religion.

**Objectifs et situation professionnelle**

field_cd : domaine d’études du participant.

goal : objectif principal de la participation au speed dating.

career_c : domaine professionnel ou carrière envisagée.

**Préférences concernant les qualités d’un partenaire**

attr1_1 : attractivité physique.

sinc1_1 : sincérité.

intel1_1 : intelligence.

fun1_1 : humour et caractère amusant.

amb1_1 : ambition.

shar1_1 : centres d’intérêt communs.

**Centres d’intérêt et activités**

sports : sport.

tvsports : sports à la télévision.

dining : sorties au restaurant.

hiking : randonnée.

tv : télévision, etc.


## 🔎 Analyse exploratoire

L’analyse exploratoire est divisée en deux parties : l’analyse des profils des participants et l’analyse des matchs. La première vise à comprendre les caractéristiques, les motivations et les préférences de la population étudiée. La seconde examine les facteurs associés aux décisions mutuelles de se revoir.

1. Profils des participants 

L’analyse exploratoire est divisée en deux parties : l’analyse des profils des participants et l’analyse des matchs. La première vise à comprendre les caractéristiques, les motivations et les préférences de la population étudiée. La seconde examine les facteurs associés aux décisions mutuelles de se revoir.

**Caractéristiques démographiques**

La population étudiée est principalement composée de jeunes adultes, âgés majoritairement de 23 à 29 ans, avec une concentration autour de 26–27 ans.

Sur le plan ethnique, les participants se déclarant White/Caucasian-American représentent 55,8 % de l’échantillon, ce qui constitue le groupe le plus représenté.

**Domaines d’études et carrières envisagées**

Les domaines d’études présentent des différences selon le genre. Les femmes sont davantage représentées dans plusieurs disciplines liées aux sciences sociales, à la psychologie et aux sciences humaines. Les hommes sont plus présents dans certains domaines scientifiques, techniques et économiques.

Les carrières envisagées suivent également des tendances différentes : la recherche et le milieu universitaire occupent une place importante chez les femmes, tandis que la finance, le conseil et le monde des affaires sont particulièrement représentés chez les hommes.

**Motivations des participants**

Les objectifs les plus fréquemment déclarés sont passer une soirée agréable et rencontrer de nouvelles personnes. Ces deux motivations dominent chez les femmes comme chez les hommes.

**Préférences concernant les qualités d’un partenaire**

Les évaluations montrent que l’importance accordée aux différentes qualités varie selon le genre et la méthode de notation utilisée.

Dans la première méthode, les femmes accordent la moyenne la plus élevée à l’intelligence (21,6), suivie de l’attractivité physique (18,8) et de la sincérité (18,2). Chez les hommes, l’attractivité physique arrive nettement en tête (29,4), devant l’intelligence (19,4) et l’humour (17,5).

Dans la seconde méthode, l’intelligence obtient la moyenne la plus élevée chez les deux genres, avec 18,4 chez les femmes et 19,3 chez les hommes.

**Importance de l’origine ethnique et de la religion**

L’importance moyenne accordée au partage de la même origine ethnique est de 4,12 chez les femmes et de 3,36 chez les hommes. Pour la religion, les moyennes sont respectivement de 4,14 et 3,03.

Sur une échelle de 1 à 10, ces moyennes se situent dans la partie basse à intermédiaire de l’échelle. Dans cet échantillon, l’origine ethnique et la religion ne semblent donc pas constituer, en moyenne, des critères prioritaires dans le choix d’un partenaire. Les femmes leur accordent toutefois une importance déclarée plus élevée que les hommes.

2. Analyse des matchs

**Résultats globaux**

Sur les 551 participants étudiés, 452 ont obtenu au moins un match, soit 82,03 %, tandis que 99 participants (17,97 %) n’en ont obtenu aucun.

**Influence de l’ordre des rendez-vous**

Le taux de décisions positives varie selon l’ordre des rendez-vous, sans suivre de tendance régulière. Il est le plus élevé lors du premier rendez-vous (49,91 %), puis diminue à 39,38 % lors du deuxième.

Ces résultats suggèrent que la décision de revoir un partenaire peut varier au fil des rencontres. Toutefois, les variations observées ne permettent pas de conclure à une tendance générale, notamment lorsque le nombre de rencontres disponibles diminue pour certains rangs.

**Influence des objectifs des participants**

Le taux d’obtention d’au moins un match varie selon l’objectif déclaré. Les participants souhaitant trouver un rendez-vous présentent le taux le plus élevé (90 %), suivis de ceux recherchant une relation sérieuse (86,36 %).

Le test du chi carré met en évidence une association statistiquement significative entre l’objectif déclaré et l’obtention d’au moins un match ((p = 0,0216)). Ce résultat suggère que les motivations des participants sont associées à leurs résultats lors de l’événement.

Cette conclusion doit toutefois être interprétée avec prudence, car certaines catégories regroupent peu de participants.

**Influence de l’appartenance ethnique**

Les résultats descriptifs indiquent que le taux d’obtention d’au moins un match est de 63,52 % lorsque les participants rencontrent une personne d’une origine ethnique différente, contre 55,95 % lorsqu’ils rencontrent une personne de la même origine.

Cependant, le test du chi carré ne met pas en évidence d’association statistiquement significative entre les variables étudiées ((p = 0,2451)). La différence observée dans les taux ne suffit donc pas à conclure à un lien statistique entre l’appartenance ethnique commune et l’obtention d’un match.

**Influence de l’écart d’âge**

Le taux de match diminue progressivement à mesure que l’écart d’âge entre les deux participants augmente :

0 à 2 ans : 18,91 %.

Plus de 2 à 5 ans : 15,94 %.

Plus de 5 à 10 ans : 13,08 %.

Plus de 10 ans : 7,83 %.

Le test du chi carré met en évidence une association statistiquement significative entre la catégorie d’écart d’âge et le résultat de la rencontre ((p < 0,001)).

Ces résultats montrent que les rencontres entre personnes d’âges proches présentent un taux de match plus élevé dans l’échantillon étudié. Ils ne permettent toutefois pas d’affirmer que la proximité d’âge est, à elle seule, la cause de cette différence.

**Conclusion de l’analyse des matchs**

Parmi les facteurs étudiés, l’objectif déclaré des participants et l’écart d’âge entre les partenaires présentent une association statistiquement significative avec les résultats des rencontres.

En revanche, les analyses réalisées ne mettent pas en évidence d’association statistiquement significative entre l’origine ethnique commune et l’obtention d’un match, ni entre la similarité globale des préférences en matière d’activités et le résultat de la rencontre.

Ces conclusions restent limitées aux variables étudiées et à la méthode d’analyse employée. Elles mettent en évidence des associations statistiques, mais ne démontrent pas de relations de cause à effet.

## ⚠️ Limites

- Ancienneté des données : les données proviennent d’événements organisés entre 2002 et 2004. Elles ne reflètent pas nécessairement les pratiques, les préférences et les comportements actuels en matière de rencontres.
- Qualité des réponses : les résultats dépendent de la fiabilité des réponses fournies par les participants.
- Méthodes d’évaluation différentes : certaines préférences sont mesurées selon des échelles ou des méthodes de notation différentes, ce qui peut limiter la comparabilité directe des résultats.
- Données de suivi manquantes : les variables issues du questionnaire envoyé aux participants trois semaines après l’événement présentent plus de 80 % de valeurs manquantes. L’analyse des suites données aux rencontres, notamment la réalisation effective d’un second rendez-vous, est donc fortement limitée.
- Absence de preuve de causalité : les analyses descriptives et les associations statistiques permettent d’identifier des tendances, mais ne suffisent pas à établir des relations de cause à effet.
- Distinction entre match et second rendez-vous : un match correspond à une décision mutuelle de se revoir à l’issue de l’événement. Il ne garantit pas qu’un second rendez-vous ait effectivement eu lieu.
