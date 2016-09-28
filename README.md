#PFE : Cahier des charges


##Principe
###Contexte, cible
Les publics cibles sont les familles, les couples ou encore les colocataires. Il est parfois difficle de s'oragniser lorsque l’on doit prendre d’autres personnes d’un groupe en compte. L’application permettra donc de gérer l’organisation au sein d’un groupe cohabitant. 

###Principe
Un compte sera créé pour chaque famille, et chaque membres de la famille aura accès à ce compte. 

##Fonctionnalités
###Impératives
- Liste de courses dans laquelle chaque utilisateur pourra y ajouter les aliments dont il a besoin. 
- Planning commun dans lequel chaque utilisateur ajoutera ses activités. Cela permettra de s’organiser au niveau des trajets par exemple.
- Liste de tâches à faire par semaine avec un système de case à cocher une fois que celles-ci sont faites.

###Complémentaires
- Répertoire téléphonique utiles à tous, avec les numéros du médecin, de la commune, du propriétaire ( le genre de renseignements que l’on cherche 10 fois par an... ).

##Aspect technologie
Intégration du code: HTML5, CSS3, SASS, GULP
J'utiliserai node pour pouvoir synchroniser en temps réel. Les données devront toujours être synchronisée en temps réel particulièrement pour le calendrier et la liste de courses qui devront absolument rester à jour. 