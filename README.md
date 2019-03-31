# Jauge-compteur-winhex
Widget pour Jeedom: Jauge compteur winhex / Version=dashboard- Type=info- S/Type=numeric

Au préalable (à configurer rubrique 7.1) https://jeedom.github.io/core/fr_FR/administration 
ainsi que l'activation historique minimum 1 jour
Afficher les statistiques sur les widgets et Période de calcul pour min, max, moyenne (en heures)

pour le reste se réfèrer au lien forum


Paramètres optionnels widget :

decimal : 1 chiffre (default =1); &quot;chiffre aprés la virgule&quot;

min_max : 2 chiffres séparés par une virgule (default = echelle sur max/mini de l'historique); &quot;debut et fin du compteur, on peux y mettre -&quot;

interval : 1 chiffre (default = arrondi de max - min +1/3 qui aura comme minimum 1) &quot;chiffre du compteur, on peut y mettre 0.5 voir moin&quot;

couleur : 12 séparés par une virgule (default = white,WhiteSmoke,WhiteSmoke,WhiteSmoke,WhiteSmoke,WhiteSmoke,WhiteSmoke,green,gray,WhiteSmoke,#006CA9,red) 
hormis la jauge c'est toutes les couleurs du widget
