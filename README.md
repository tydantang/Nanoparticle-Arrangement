# Nanoparticle-Arrangement
This project aims on generating predictive models as well as sorting out the most important features that determine the types of nanoparticle arragement. The results were treated as a reference for a NSF funded nanoparticle arrangement research that has been published on ACS Macromolecules[1]. Nanoparticle arrangement data was prepared using Monte Carlo simulations.

In this project, supervised learning algorithms and unsupervised clustering algorithms were applied and evaluated for classifying 3 types of nanoparticle arrangements. Supervised learning algorithms, including Decision Tree, Random Forest, and K-Nearest Neighbor (KNN) methods, were first carried out along with some parameter exploration. Each of these yielded decent performance with accuracy over 75% for Decision Tree and Random Forest, and ~65% for KNN. Unsupervised algorithms including Kmeans, GaussionMixture, and DBSCAN were also carried out. Due to the continuous data, unsupervised algorithms did not perform well.

Feature importance was performed using Decision Tree and Random Forest. The results were surprisingly consistent to those obtained from highly computation demanding Molecular Dynamic simulations.

1. https://pubs.acs.org/doi/abs/10.1021/acs.macromol.6b01936
