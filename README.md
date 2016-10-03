#PFE : Cahier des charges


##Principe
###Contexte, cible
Vivre dans une famille nombreuse, en colocation ou encore en couple n'est pas toujours une mince affaire. Il faut pouvoir. Il est parfois difficle de s'oragniser lorsque l’on doit prendre d’autres personnes d’un groupe en compte. L’application permettra donc de gérer une partie de l’organisation au sein d’un groupe cohabitant. Les publics cibles sont donc les familles, les couples ou encore les colocataires. 

###Principe
Un compte sera créé pour chaque famille, et chaque membres de la famille aura accès à ce compte. 

##Fonctionnalités
###Impératives
- Liste de courses dans laquelle chaque utilisateur pourra y ajouter les aliments dont il a besoin. Une fois qu'un des utilisateurs aura acheté un des éléments de la liste de courses, l'ingrédient se supprimera de la liste de courses et les autres utilisateurs seront notifiés.
- Planning commun dans lequel chaque utilisateur ajoutera ses activités. Cela permettra de s’organiser au niveau des trajets en assigant un conducteur pour chaque évènement. L'utilisateur recevra une notifications x temps avant un évènement qu'il a entré dans le calendrier.
- Liste de tâches à faire par semaine avec un système de case à cocher une fois que celles-ci sont faites.
- Chat pour permettre aux utilisateurs de discuter à propos des infos ( les courses, trajets à prévoir pour un évènement ).

###Complémentaires
- Répertoire téléphonique utiles à tous, avec les numéros du médecin, de la commune, du propriétaire ( le genre de renseignements que l’on cherche 10 fois par an... ).

##Aspect technologie
Intégration du code: HTML5, CSS3, SASS, GULP
J'utiliserai node pour pouvoir synchroniser en temps réel. Les données devront toujours être synchronisée en temps réel particulièrement pour le calendrier et la liste de courses qui devront absolument rester à jour mais aussi pour le chat. 