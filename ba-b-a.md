# Le b.a.-ba

Dans le cadre des CaenCamp.s, les projets vont très largement consister en la mise en place de projets informatiques liés à l'animation du collectif des développeurs de Caen. Nous allons travailler à plusieurs et donc partager du code. Et pour cela, nous allons partager ce que l'on nomme une base de code versionnée. L'outil de base pour faire cela, c'est un [logiciel de gestion de version](https://fr.wikipedia.org/wiki/Logiciel_de_gestion_de_versions) que l'on appel Git *(1)*. Et très souvent, la première rencontre que l'on fait avec une base de code versionnée sous Git, c'est Github *(2)*. La preuve, vous êtes ici !

*1: en vrai, il existe beaucoup d'autre solutions, mais dans la cadre des CaenCamp.s nous utilisons Git.*    
*2: tout comme il existe d'autre solutions que Git, il existe d'autre sites permettant de travailler sur une base versionnée de code, comme [GitLab](https://gitlab.com) ou [Bitbucket](https://bitbucket.org
). Mais pour le moment, nous utilisons Github.*

## Github

Voyons ce que dit [wikipedia](https://fr.wikipedia.org/wiki/GitHub)

> GitHub est centré vers l'aspect social du développement. En plus d'offrir l'hébergement de projets avec Git, le site offre de nombreuses fonctionnalités habituellement retrouvées sur les réseaux sociaux comme les flux, la possibilité de suivre des personnes ou des projets ainsi que des graphes de réseaux pour les dépôts (en anglais repository). GitHub offre aussi la possibilité de créer un wiki et une page web pour chaque dépôt. Le site offre aussi un logiciel de suivi de problèmes (de l'anglais issue tracking system). GitHub propose aussi l'intégration d'un grand nombre de services externes, tels que l'intégration continue, la gestion de versions, badges, chat basés sur les projets, etc.

Github nous permet principalement :

* de découvrir un projet. Le fichier [readme](#) est d'une grande importance pour cela,
* de remonter un problème en créant des [issues](https://guides.github.com/features/issues/). Classiquement, une issue concerne un bug observé sur le projet. Mais cela peut-être aussi une fonctionnalité manquante, une ergonomie contestable ... Bref, on fait une issue quand on a remarqué un problème ou que l'on a pensé à une amélioration à apporter à l'existant.
* de proposer une modification de la base de code via ce que l'on appel une **Pull Request** (nous y reviendrons plus loin).

## Git

Si créer une issue ne demande pas à intervenir sur la base de code, proposer une Pull Request si !

**Et pour cela, vous devrez apprendre à utiliser Git.** 

C'est un très vaste sujet. Certains vous conseillerons d'utiliser des logiciels graphiques comme [Github Desktop](https://desktop.github.com/), d'autres ne jurent que par la console. Mais quoi qu'il en soit, vous ne maîtriserez pas Git en un jour ! Mais ne vous découragez pas, c'est un outil très utile à connaître, et vous n'aurez pas besoin d'être un expert pour faire vos premières pull-requests.

Ce guide n'a pas vocation à être un tutoriel Git, mais il existe beaucoup de bonnes ressources sur le sujet. En voici une petite liste :

* [Git - Petit Guide (fr)](https://rogerdudler.github.io/git-guide/index.fr.html)
* [Le guide Github (en)](https://guides.github.com/introduction/git-handbook/)
* [Git from Beginner to Advanced (en)](https://www.madebymike.com.au/writing/how-to-git/)

### Git aux CaenCamp.s

Preuve que Git est un sujet important, nous en avons déjà beaucoup parlé aux CaenCamp.s !

* [Versionning avec Git, par Mathieu Sadouni (09/10/2012)](https://www.caen.camp/talks/edition-5-versioning-avec-git)

* [Git pratique, par Mathieu Sadouni (06/12/2012)](https://www.caen.camp/talks/edition-7-git-pratique)

* [Git, comprendre les submodules, par Sylvain Zyssman (15/02/2013)](https://www.caen.camp/talks/edition-9-git-comprendre-les-submodules)

* [Devenir un git master, par Antoine Lelaisant (27/06/2017)](https://www.caen.camp/talks/edition-5-versioning-avec-git)

## Proposer une Pull Request (PR)

Vous vous sentez plus à l'aise avec Git ? Faire une nouvelle branche, ajouter du code à l'index, faire un commit ne vous font plus peur ? Vous savez cloner un projet et ouvrir une branche de suivie distante ? Vous êtes donc prêt pour faire votre première Pull Request !

Mais avant cela, plusieurs options sont à considérer. Tout d'abord, si vous venez régulièrement aux Coding CaenCamp.s, il y a de fortes chances pour que vous fassiez partie de [l'équipe ccc Github](https://github.com/orgs/CaenCamp/teams/codingcaencamp). Dans ce cas, vous pouvez donc créer une branche de travail sur le dépôt des CaenCamp.s et proposer directement une PR.    
Si vous ne faite pas partie de l'équipe, ou si vous préférez travailler sur votre propre code base, il est bien sûre tout à fait possible de partir d'un **[fork](https://guides.github.com/activities/forking/)** du projet. Le [workflow](https://blog.scottlowe.org/2015/01/27/using-fork-branch-git-workflow/) sera très proche !

Mais d'ailleurs, de quel workflow parle-t-on ? Il existe en effet beaucoup de théories et de tenants de la bonne manière de gérer les branches de développement. Par exemple, un workflow assez répandu est le [GitFlow Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow). Mais souvent, ces workflows répondent à des problématiques de grosses équipes et de gros projets.

Ce ne sera pas le cas sur les projets des CCC, et l'on ne peut que conseiller un workflow simple du type [Github Flow](https://guides.github.com/introduction/flow/), c'est à dire une branch master sur laquelle on va merger les PR de features.

![Github Flow](images/githubflow.jpg)

## Je me sens plus à l'aise avec Git. Je fais quoi maintenant

Vous vous sentez prêt à proposer des pull requests sur les projets des CaenCamp.s ? Ou d'ailleurs ? Génial.
Si vous voulez commencer *doucement*, et bien n'hésitez pas à proposer des améliorations à ce présent dépôt ! 

En effet, si vous êtes arrivés jusqu'ici, vous avez sûrement repéré des fautes de frappes, des fautes d'orthographe ? Ou alors, vous avez trouvé des guides plus pertinents que ceux cités en exemple ? Parfait, faites des PR pour rendre ce guide meilleur et faciliter l'arrivée de nouveaux participants ! 

L'une des première contribution, et l'une des plus appréciée sur les projet open-source concerne la documentation ! Alors allez-y, la communauté vous le rendra ;)
