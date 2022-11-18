## protocole de recherche : estimation de l'hémoglobine glyquée

La moyenne et la médiane sont graphiquement séparée sur les mesures AM (matin) de la glycémie, contrairement à celles de PM (après-midi).
Lors de précédente sessions cloud jamovi, une valeur significative de petit-p a été obtenu à l'aide de l'Anova de KW. Il convient donc d'intégrer dans le protocole de recherche 
sur l'eAb1c (hémoglobine glyquée qu'on peut estimer sur le site https://www.accu-chek.fr/eA1c-calculator) 

## approche non paramétrique : Anova de Kruskall-Wallis

une approche non paramétrique à partir des rangs de la glycémie et non plus à partir de la valeur continue mesurée.
n/ref: http://care.diabetesjournals.org/content/31/8/1473.full.pdf
projet sous R : utilisation des fonctions de Kruskall Wallis
https://biodatascience-course.sciviews.org/sdd-umons-2018/test-de-kruskal-wallis.html

### exemple concret : estimation à partir des données d'une semaine :
https://www.accu-chekconnect.com/ui/guest/login.jsf?country=LU
ex: pour une glycémie de moyenne à 122 mg/dL +/- 20 (écart-type), on obtiens une HbA1c estimée de 5,87% (< 6 ou 7%)
