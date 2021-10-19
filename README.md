# machine-learning-habitabilite-exoplanete

Au terme de ces deux dernières années, nous avons eu pour but de créer un programme permettant
de trouver, à l’aide de l’apprentissage automatique, l’habitabilité d’une exoplanètes inconnue à partir
de ses principales caractéristiques.
Nous avons donc dans un premier temps, au moyen d’une recherche bibliographique, étudié les
données qui seraient les plus pertinentes. Cela nous a permis de trouver quelles caractéristiques et
critères rendent une planète habitable. Cependant, lors de la création de notre base de données, certaines exoplanètes avaient des données manquantes, celles-ci correspondaient souvent aux même
critères et caractéristiques. Nous les avons donc enlevé au risque de transmettre de mauvaises données et ainsi corrompre l’apprentissage automatique de notre programme.
Nous avons Finalement retenus les critères suivant :
— La distance entre la planète et son étoile
— La température moyenne de la planète
— La masse de la planète ainsi que celle de son étoile
— La périodicité de la planète (le temps qu’elle prend pour faire un tour sur elle-même)
— Le rayon de la planète
— L’habitabilité de la planète (utilisé seulement lors de l’apprentissage du programme)
Une fois la recherche des caractéristiques d’exoplanète habitable établie, nous avons dû nous renseigner quant aux différents types d’apprentissage automatique existant, afin de mieux comprendre
où nous orienter. Nous avons Finalement décidé de nous reposer sur un algorithme reposant sur le
principe de Deep Learning, associé à un apprentissage supervisé. Nous nous sommes aidés de TensorFlow afin de pouvoir mettre en place cet algorithme.
C’est avec l’aide de la bibliothèque et des tutoriels disponibles sur le site de TensorFlow, que nous
avons pu obtenir un algorithme qui répondait à nos besoins. Nous avons ainsi adapté notre base de
données (construite l’année précédente), afin que cette dernière répondent aux exigences de l’algorithme (format CSV). Lors de la première exécution de l’algorithme d’apprentissage automatique,
nous avons été surpris par le bon taux de réussite que nous rendait l’algorithme. Par la suite, nous
avons effectué quelques modifications, afin de vérifier si ces dernières pouvaient encore augmenter
le taux de réussite de notre algorithme.

Le rapport complet est disponible à cette adresse : https://www.yohandugain.com/files/pdf/Utilisation%20du%20marchine%20learning%20pour%20de%CC%81terminer%20l'habitabilite%CC%81%20d'une%20exoplane%CC%80te.pdf

Le poster est disponible à cette adresse : https://www.yohandugain.com/files/pdf/Re%CC%81sume%CC%81%20-%20Utilisation%20du%20marchine%20learning%20pour%20de%CC%81terminer%20l'habitabilite%CC%81%20d'une%20exoplane%CC%80te.pdf