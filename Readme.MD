This correction includes Abstrat classes and methods and shows how they are typically used to prevent code redundancy (ie writing the same code twice) by putting shared fuctions in classes to be inherited from and uses abstract fuctions to define the existence of fuction for which the implementation will change for every child class (here the Feed() method) This enables us to call (Animal.Feed())

Casting is used in the reproduce fuctions in both Lion and Gazelle. It is defined as Reproduce(Aminal beast) yet we need to access beast.EscapeChance and Animal.EscapeChance inst defined yet. So we cast the Animal as a Lion to access it. NB casting is dangerous and should only be done when we are CERTAIN we are right.

RESUME:

Inheritence => sharing code and making methods possible (Mate(Animal A, Animal b) n'est pas possible sans la classe Animal)

Casting => resoudre les problemes de type dus a ces fonctions generalistes (ici acceder a EscapeChance dans une variable dite Animal alors que l'on sait que c'est une proie)
