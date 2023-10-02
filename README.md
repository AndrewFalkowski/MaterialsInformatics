# MaterialsInformatics
MSE5050/7050 Materials Informatics course at the University of Utah

This github repo contains coursework content such as class slides, code notebooks, homework assignments, literature, and more for MSE 5050/7050 "Materials Informatics" taught at the University of Utah in the Materials Science & Engineering department. 

Below you'll find the approximate calendar for Spring 2022 and videos of the lectures are being placed on the following YouTube playlist
https://youtube.com/playlist?list=PLL0SWcFqypCl4lrzk1dMWwTUrzQZFt7y0

![My Image](YT_playlist.jpg)


| month | day | Subject to cover                                                                          | Assignment                                                                                                                  | Link                          |
|-------|-----|-------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| Jan   | 11  | Syllabus. What is machine learning? How are materials discovered?                         |                                                                                                                             |                               |
| Jan   | 13  | Machine Learning vs Materials Informatics, Materials Data repositories                    | Read 5 High Impact Research Areas in ML for MSE (paper1) and materials databases (paper2).                                  | [paper1](https://doi.org/10.1021/acs.chemmater.9b04078), [paper2](https://doi.org/10.1063/1.4944682)                |
| Jan   | 18  | Get pymatgen running for everybody, MP API example, Citrination example, others           | Download pymatgen ahead of class if possible                                                                                | [pymatgen](https://pymatgen.org/installation.html)                      |
| Jan   | 20  | Machine Learning Tasks and Types, Featurization in ML, Composition-based feature vector   | Read Is domain knowledge necessary for MI (paper1)                                                                          | [paper1](https://doi.org/10.1007/s40192-020-00179-z)                       |
| Jan   | 25  | Structure-based feature vector, crystal graph networks, SMILES vs SELFIES, 2pt statistics | read selfies (paper1), two-point statistics (paper2) and intro to graph networks (blog1)                                    | [paper1](https://doi.org/10.1088/2632-2153/aba947), [paper2](https://linkinghub.elsevier.com/retrieve/pii/S1359645408004886), [blog1](https://distill.pub/2021/gnn-intro/)         |
| Jan   | 27  | Simple linear/nonlinear models. test/train/validation/metrics                             | HW1 due. Read linear vs non-linear (blog1), read best practices (paper1), benchmark dataset (paper2), and loco-cv (paper3). | [blog1](https://statisticsbyjim.com/regression/choose-linear-nonlinear-regression/), [paper1](https://doi.org/10.1021/acs.chemmater.0c01907), [paper2](https://doi.org/10.1038/s41524-020-00406-3), [paper3](https://doi.org/10.1039/C8ME00012C) |
| Jan   | 1   | Support vector machines, ensemble models                                                  | Read SVM (blog1) and ensemble (blog2)                                                                                       | [blog1](https://towardsdatascience.com/the-complete-guide-to-support-vector-machine-svm-f1a820d8af0b), [blog2](https://towardsdatascience.com/ensemble-methods-bagging-boosting-and-stacking-c9214a10a205)                  |
| Feb   | 3   | Extrapolation, ensemble learning, clustering                                              | Read extrapolation to extraordinary materials (paper1), ensemble learning (paper2), clustering (blog1)                      | [paper1](https://doi.org/10.1016/j.commatsci.2019.109498), [paper2](https://doi.org/10.1007/s40192-020-00178-0), [blog1](https://towardsdatascience.com/how-exactly-umap-works-13e3040e1668)         |
| Feb   | 8   | Artificial neural networks                                                                | Read the introduction to neural networks (blog1, blog2)                                                                     | [blog1](https://towardsdatascience.com/machine-learning-for-beginners-an-introduction-to-neural-networks-d49f22d238f9), [blog2](https://towardsdatascience.com/a-gentle-introduction-to-neural-networks-series-part-1-2b90b87795bc)                  |
| Feb   | 10  | Advanced deep learning (CNNs, RNNs)                                                       | HW2 due. Read…                                                                                                              | [blog1](https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53), [blog2](https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53)                  |
| Feb   | 15  | Transformers                                                                              | Read the introduction to transformers (blog1, blog2)                                                                        | [blog1](https://medium.com/inside-machine-learning/what-is-a-transformer-d07dd1fbec04), [blog2](https://towardsdatascience.com/illustrated-guide-to-transformers-step-by-step-explanation-f74876522bc0)                  |
| Feb   | 17  | Generative ML: Generative Adversarial Networks and variational autoencoders               | Read about VAEs (blog1, blog2, repo1) and GANS ()                                                                           | [blog1](https://visualstudiomagazine.com/articles/2021/05/06/variational-autoencoder.aspx?m=1), [blog2](https://debuggercafe.com/getting-started-with-variational-autoencoder-using-pytorch/), [repo1](https://github.com/AntixK/PyTorch-VAE)           |
| Feb   | 22  | Image segmentation                                                                        | TBD                                                                                                                         |  TBD                             |
| Feb   | 24  | Bayesian Inference                                                                        | HW3 due. Read the introduction to Bayesian (blog1)                                                                          | [blog1](https://distill.pub/2019/visual-exploration-gaussian-processes/)                        |
| Feb   | 29  | TMS meeting, NO CLASS                                                                     |                                                                                                                             |                               |
| Mar   | 3   | Dr. Sparks at TMS meeting, Dr. Luther McDonald will provide guest lecture                                                               | TBD                                                                                                                         |   TBD                            |
| Mar   | 8   | Spring Break, NO CLASS                                                                    |                                                                                                                             |                               |
| Mar   | 10  | Spring Break, NO CLASS                                                                    |                                                                                                                             |                               |
| Mar   | 15  | Dr. Sparks at APS Meeting, Dr. Tolga Tasdizen will provide guest lecture                                                                 | Read U-net (paper1) and nuclear forensics (paper2)                                                                                                                         |   [paper1](https://arxiv.org/pdf/1505.04597.pdf), [paper2](https://doi.org/10.1016/j.jnucmat.2019.01.042)                            |
| Mar   | 17  | APS meeting, NO CLASS                                                                     |                                                                                                                             |                               |
| Mar   | 22  | Case study: Superhard materials, structure prediction                                     | Read superhard (paper1), and structure prediction papers (paper2)                                                           | [paper1](https://doi.org/10.1021/jacs.8b02717), [paper2](https://doi.org/10.1021/acs.chemmater.7b05304)                |
| Mar   | 24  | Case study: CGCNN vs MEGNET vs SchNET                                                     | Read CGCNN (paper1), MegNET (paper2), SchNET (paper3)                                                                       | [paper1](https://doi.org/10.1103/PhysRevLett.120.145301), [paper2](https://doi.org/10.1021/acs.chemmater.9b01294), [paper3](https://arxiv.org/abs/1706.08566)        |
| Mar   | 29  | Case study: CrabNET vs Roost                                                              | Read CrabNet (paper1) and Roost (paper2)                                                                                    | [paper1](https://doi.org/10.1038/s41524-021-00545-1), [paper2](https://doi.org/10.1038/s41467-020-19964-7)                |
| Mar   | 31  | Case study: Cococrab, BRDA                                                                | HW4 due. Read Cococrab (paper1) and BRDA (paper2)                                                                           | [paper1](https://doi.org/10.1007/s40192-021-00242-3), [paper2](https://chemrxiv.org/engage/api-gateway/chemrxiv/assets/orp/resource/item/61232ed2ded28ab922866adb/original/comparing-transfer-learning-to-feature-optimization-in-microstructure-classification.pdf)                |
| Apr   | 5   | Dr. Sparks at AIM 2022 meeting, Dr. Jake Hochalter will provide guest lecture.                                                          | Explainable/interpretable ML, physics-informed modeling                                                                     | TBD                           |
| Apr   | 7   | Dr. Sparks at AIM 2022 meeting, Dr. Ben Blaiszik of MDF will provide guest lecture.                                                          | MDF                                                                                                                         | TBD                           |
| Apr   | 12  | Case study: Element Mover’s Distance, Mat2Vec                                             | Read Element mover’s distance (paper1) and Mat2Vec (paper2)                                                                 | [paper1](https://doi.org/10.1007/s40192-021-00242-3), [paper2](https://chemrxiv.org/engage/api-gateway/chemrxiv/assets/orp/resource/item/61232ed2ded28ab922866adb/original/comparing-transfer-learning-to-feature-optimization-in-microstructure-classification.pdf)                |
| Apr   | 14  | Case study: Discover algorithm, Robocrystallographer                                      | TBD                                                                                                                         | TBD                           |
| Apr   | 19  | Final project presentation day 1                                                          | Final Project due                                                                                                           |                               |
| Apr   | 21  | Dr. Sparks at AMRAD meeting, Dr. Ashley Spear will provide guest lecture                                                             | TBD                                                                                                                         |     TBD                          |
| Apr   | 26  | Final project presentation day 2                                                          | Final Project due                                                                                                           |                               |
|       |     |                                                                                           |                                                                                                                             |                               |


I can recommend the book Introduction to Machine Learning found here https://www.statlearning.com/
