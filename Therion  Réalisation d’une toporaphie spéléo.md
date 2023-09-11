# Therion : Réalisation d’une toporaphie spéléo

Therion est un logiciel assez complexe demandant une organisation importante de l’espace de travail.

Une séance de relevé topographique est alors contenue dans un dossier avec des sous dossier data et output. Ensuite l’ensemble des relevés peuvent être assembler.

![Therion_dossier_structure](/home/urrutyb/Documents/Spéléo/Topographie/Topographie_md/Therion_dossier_structure.png)

Si on ouvre le dossier **siphon** nous trouvons l’arborescence suivante : 

![zoom_siphon](/home/urrutyb/Documents/Spéléo/Topographie/Topographie_md/zoom_siphon.png)

Les fichiers *.th correspondent aux données assemblés (map, scrap,th2,th).

Le fichier **thconfig** défini la configuration permettant de réaliser la topographie de la cavité et de définir les outputs désirés. Le fichier **log** contient le rapport du calcul effectué.

Dans le **siphon/data**, nous avons :

- *.th $\rightarrow$ Fichier contenant les mesures
- *.th2 $\rightarrow$ Fichier de dessin vectoriel de therion
- *.xvi $\rightarrow$ fichier représentant le squelette des visées

Dans le **siphon/output**, nous avons toute les sorties définies dans le fichier **thconfig**

Afin de réaliser l’arborescence présentée ci-dessous, des scripts ont été créé par Benoît Urruty : https://github.com/BenoitURRUTY/Script_Therion

### Importation des données dans Therion

On importe le ficher *.th exporté de TopoDroid et réoganiser le header (nom des topographes, localisation). Vérifier que les “extend” sont défini pour chaque visée.

```
# 2022.11.15 created by TopoDroid v 5.1.40

survey puits_des_3_morts -title "Puits des 3 cadavres"
  centerline
    date 2022.11.14 #date de la survey
    cs UTM32 #définition de la projection des coordonnées de l'entrée
    fix 2 245809 5023824 1696 # coordonnées de l'entrée
    team "Benoît/Urruty (GUCEM)" #équipe de topographe
    team "Fabien/Simon (GUCEM)"  # une ligne par équipier
    team "Fabien/Mullet (GUCEM)"
    units length meters
    units compass clino degrees
    data normal from to length compass clino
    # extend auto
    0 . 3.41 88.1 -5.7
    0 . 1.99 118.7 -2.4
    0 . 1.71 181.0 -0.0
    0 . 4.31 225.7 -5.1
    0 . 3.55 262.1 -0.4
    0 . 1.32 319.0 0.0
    0 . 1.31 277.8 -80.6
    0 . 5.71 236.8 -34.8
    0 . 4.23 104.1 -48.6
    0 . 4.38 251.9 -30.6
    extend left
    0 1 12.91 111.0 80.9
    # extend auto
    1 . 2.98 318.0 -3.6
    1 . 3.94 281.1 -6.4
    1 . 5.04 257.8 -7.9
    1 . 1.11 248.4 -1.3
    1 . 0.47 224.6 1.3
    extend right
    1 2 7.05 359.6 86.8
    2 3 4.97 69.9 33.6
    # extend auto
    2 . 0.99 80.4 2.6
    2 . 2.03 109.6 1.8
    2 . 2.37 127.8 -4.9
    2 . 0.94 207.7 -5.8
    2 . 1.39 184.9 -4.0
  endcenterline
endsurvey
```



 ### Premier compilation

On peut alors réaliser une premier compilation pour cela ouvrir le ‘thconfig’ avec therion ou bien lancer la commande `therion thconfig`.

Cette première compilation va créer des output avec le squelette ainsi que les fichiers xvi qui vont servir de support au dessin. Plein d’outputs différents sont possible svg, pdf, shapefile, 3D, ….

Attention à l’échelle des XVI si on exporte un dessin depuis topodroid X. Les deux échelles (celle de compilation du XVI et celle d’export du dessin en th2) doivent correspondre.

## Dessin sur ordinateur : Therion

