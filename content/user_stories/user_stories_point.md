+++
title = "Pourquoi des USPoints"
weight = 40
+++

{{% notice style="tip" title="Ressources" icon="book" %}}
- [CURSE Your Way To Better Scrum Story Pointing](http://www.artemisagile.com/curse-your-way-to-better-scrum-story-points/)
- [Don’t Equate Story Points to Hours](https://www.mountaingoatsoftware.com/blog/dont-equate-story-points-to-hours)
{{% /notice %}}

Quelque chose de notable est la séparation entre :
- la taille d'une fonctionnalité (représentant l'effort futur pour la mettre en œuvre) 
- et l'attribution de la tâche à une personne (décision de l'équipe pendant le sprint).

Sachant que généralement ces deux activités ne sont pas effectuée en même temps. La définition de la taille d'une fonctionnalité va pouvoir se faire durant un Release Planning tandis que l'affectation ne se fera qu'au "Just-in-Time" durant l'Itération Planning (I.g. Spring Planning).

## Les heures sont propres à chacun

Estimer ainsi en nombreux d'heure (*Ideal Days*) au tout début n'est pas dès plus envisageable. Une personne nouvelle pourra estimer à 5 jours tandis que l'expert pourra seulement dire 2 jours. 

Puis, pour déterminer le nombre de fonctionnalités qu'une équipe peut livrer au cours d'un sprint, l'équipe mesure sa vélocité et la vélocité moyenne des différents sprints est appelée vélocité durable. Ainsi si la vélocité est de 40 l'objectif est de trouver des User Stories liées au Sprint Goal qui cumulée avoisine 40 USP.
- développeur 1 en 40h réalise 20 USP -> 1 USP = 2 heures
- développeur 2 en 40h réalise 5 USP -> 1 USP = 8 heures

Et ensemble ils produisent 25 USP en 80h, soit 1 point en un peu plus de 3h. On pourrait donc se dire que notre nouvelle référence est de 3h. Mais il sera très difficile lors les Poker Planning d'arriver à mettre d'accord les deux développeurs sur l'estimation d'une nouvelle US tellement la différence de travail accomplit en 3h est différente pour les deux.

En réalisant à la place une estimation sur en USP, on se concentre plus sur l'effort à fournir pour réaliser l'US quelque soit le développeur qui la réalise. Nous regardons l'équipe dans son global et pas chaque membre individuellement.

## Estimer est difficile
Si je vous demande l'age de quelqu'un dans la rue vous aurez du mal à me donner son age précis. Néanmoins vous pouvez plus facilement le comparer avec l'age de quelqu'un d'autres.
Il est 2x plus vieux, ou 3x plus vieux sans donner d'age précis.

Les estimations en USP vont dans ce sans, l'humain n'est pas très fort pour estimer précisément la durée qu'il va mettre. Néanmoins, il est capable de donner un taille relative à une US par rapport à une autre US (comme pour l'âge).

## Conversion en temps
Et oui, nous devons bien à un moment répondre à la question "Quand cela sera-t-il fini ?". Cette question amène donc de la durée et du temps.
Pour passer de notre estimation en USP (e.g. 250 USP) en durée nous utilisons la vélocité. Si l'équipe à une vélocité moyenne de 25 alors nous pouvons envisager de livrer la fonctionnalité dans 10 itération.

**La durée d'un projet n'est pas estimée mais dérivée du nombre total d'USP en le divisant par la vélocité de l'équipe.**

PS : si vous prenez les 3h evoquées précédement vous allez retomber sur 10 :
- 250 USP * 3USP/h = 750h
- 750h / 80h (2x40h) = +-10

MAIS ceci n'est possible que théorique, car nous transformons des nombres. Aurions-nous était capable au début de prédire 750h (sans passer par les USP). Ceci aurait forcément était plus compliqué. En passant par les USP nous simplifions le process d'estimation en le rendant abstrait => on se concentrera plus sur la discussion autour que la valeur de l'estimation.