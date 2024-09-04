
Lors de la création d'une MAP, il faut avoir au minimum les calque de Tuiles **`Back`**, **`Buildings`** et **`Front`**.




- Chaque couche se compose de nombreuses tuiles, qui sont des carrés de 16 × 16 pixels placés dans une grille pour former la carte visible.
- Chaque tuile peut avoir des propriétés ( par exemple, praticable/bloqué), une **logique spéciale** ( par exemple, une action à effectuer lorsque le joueur marche dessus) et une image à afficher.
- L'image est représentée par un index de sprite (ou index de tuile), qui est sa position dans une feuille de sprite associée. 2 tuiles avec un image différentes peuvent donc avoir le même index car elle font partie de 2 feuille de sprite différente.



Jeux de tuiles et feuilles de tuiles

Feuilles de tuiles sont les .png fichiers utilisés comme images sources. Les feuilles de tuiles n'ont aucune animation, propriétés, terrains ou quoi que ce soit d'autre que des pixels qui leur sont associés : ce ne sont que des images. Ensembles de tuiles sont des fichiers XML de Tiled qui contiennent toutes les informations sur la façon dont la carte utilise l'image source. Leurs noms prêtent à confusion et sont souvent utilisés de manière interchangeable. 



[La création d'un mod SMAPI nécessite de la programmation, mais c'est beaucoup plus puissant et plusieurs mods SMAPI peuvent éditer la même carte.](https://stardewvalleywiki.com/Modding:Maps#Using_SMAPI)


Une fois une carte modifier, créer un mod Content Patcher ou SMAPI pour charger votre carte.