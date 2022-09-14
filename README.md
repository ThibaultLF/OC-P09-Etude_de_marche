# OC-P09-Produire_une_étude_de_marché

[![Language](https://img.shields.io/badge/R-darkblue.svg?style=flat&logo=R&logoColor=white)](https://www.r-project.org/)
[![RStudio](https://img.shields.io/badge/RStudio-darkgreen.svg?style=flat&logo=rstudio&logoColor=white)](https://www.rstudio.com/)
[![Framework](https://img.shields.io/badge/Plotly-darkorange.svg?style=flat&logo=plotly&logoColor=white)](https://plotly.com/)
[![Framework](https://img.shields.io/badge/Factominer-red.svg?style=flat&logo=factominer&logoColor=white)](http://factominer.free.fr/index_fr.html)


Production d'une étude de marché afin de conseiller au mieux l'entreprise qui souhaite se développer à l'international. Ce projet permet de récupérer ses propres données en utilisant les critères de l'analyse PESTEL.
Une fois les données récupérées, on effectuera une ACP, CAH et K-Means afin de voir quelles caractéristiques ressortent de chaque groupe. Nous effectuerons alors un choix du groupe à sélectionner pour le développement à l'international.
Tout cela a été effectué avec RStudio en Rmarkdown. Vous retrouverez donc dans ce repo les fichiers suivants:
- Le notebook *Traitement_Data* avec son fichier html éponyme qui comprend l'analyse primaire de chaque BDD ainsi que les jointures qui permettront d'avoir une BDD unifiée;
- Le notebook *Analyse_Clustering* ainsi que le fichier édité en html qui effectue l'étude de marché en utilisant les méthodes d'ACP, de CAH et K-means et rend les conclusions par rapport aux choix des groupes pour l'internationalisation;
- Un dossier *Données* qui comprend tous les fichiers nécéssaires à l'éxécution des notebooks.


## Scénario du projet

Vous travaillez chez La poule qui chante, une entreprise française d’agroalimentaire. Elle souhaite se développer à l'international.  
L'international, oui, mais pour l'instant, le champ des possibles est bien large : aucun pays particulier ni aucun continent n'est pour le moment choisi. Tous les pays sont envisageables !


### Besoins en analyse de données:

Comme on en a déjà brièvement parlé, je te fais ce mail pour te briefer sur la mission d’analyse pour le lancement à l’international.

Ton objectif sera de proposer une première analyse des groupements de pays que l’on peut cibler pour exporter nos poulets. Nous approfondirons ensuite l'étude de marché. 

Tu seras en totale autonomie sur ce projet, notamment sur le choix des données à analyser et même du langage à utiliser (R ou Python). 

Pars des données de la FAO (Food and Agriculture Organization) que je te mets en pièce jointe pour faire ton analyse. Si tu veux aller plus loin, notamment avec les critères de l’analyse PESTEL, tu peux récupérer et utiliser toutes les données en open data que tu souhaites.

Pour la partie analyse, dans un premier temps j’aimerais que tu testes la classification ascendante hiérarchique, avec un dendrogramme comme visualisation. Ensuite tu pourras utiliser la méthode des k-means, afin d’affiner l’analyse et comparer les résultats des deux méthodes de clustering. N'hésite pas à prendre le temps d’analyser les centroïdes de tes classes. Tu peux également réaliser une ACP afin de visualiser les résultats de ton analyse, comprendre les groupes, les liens entre les variables, les liens entre les individus...

### **Livrable:**
- Notebook R Markdown