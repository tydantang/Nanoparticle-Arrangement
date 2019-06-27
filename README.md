# Nanoparticle-Arrangement

Full control of nanoparticle (NP) arrangement is critical in many advanced applications that rely on the organization of NP assemblies.
This project aims on generating predictive models as well as sorting out the most important features that can be used for determining the types of NP arragement in liquid-like media. NP arrangement data was prepared using Monte Carlo simulations. The results were treated as references for a NSF funded NP arrangement research that has been published on ACS Macromolecules[1]. 

In this project, supervised learning algorithms and unsupervised clustering algorithms were applied and evaluated for classifying 3 types of NP arrangements. Supervised learning algorithms, including Decision Tree, Random Forest, and K-Nearest Neighbor (KNN) methods, were first carried out along with some parameter exploration. Each of these yielded decent performance with accuracy over 75% for Decision Tree and Random Forest, and ~65% for KNN. Unsupervised algorithms including Kmeans, GaussionMixture, and DBSCAN were also carried out. Due to the continuous data, unsupervised algorithms did not perform well.

Feature importance was performed using Decision Tree and Random Forest. The results were consistent to those obtained from highly computation demanding Molecular Dynamic simulations. Features with higher importance rankings were proved to exhibit great predictive power for NP arrangement classification.

1. https://pubs.acs.org/doi/abs/10.1021/acs.macromol.6b01936
