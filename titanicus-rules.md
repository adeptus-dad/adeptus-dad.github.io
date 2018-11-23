---
layout: page
title: Titanicus Rules
permalink: /titanicus-rules/
feature-img: "assets/img/titanicusBoxDusty.jpg"
---

* TOC
{:toc}

# Règles du jeu

## Le tour de jeu

Une partie se déroule en un nombre de tours variable, qui dépend notamment du scénario choisi, des conditions de victoire et du temps qu'il reste avant le dîner.

Un tour consiste en une suite d'activation d'unités. Lorsque c'est son tour, un joueur peut choisir une unité qu'il n'a pas encore activé pour l'activer, ou passer la main. Ensuite, c'est au joueur suivant, etc. On tourne ainsi jusqu'à ce qu'il ne reste plus d'unités à activer ou que tous les joueurs passent la main successivement. Si un des joueurs dispose de plus d'unités que les autres, il pourra finir le tour seul en activant toutes ses unités restantes.

### Unité

Une unité peut correspondre à :
* un titan
* un groupe de super-lourds identiques et cohérents
* un groupe de combat léger (infanterie, blindés, cohérent à 5cm)

Un groupe cohérent doit s'efforcer de *finir* son activation de façon à être connexe par arcs de moins de 5cm. 

Une unité a un certain nombre de point d’action chaque tour (qui peut être variable). Avec un point d’action, il est possible de :
* se déplacer de sa capacité de mouvement (au maximum deux fois)
* utiliser une arme
* viser pour bénéficier de +1 au toucher sur la prochaine utilisation d'une arme et choisir l'effet le cas échéant (exemple viser le réacteur d'un titan)
*  mettre une arme en alerte (2PA) jusqu’à la prochaine activation de l'unité. L'unité  peut alors attaquer avec cette arme en réaction à une action ennemie à n’importe quel moment tant qu’elle a une ligne de vue sur l’ennemi à cet instant.
* faire une action spéciale (réparer ses boucliers, etc.)

### Combat
Pour une arme, on jette le nombre de dés d’attaque. Un 1 rate toujours, un 6 touche toujours.
Pour chaque touche on fait un jet de dommages 1D6+Force de l’arme. Si le résultat est supérieur ou égal à la valeur d’armure, on inflige un nombre de dégâts égal à la différence, avec un minimum de 1 (dans l'ordre ... 0, 1, 1, 2, 3, 4, etc.). Une arme de titan inflige toujours un dégât sur un 6. Chaque point de dégât retire un point de structure supplémentaire à la cible. Arrivés à zéro, la cible est détruite.

Si seulement 50% la cible est visible, on applique -1 pout toucher.

Si le tireur n'a pas encore bougé pendant son activation, on applique +1 pour toucher.

Une arme qui a déjà servi dans le tour subit un modificateur cumulatif de -1 au toucher (il devient de plus en plus dur de viser, ou les combattants sont fatigués). Les armes notées `!X` ne peuvent être utilisées qu’une seule fois par tour.

Si une arme est notée `CC` (close combat) l’unité adverse a l’opportunité d’attaquer avec une arme de close combat si elle en possède une et qu’elle est encore en vie après la résolution de l’attaque.
Les attaques de close combat ont une portée de 3 cm. 
  

## Types d'unités

### Titans
Lorsque l’on attaque un titan, on choisi d’attaquer haut ou bas. Pour les armes à courte portée, il peut être nécessaire de vérifier que l’on peut attaquer la zone. En général seuls les titans pourront attaquer les autres titans en haut.

### Super lourds
Capables d’encaisser plusieurs dégâts. En général, un super lourd perd 1PA par dommage reçu.

### Infanterie et unités légères
Une unité légère (pas un super lourd, ni un titan) peut se déplacer de 5 cm juste avant d’attaquer avec une arme `CC`. Cela représente la charge au corps à corps.

# Forces de l'Imperium

## Titans impériaux

* Les titans impériaux touchent sur un 4+.
* Un bouclier a une armure de 8.
* On répare un bouclier sur un 4+, on lance 1D6 par bouclier tombé.
* Action spéciale : puissance sur le générateur de boucliers (VSG) 1PA pout avoir des bouclier à 10 d'armure jusqu'à la prochaine activation du titan. Lancer 1D6, sur un 1 le générateur de boucliers est détruit.

### Dégâts sur les titans impériaux

En haut, à partir du deuxième point de structure perdu, on tire un D6 pour déterminer un effet spécial : 
<ul>
	<li>[1-3] une arme détruite</li> 
	<li>[4] VSG détruit, puis réacteur endommagé</li> 
	<li>[5-6] réacteur endommagé (-2PA), puis explosion</li>
</ul>
En bas, le premier point de structure fait perdre un 45°, le deuxième la moitié de la distance de mouvement, le troisième un autre 45° (s'il n'en reste pas, la moitié du mouvement restant, etc.) Un titan à qui il reste au moins 1 cm de mouvement peut toujours choisir de tourner de 45° au lieu d'avancer. 

### Mouvement

Si un titan choisit de reculer pendant son action de mouvement, son déplacement est réduit de moitié.

Si un titan passe sur un terrain difficile pendant son action de mouvement, son déplacement est réduit de moitié.


### Armes des titans impériaux

<div class="row">
  <div class="col-1-4 unit-sheet">
    	<div class="centered" style="font-weight: bold;">Multilaser</div>
	  	<div>45cm // 6xF4</div>
  </div>
  <div class="col-1-4 unit-sheet">
    	<div class="centered" style="font-weight: bold;">Gatling Blaster</div>
	  	<div>45cm // 4xF5</div>
  </div>
  <div class="col-1-4 unit-sheet">
    	<div class="centered" style="font-weight: bold;">Plasma Cannon</div>
	  	<div>45cm // 2xF6</div>
  </div>
  <div class="col-1-4 unit-sheet">
    	<div class="centered" style="font-weight: bold;">Volcano Cannon</div>
	  	<div>60cm // 1xF9</div>
  </div>
</div><!-- /.row -->
<div class="row">
  <div class="col-1-4 unit-sheet">
    	<div class="centered" style="font-weight: bold;">Chainfist</div>
	  	<div>CC // 2xF7</div>
  </div>
  <div class="col-1-4 unit-sheet">
    	<div class="centered" style="font-weight: bold;">Powerfist</div>
	  	<div>CC // !1xF9</div>
  </div>
  <div class="col-1-4 unit-sheet">
    	<div class="centered" style="font-weight: bold;">Attaque improvisée</div>
	  	<div>CC // 1xF5</div>
  </div>
</div><!-- /.row -->
<div class="row">
  <div class="col-1-3 unit-sheet">
    	<div class="centered" style="font-weight: bold;">Quake Cannon</div>
	  	<div>90cm // 1xF7</div>
	  	<div>Si un Quake Cannon touche, il inflige au moins point un dégât</div>
  </div>
  <div class="col-1-3 unit-sheet">
    	<div class="centered" style="font-weight: bold;">Missile Launcher</div>
	  	<div>60cm // D6xF5</div>
	  	<div>Peut tirer en indirect si un titan ami voit la cible</div>
  </div>
  <div class="col-1-3 unit-sheet">
    	<div class="centered" style="font-weight: bold;">Plasma Annihilateur</div>
	  	<div>60cm // 4xF9</div>
	  	<div>3 PA pour tirer</div>
	  	<div>Impossible de viser avec cette arme</div>
  </div>
</div><!-- /.row -->
<div class="row">
  <div class="col-1-1 unit-sheet">
    	<div class="centered" style="font-weight: bold;">Trident</div>
	  	<div>20cm // 1xF7</div>
	  	<div>
			<ul>
				<li>Ignore les boucliers</li>
				<li>Si des dégâts sont infligés ou si le jet de toucher est de 4+, le trident est accroché à la cible. L'attaquant peut décider de décrocher à la fin de n'importe quelle activation (amie ou ennemie)</li>
				<li>Impossible de s'éloigner</li>
				<li>N'importe lequel des deux (A) peut dépenser 1+ PA pour essayer de faire tomber l'autre (B). Chacun lance 1D6 (+PA pour A). Sur un 1 naturel A ou B tombe. Sur une égalité la chaîne casse. Si A obtient plus que B, B tombe</li>
			</ul>		
		</div>
  </div>
</div><!-- /.row -->



### Fiches

<div class="row">
  <div class="col-1-3 unit-sheet">
  	<div class="centered" style="font-weight: bold;">Seigneur de Guerre (12pt)</div>
  	<div class="centered" style="font-style: italic;">Warlord / Nemesis</div>
	<div>4 armes</div>
	<div>Mouvement 8 cm + 1x45°</div>
	<div><span>BAS - Armure 12/10</span> ◎◎◎◎◎</div>
	<div><span>BAS - Armure 12/10</span> ◎◎◎◎◎</div>
  </div>
  <div class="col-1-3 unit-sheet">
  	<div class="centered" style="font-weight: bold;">Seigneur de Guerre (10pt)</div>
  	<div class="centered" style="font-style: italic;">Warlord / Death Bringer</div>
	<div>3 armes</div>
	<div>Mouvement 12 cm + 1x45°</div>
	<div><span>BAS - Armure 12/10</span> ◎◎◎◎◎</div>
	<div><span>BAS - Armure 12/10</span> ◎◎◎◎◎</div>
  </div>
  <div class="col-1-3 unit-sheet">
  	<div class="centered" style="font-weight: bold;">Seigneur de Guerre (8pt)</div>
  	<div class="centered" style="font-style: italic;">Warlord / Night Gaunt</div>
	<div>2 armes</div>
	<div>Mouvement 16 cm + 2x45°</div>
	<div><span>BAS - Armure 12/10</span> ◎◎◎◎◎</div>
	<div><span>BAS - Armure 12/10</span> ◎◎◎◎◎</div>
  </div>
</div><!-- /.row -->

<div class="row">
  <div class="col-1-3 unit-sheet">
  	<div class="centered" style="font-weight: bold;">Écumeur (7pt)</div>
  	<div class="centered" style="font-style: italic;">Reaver</div>
	<div>3 armes</div>
	<div>Mouvement 16 cm + 2x45°</div>
	<div><span>BAS - Armure 11</span> ◎◎◎◎</div>
	<div><span>BAS - Armure 11</span> ◎◎◎◎</div>
  </div>
  <div class="col-1-3 unit-sheet">
  	<div class="centered" style="font-weight: bold;">Chien de Guerre (4pt)</div>
  	<div class="centered" style="font-style: italic;">Warhound</div>
	<div>2 armes</div>
	<div>Mouvement 24 cm / 3x45°</div>
	<div><span>BAS - Armure 10</span> ◎◎◎</div>
	<div><span>BAS - Armure 10</span> ◎◎◎</div>
	<div>Manoeuvrable: -1 pour toucher un Chien de Guerre</div>
  </div>
</div><!-- /.row -->

# Forces Orks

