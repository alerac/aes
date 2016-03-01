% Advanced Engine Search
% Alexandre Racine - Igor Milhit
% 2 mars 2016

# Introduction

## *Google Search*

* partout, tout le temps
* *Google* me connaît mieux que moi-même
* intrusif mais **efficace**

## *Google Search*

...pourtant, *parfois*, le besoin d'aller plus loin se fait sentir.

* Qui connaît la recherche avancée de *Google* ?
* Qui l'utilise ?
* Et la syntaxe de recherche, c'est... ?

## Fonctionnement de base

* Par mots clés : ``panda roux``
* Opérateur par défaut : ``ET``
* Phrases simples : ``l'aéroport le plus proche``

## Terme manquant

Exemple : [https://www.google.ch/search?q=panda+python+goudron](https://www.google.ch/search?q=panda+python+goudron)

## Exercice pratique

Nous voulons acheter du *thé vert japonais* à la fin de notre journée de travail.

Proposez-nous des adresses.

[Solution](https://www.google.ch/search?q=thé-vert-japonais)

# Des mots clés particuliers

## Définition

``définition [terme]``   
fait apparaître la définition du terme avant les résultats.

## Météo

Quel temps fait-il à *New Dehli* ?

``météo dehli`` : [https://www.google.ch/search?q=météo+dehli](https://www.google.ch/search?q=météo+dehli)

Vous pouvez faire quelques tests... Quelle est la source ? Est-ce toujours correct ?

## Calcul

Peut donner le résultat d'un calcul :

14 x 18 → 14 * 18

[https://www.google.ch/search?q=14+*+18](https://www.google.ch/search?q=14+*+18)

## Exercice pratique

Trouvez comment obtenir le résultat de *5 à la puissance 5*

[Solution](https://www.google.ch/search?q=5^5)

## Conversion d'unité

``3 dollars en francs suisse`` : [https://www.google.ch/search?q=3+dollars+en+francs+suisse](https://www.google.ch/search?q=3+dollars+en+francs+suisse)

## Exercice pratique

* Essayez de convertir des unités de volume  
Ex :``litres vers cm3``
* Explorez maintenant les autres possibilités de conversion d'unités

## Autres conversions

<img src="images/autres-conversions.png" style="width:700px;" />

# Recheche avancée

## Où la trouver ?

Au fond de la page, sous ``Parmètres > Recherche avancée`` :

<img src="images/ou-recherche-avancee.png" style="width:400px;" />

## Où la trouver ?

Au sommet de la page, sous la roue crantée :

<img src="images/ou-recherche-avancee-2.png" style="width:350px;" />

## Le masque

* ``statistiques bibliothèques`` entre les années ``2014 et 2016`` au format de fichier ``Excel``
* Comment ?
* [Solution](https://www.google.ch/advanced_search?q=statistiques+biblioth%C3%A8ques+filetype:xls+2014..2016&lr&hl=fr&as_qdr=all)

## Mise en évidence syntaxe

* Renvoi au champ de recherche simple
* Affinage des résultats
* Comment trouver des résultats limités au site de la confédération suisse ?
* [Solution](https://www.google.ch/search?hl=fr&as_q=statistiques+biblioth%C3%A8ques+2014..2016&as_epq=&as_oq=&as_eq=&as_nlo=&as_nhi=&lr=&cr=&as_qdr=all&as_sitesearch=&as_occt=any&safe=images&as_filetype=xls&as_rights=#hl=fr&as_qdr=all&q=statistiques+biblioth%C3%A8ques+2014..2016+filetype:xls+site:admin.ch)

# Autres opérateurs

## Exemples

## inurl:

* Retrouve le terme contenu dans une URL
* Retrouvez les sites rattachés à la heg de cette manière
* [Solution](https://www.google.com/search?biw=1280&bih=643&noj=1&q=inurl%3Ahesge.ch%2Fheg&oq=inurl%3Ahesge.ch%2Fheg&gs_l=serp.3...132548.147893.0.148130.46.36.9.1.3.0.421.3954.4j17j4j0j1.26.0....0...1c.1.64.serp..14.15.1086.U1BSbEEw1r4)
* Comparaison avec l'opérateur ``site:`` vu plus haut
* Quel constat ?

## cache:

Permet de consulter une page telle qu'elle s'affichait lors de la dernière exploration Google.

* [La quadrature du net (29.02.2016 21h18)](http://webcache.googleusercontent.com/search?q=cache:www.laquadrature.net/fr&ie=utf-8&oe=utf-8&gws_rd=cr&ei=OfvVVtuuJYbyUPr7hZgB)
* [La quadrature du net (maintenant)](https://www.laquadrature.net/fr)
* Quel constat ?

## OR, |

Permet de rechercher des pages qui ne contiennent qu'un terme parmi plusieurs.

[Exemple 1](https://www.google.ch/search?q=statistiques+biblioth%C3%A8ques+OR+population&ie=utf-8&oe=utf-8&gws_rd=cr&ei=5QHWVoGuNoW5PcbztuAE)

[Exemple 2](https://www.google.ch/search?q=statistiques+biblioth%C3%A8ques+OR+population&ie=utf-8&oe=utf-8&gws_rd=cr&ei=5QHWVoGuNoW5PcbztuAE#q=statistiques+emploi+|+salaire)

## " "

Permet de trouver l'expression exacte. Telle qu'elle apparaît.

[Exemple 1](https://www.google.ch/search?q=casser+les+pieds&ie=utf-8&oe=utf-8&gws_rd=cr&ei=OAPWVs3fBYXRO-fbk4gL#q=faire+passer+un+chameau+par+le+chas+d%27une+aiguille)

[Exemple 2](https://www.google.ch/search?q=casser+les+pieds&ie=utf-8&oe=utf-8&gws_rd=cr&ei=OAPWVs3fBYXRO-fbk4gL#q=%22faire+passer+un+chameau+par+le+chas+d%27une+aiguille%22)

Observez les différences entre ces deux exemples.

## * (troncature)

Lorsque vous ne connaissez pas ou n'êtes pas sûr du terme que vous recherchez

[Exemple 1](https://www.google.ch/search?q=%22un+*+vaut+mieux+que+deux+*%22&ie=utf-8&oe=utf-8&gws_rd=cr&ei=zwXWVrPCFMX_O_z2kOAJ#)

[Exemple 2](https://www.google.ch/search?q=%22un+*+vaut+mieux+que+deux+*%22&ie=utf-8&oe=utf-8&gws_rd=cr&ei=zwXWVrPCFMX_O_z2kOAJ#q=%22un+tiens+vaut+mieux+que+deux+*%22)

Observez les différences entre ces deux exemples.

# En conclusion

## Les trucs à retenir

* Recherche simple **peut** suffire mais...
* Recherche avancée pour aller **plus loin**
* **Combinaison** de plusieurs opérateurs
* **Dépend des besoins** de la requête...
* et de **l'adéquation** à votre recherche
* **Analyse** des résultats ``ET`` esprit **critique**

## Merci de votre attention
