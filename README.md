Version de App1 avec Spring et en utilisant les annotations.

Il faudra ajouter les dépendances Spring Core, Spring Context et Spring Beans.

On évitera d'utiliser @Autowired mais plutôt l'injection via le constructeur. Vérifiez bien qu'il n'y a qu'un seul constructeur (avec paramètre) dans MetierImpl sans quoi il y aura un petit soucis..
