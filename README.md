# Project_Hopper

Le projet Hopper consiste en l'établissement d'une simulation numérique fonctionnelle et réaliste du robot Hopper qui est la base de la modélisation des robots bipèdes complexes. Le simulateur se divise en quatre codes:

-air_R.py où est implémentée la dynamique du robot lorsqu'il se trouve dans les airs
-sol_R.py où est implémentée la dynamique du robot lorsqu'il est en contact avec le sol
-OrderStateMachine_R.py où est codée la machine à états qui lie les commandes et les différentes phases
-main.py qui constitue le fichier à exécuter pour faire tourner la simulation

Il est nécessaire pour le bon fonctionnement du simulateur d'installer python ainsi que les modules numpy, scipy_integrate et pygame. Les quatre fichiers python doivent occupés un même dossier, et il suffit ensuite de lancer le fichier main.py pour lancer la simulation.
