# ProjetIAS

Projet réalisé dans le cadre du cours d'Introduction à l'Apprentissage Statistique.

#Objectif
L'objectif de ce projet est d'étudier un jeu de donnée contenant les statistiques à 10 minutes de 10 000 parties classées du jeu League of Legends.  
Le but est de faire re-sortir une stratégie permettant de maximiser ses chances de victoire, et des caractéristiques permettant de déterminer à l'avance l'issue d'une victoire.  
En outre cette analyse nous permettra de mesurer l'importance des 10 premières minutes dans l'issues d'une partie

#League of Legends
League of Legends est un jeu compétitif d'arène en 5 contre 5. L'objectif pour chaque équipe est de détruire le nexus adverse, lui-même protégé par des tourelles.  
Afin de détruire les tourelles, puis le nexus, les joueurs incarnent chacun un champion unique.  
Lors de la partie les joueurs peuvent tuer (temporairement) les autres joueurs, ou encore des sbires apparaissant à intervalle régulier, afin de gagner de l'or et de l'expérience.  
L'or et l'expérience permettent au joueur d'améliorer leur statistiques afin de devenir plus fort.
En outre d'autre objectifs optionnels, mais offrant des bonus à l'équipe qui les récupère, apparaissent régulièrement sur la carte.

#Jeu de donnée
Notre jeu de donnée est composée de 10 000 parties classées, jouées au niveau diamant et plus (top 1% des joueurs). Il contient des statistiques sur chacune des équipes à 10 minutes de jeu. En particulier :
-Les objectifs pris par chaque équipe
-Le nombre d'élimination/de mort
-La quantité d'or, d'expérience, de sbires
-L'équipe gagnante
