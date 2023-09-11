# Prise de mesure topographique

## Étapes pour topographier

- Lever la topographie sous terre
- De retour à la maison :
	- Si la topographie a été faite à l’ancienne, à la main, reprendre le carnet topographique et recopier sur une feuille propre l’intégralité du carnet. Une fois le carnet mis au propre, faire une double vérification pour trouver les erreurs de recopie.
	- Si la topographie a été faite avec un disto X2 couplé à une tablette/téléphone, transférer les données et le dessin sur un ordinateur, et en faire une copie sur un second support (clef USB, disque dur externe, NAS, Serveur dans le Cloud…)
- Si besoin, formater les données pour le logiciel de topographie
- Exporter le squelette topographique pour le vérifier avant dessin

- Dessiner soit directement sur l’ordinateur, soit sur papier (à scanner). Si sous terre, le dessin a été pris sur un carnet quadrillé, à l’échelle, alors, le scanner et travailler directement dessus (facile avec Therion)

- Diffusion de la topographie
- Écriture de la fiche descriptive

## Lever la topographie sous terre

### Outils

Décamètre ou télémètre laser

Bousolle

Inclinomètre

Carnet

Crayon

### Prise d’une mesure et tenue du carnet

| Départ | Arrivée | Distance (m) | Direction (°) | Pente(°) | Gauche (m) | Droite (m) | Haut (m) | Bas (m) | Commentaire            |
| ------ | ------- | ------------ | ------------- | -------- | ---------- | ---------- | -------- | ------- | ---------------------- |
| 1      | 1       | 0            | 0             | 0        | 2          | 3          | 6        | 8       | Start                  |
| 1      | 2       | 20           | 25            | -50      | 2          | 4          | 6        | 1       | Entrée au bas du puits |
| 2      | 3       | 15           | 34            | 0        | 3          | 5          | 6        | 1       |                        |
| 3      | 4       | 5            | 30            | 20       | 3          | 4          | 1        | 4       |                        |
|        |         |              |               |          |            |            |          |         |                        |
|        |         |              |               |          |            |            |          |         |                        |

La prise de mesure se fait depuis un point référencé par GPS (entrée de la cavité) ou depuis un ancien point topographique identifié.

#### Visée

Chaque mesure peut être fait de manière direct (de 1 vers 2) ou inverse (de 2 vers 1). Il est important d’indiquer la méthode utiliser

##### Perturbation de la boussole

La boussole peut être perturbé par beaucoup de d’éléments que nous pouvons avoir sur nous lors de la topographie. Il est impératif de limiter ces perturbations voir de les supprimer.

- Lampe avec aimant, ex : armytek
- casque avec aimant, ex : Meteor, Sirocco
- Aimant sur clé de 13
- Batterie de lampe
- Téléphone portable

#### Habillage

Entre chaque point, nous devons nous repérer dans les 3 dimensions et donc mesurer la distance, la direction par au nord et la pente.

Les mesures Gauche, Droite, Haut et Bas permettent de mesurer le volume de la galerie de manière simple.  Avec le logiciel Therion, la mesure haut et bas se fait dans un plan perpendiculaire à la visée de +/- 90 à 68 ° et perpenticulaire au plan horizontal dans les autres cas.

La mesure du premier point d’une serie se fait sans déplacement. Juste une mesure de volume (cf tableau)

Exemple issu de https://www.groupe-speleo-vulcain.com/explorations/techniques-topographiques/comment-lever-une-topographie-sous-terre/comment-lever-une-topographie/ : 

![img](https://www.groupe-speleo-vulcain.com/wp-content/uploads/2020/05/Data-carnet-1430x1024.png)

Dans l’exemple ci-dessus, vous pouvez remarquer qu’il n’y a pas l’indication du point de départ. C’est possible de le rajouter, mais s’il est indiqué à chaque visée, nous perdons du temps lors de la prise de note, et la lecture du tableau est rendue plus difficile : nous ne voyons pas du premier coup d’œil où sont les départs et les bouclages.

C’est pourquoi, il est intéressant de ne noter que la station d’arrivée à chaque visée qui part de la précédente visée. Dans un cas plus complexe :

- Si nous partons d’une station qui n’est pas la précédente visée, alors, il suffit d’écrire la station de départ et la station d’arrivée dans cette colonne, et d’indiquer une petite flèche entre le départ et l’arrivée.
- Si nous faisons un bouclage sur une autre stations, alors, il suffit de relier les deux noms de stations dans cette colonne par un =
- S’il y a un croisement, pour le retrouver facilement dans les notes topographiques, il suffit d’y adjoindre une étoile, par exemple.

Ainsi, par exemple, si pour une visée, dans la colonne « point de d’arrivée », nous lisons :

- 25 : alors, la ligne correspond à la visée de la station 24 (précédente) vers la station 25.
- 12 –> 25 : alors, la ligne correspond à la visée de la station 12 vers la station 25
- 14 = 25 : alors, nous avons bouclé la station 25 sur la station 14
- *25 : alors, la ligne correspond à la visée de la station 24 (précédente) vers la station 25, mais au niveau de la station 25, il y a un départ à topographier plus tard.

En conséquence, d’un seul coup d’oeil, nous pouvons repérer les départs, les différentes séries de données, et les bouclages.

#### Utilisation du Disto X2 et d'une application sur smartphone

L’application TopoDroid permet de recevoir des mesures directement d’un télémètre laser équipé du Bluetooth (tel qu’un Disto X2). 

Avant de réaliser un relevé topographique , il est nécessaire de calibrer le dispositif de mesure. Cette calibration doit être réalisé loin de toute source magnétique active ou passive. Le mieux au milieu de la forêt sans rien de métallique proche.

Ensuite, nous pouvons commencé le relevé. 3 mesures identiques = 1 visée (Paramètre par défaut). Tout les mesures uniques correspondent à de l’habillage. 

Dans TopoDroid, les paramètres part défaut définissent une mesure de + de 50 m comme une erreur. Cela peut être modifié.

Pendant le relevé, il est possible de dessiner sur le téléphone. 

A la fin du relevé, il est alors possible de télécharger les données formater pour le logiciel de traitement utilisé. 

### Point topo

De manière régulière il est bon de marqué à l’aide de vernis à ongle ou d’un scotch avec un numéro, la position des points topographiques importants. Cela servira dans le cas de la reprise d’une section de la topographie cela permet de simplifié la tâche. 

Il est possible de marquer les points topographique

### Dessin

La prise de ces mesures doit être accompagné d’un dessin de la topographie sur la page opposé du carnet. Il doit être à la fois en coupe et en plan.

Avec les mesures d’habillages au Disto X2, le dessin n’est plus aussi utile mais permet de mieux se souvenir où était placé les points topographiques.

