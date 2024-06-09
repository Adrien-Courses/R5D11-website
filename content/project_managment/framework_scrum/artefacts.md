+++
title="Artefacs Scrum"
weight=60
+++

Les artefacts scrum représentent le travail ou une valeur. Ils sont conçus pour maximiser la
transparence des informations clés. Ils matérialisent :
- l’avancement du travail
- l’atteinte des objectifs
- progression de l’équipe

![Artefacts Scrum](../images/scrum_artefacts.png)

Ils sont au nombre de 3 : *Product Backlog*, *Sprint Backlog* et *Incrément*

## Product Backlog
{{% notice style="warning" title="Definition" icon="pen" %}}
Liste ordonnée des caractéristiques que les parties prenantes du produit pensent qu’il est
nécessaire de réaliser.
{{% /notice %}}
Le Product Backlog est une **liste ordonnée** et **émergente** de d’user-stories qui contiennent
une brève description de quelle est l’exigence, qui en a besoin et pourquoi elle est nécessaire.

Il consiste à un **plan provisoire à un instant t pour atteindre le Product Goal**.
Le Product Backlog n’est jamais fini. Au commencement, nous y positionnons les fonctionnalités requises connues puis évolue au fil du développement du produit.

Le Product Backlog n’est pas définitif, il évolue tout au long du processus de création. L’équipe
va découvrir de nouveaux éléments à ajouter (émergent).

{{% notice style="note" title="Affirmation" icon="check" %}}
L’engagement de l’équipe n’est pas sur le Product Backlog mais sur le Product Goal.
{{% /notice %}}

### Product Backlog géré par le Product Owner
Le Product Backlog est maintenu par le Product Owner. Néanmoins, les développeurs peuvent
suggérer d’ajouter des choses et se concertent avec le PO.
Il faut éviter que le PO est créé le Product Backlog dans son coin avec un ensemble de tâches
à faire

### Un Product Backlog évasif et précis
Le Product Backlog vise à atteindre le Product Goal. Ainsi lorsqu’un élément est ajouté au PB
il est assez évasif, lorsqu’on va vouloir réellement mettre en œuvre cet item nous allons procéder à un raffinage afin de le rendre plus précis pour l’équipe de développement.
Le Product Backlog change/évolue afin d’en l’unique but d’atteindre le Product Goal. En fonction du Product Goal on ordonne le Product Backlog

### Un Product Backlog n’a pas un temps défini
Des exigences sont ajoutées Product Backlog tant que nous n’avons pas atteint ou abandonné
le Product Goal

### Definition of Ready
{{% notice style="warning" title="Definition" icon="pen" %}}
Liste d’éléments attendus qu’une user story doit rassembler pour être candidate au développement.
{{% /notice %}}

Étant donné que les exigences ne sont définies que de manière vague, elles doivent être
affinées et clairement définies avant d’être intégrées dans le sprint.

## Sprint Backlog
{{% notice style="warning" title="Definition" icon="pen" %}}
Décris ce que les membres de l’équipe doivent développer au cours d’un sprint
{{% /notice %}}
Le Sprint Backlog est créé pendant le Sprint Planning. Il représente le plan de l’équipe pour
atteindre le Sprint Goal.
1. L’équipe Scrum collabore pour définir un Sprint Goal.
2. Les développeurs (influencé par le PO) choisissent les éléments du Product Backlog pour
atteindre le Sprint Goal

Le Sprint Backlog est composé du :
- Pourquoi : Sprint Goal
- Quoi : éléments du Product Backlog
- Comment : plan d’action pour réaliser l’Incrément
  - Ordre / Priorité
  - Détails des tâches techniques

### Construction du Sprint Backlog
{{% notice style="note" title="Affirmation" icon="check" %}}
Dans le Product Backlog on liste les fonctionnalités, alors que dans le Sprint Backlog on
liste les activités correspondant aux fonctionnalités à implémenter durant le sprint.
{{% /notice %}}
Le Sprint Backlog est la décomposition des user-stories en une unité de taille adéquate pour
pouvoir suivre le progrès et identifier les risques et les problèmes.

Le Sprint Backlog est donc amené à évoluer chaque jour (lors du daily) en fonction de ce que
nous apprenons.

Il s’agit donc d’un élément de communication visuel entre les membres de l’équipe. L’équipe
à son plan de route et elle le fera évoluer chaque jour.

### L’engagement de l’équipe
{{% notice style="note" title="Affirmation" icon="check" %}}
L’engagement de l’équipe n’est pas sur le Sprint Backlog mais sur le Sprint Goal
{{% /notice %}}
L’équipe ne s’engage pas à finir l’ensemble des user-stories lors du Sprint mais de finir à
minima le Sprint Goal.

## Incrément
{{% notice style="warning" title="Definition" icon="pen" %}}
La version du produit livré aux parties prenantes après chaque sprint. Finit et testé.
{{% /notice %}}

{{% notice style="note" title="Affirmation" icon="check" %}}
Le travail réalisé devient un incrément uniquement s’il satisfait la Definition of Done
{{% /notice %}}
L’incrément représente une étape vers le Product Goal. Chaque incrément doit apporter de la
valeur au produit et ils doivent fonctionner ensemble.

C’est le résultat visible de toutes les décisions et priorisations prises par le Product Owner et
l’équipe.

## Product Backlog VS Spring Backlog
Le Product Backlog enregistre les exigences du point de vue du client. Il s’agit de la liste des
fonctionnalités ou user stories que le client souhaite obtenir, classées selon la priorité qu’il
accorde à chacune d’elles.

Le Sprint Backlog reflète les exigences du point de vue de l’équipe de développement. Il s’agit
d’une liste de tâches dans laquelle les user-stories qui doivent être réalisées au cours du sprint
sont décomposées.