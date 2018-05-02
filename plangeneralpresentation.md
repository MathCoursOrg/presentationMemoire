# Plan de présentation

## Première partie 

### Introduction & premières définitions et résultats.

La première partie est une introduction aux concepts de l'algèbre de Banach, homomorphismes, idéaux et tout ce qui s'en suit.

### Lemme de W

Ensuite, lemme de W, et preuve pour parler d'une première application

### Parler de la GN pour la physique

On doit citer les théorèmes de GN et GNS pour la partie physique. Pour établir le lien entre les axiomes de la physique quantique
et ces théorèmes.

# Transition

Mais qu'est-ce qui motive l'étude des algèbres de Banach ? La réponse nous est donné par la physique quantique. Nous verrons cela
en détail dans la partie suivante 

## Physique quantique

### Interprétation des observables 

On attaque l'interprétation physique des algèbres de Banach.

Un système physique est caractérisé par ses propriétés physiques, qui sont mesurables à l'aide d'appareil de mesure ( position,
vitesse, électromagnétisme, que sais-je encore...

**Relire la page 76 de [FS] !!!** Elle donne une définition claire et *courte* des états, observables etc..
En fait, on peut commencer la relecture à partir de cette page, tout est synthétiser.


#### Définition d'une observable 

Soit $O$ l'ensemble des caractéristiques que l'on peut mesurer. Alors, multiplier A\in O par \lambda revient à changer l'échelle
de l'appareil de mesure, un changement d'unité on pourrait dire. De même, mesurer A^2 revient à mettre la mesure de l'observable
au carré. De la même manière pour A^n.

Une observable A \in O est dite positive si tout les mesures qui lui sont faites sont positives. 

On peut donc mesurer tout polynôme d'une observable, simplement en appliquant ce polynôme aux mesures de A\in O.

#### Définition d'un état$

Un état, ou espace de phase, d'un système physique, c'est la moyenne constatée de plusieurs mesures d'une même observable A \in O.On pose donc
\omega(A) = \lim \frac { \sum f_i (A) } {n} 

C'est donc une fonction qui va de O à R On a des propriétés de linéarité évidentes sur \omega \omega ( \lambda A ) = \lambda
\omega(A), et la somme des espérances et l'espérance de la somme.

On a aussi une identification immédiate si pour tout observable, deux états donnent la même espérance, alors ils sont égaux

Comme on ne peut faire la différence entre deux observables que en les mesurant, on dit que  A~B si et seulement si \omega(A) =
\omega(B) (on ne peut pas faire la différence entre A et B). C'est évidemment une relation d'équivalence. Et nous allons
considérer les classes d'équivalences de cette relation.

#### La structure de C étoile-algèbre 

On pose la norme :
|| A || = sup { \omega } | \omega(A) | sachant que omega est une fonction qui a une image réelle.

C'est une norme avec la propriété voir la démonstration page 18 de [FS]
|| A ^ 2 || = || A || ^ 2

Ensuite, on considère que l'on complète O pour obtenir un espace de Banach.

Puis, on considère la complexification des observables :
O^C = { A + i B | A, B \in O}
avec 
\omega{A + i B) = \omega{A} + i \omega{B}


### Interprétation de la non commutativité des observables 

Lien avec le principe d'incertitude de Heisenberg !

### On fait le point

On fait la liste des axiomes de la physique quantique (dans les parties suivantes on va motiver ces axiomes avec les théorèmes GN
et GNS)

### Interprétation des théorèmes de GNS

On donne une interprétation physique des théorèmes de représentation de GN.

## Démonstration des gros théorèmes 

On fait la synthèse des deux parties en finissant sur les théorèmes de GN et de construction de GNS et leur preuves.

## Conclusion

Nous avons vu que la théorie de Gelfand a plusieurs intérêt :
    * Simplifier des preuves et fournir un cadre naturel pour généraliser la transformée de Fourier.
    * Représenter les observables en physique quantique.
    * Le puissant théorème de GN ramène l'étude de ces types d'algèbres à des sous algèbres de B(H), ou H est un hilbertien espace qui a énormément de propriétés sympa.

