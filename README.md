# [2025 IAIFI Summer School](https://iaifi.org/phd-summer-school.html)

## Introduction
Presented by Fabian Ruehle and Marisa LaFleur
Recording: To Come
Slides: [Introduction Slides](https://www.dropbox.com/scl/fi/kbjpk4vsunedwulezu2yb/2025_Summer-School_Introduction.pdf?rlkey=34cprm9ns3gqlhuk2saxrn3u8&dl=0)

## 1. Elements of Interactive Decision Making
(Author: Sasha Rakhlin)

Instructor: [Sasha Rakhlin](https://www.mit.edu/~rakhlin/)

Slides: To Come

### Useful materials

* [Foundations of Reinforcement Learning and Interactive Decision Making](https://arxiv.org/abs/2312.16730)

### Tutorial
(Author: Margalit Glasgow)

Instructor: [Margalit Glasgow](https://margalitglasgow.github.io)

Notebook: [https://drive.google.com/drive/folders/1eMn5tRMaO9JCbBKHheHIq-9M6g2yWSQN?usp=sharing](https://drive.google.com/drive/folders/1eMn5tRMaO9JCbBKHheHIq-9M6g2yWSQN?usp=sharing)

## 2. Physics-Guided Optimizations: Inform and Inspire AI Models with Physics Principles
(Author: Gaia Grosso)

Instructor: [Gaia Grosso](https://iaifi.org/current-fellows.html#gaia-grosso)

Slides: To Come

### Useful materials

* [An Introduction to Physics-Guided Deep Learning](https://www.pnas.org/doi/10.1073/pnas.2311808121)
* [Energy Based Models](https://www.researchgate.net/profile/Marcaurelio-Ranzato/publication/216792742_A_Tutorial_on_Energy-Based_Learning/links/0912f50c6862425435000000/A-Tutorial-on-Energy-Based-Learning.pdf)
* [The Role of Momentum in ML Optimization](https://distill.pub/2017/momentum/)
* [Entropy Regularization](https://www.researchgate.net/profile/Y-Bengio/publication/237619703_9_Entropy_Regularization/links/0f3175320aaecbde17000000/9-Entropy-Regularization.pdf)
* [Hamiltonian Neural Networks](https://proceedings.neurips.cc/paper/2019/file/26cd8ecadce0d4efd6cc8a8725cbd1f8-Paper.pdf)
* [Physics Informed Neural Networks](https://arxiv.org/pdf/2105.09506)`  
* [New Frontiers for Hopfield Networks](https://www.nature.com/articles/s42254-023-00595-y)
* [Diffusion Models](https://arxiv.org/pdf/2209.00796)

### Tutorial
(Author: Sean Benevedes and Jigyasa Nigam)

Instructors: [Sean Benevedes](https://physics.mit.edu/faculty/sean-benevedes/) and [Jigyasa Nigam](https://curiosity54.github.io)

Notebook: To come

## 3. Computing with Neural Manifolds: A Multi-Sclae Framework for Understanding Biological and Artificial Neural Networks
(Author: SueYeon Chung)

Instructor: [SueYeon Chung](https://as.nyu.edu/faculty/sueyeon-chung.html)

Slides: To Come

### Useful materials

* [Chung, S., Lee, D.D. and Sompolinsky, H., 2018. Classification and geometry of general perceptual manifolds. Physical Review X, 8(3), p.031003.](https://arxiv.org/abs/1710.06487)
* [Cohen, U., Chung, S., Lee, D.D. and Sompolinsky, H., 2020. Separability and geometry of object manifolds in deep neural networks. Nature communications, 11(1), p.746.](https://www.nature.com/articles/s41467-020-14578-5)
* [Chung, S. and Abbott, L.F., 2021. Neural population geometry: An approach for understanding biological and artificial neural networks. Current opinion in neurobiology, 70, pp.137-144.](https://arxiv.org/abs/2104.07059)
* [Yerxa, T., Kuang, Y., Simoncelli, E. and Chung, S., 2023. Learning efficient coding of natural images with maximum manifold capacity representations. Advances in Neural Information Processing Systems, 36, pp.24103-24128.](https://arxiv.org/abs/2303.03307)

### Tutorial
(Author: Sam Bright-Thonney)

Instructor: [Sam Bright-Thonney](https://www.sambrightthonney.com)

Notebook: To come

## 4. Domain Shift Problem: Building Robust AI Models with Domain Adaptation
(Author: Aleksandra Ciprajanovic)

Instructor: [Aleksandra Ciprajanovic](https://aleksandraciprijanovic.wordpress.com/)

Slides: To Come
  
### Useful materials

* [A Brief Review of Domain Adaptation](https://arxiv.org/pdf/2010.03978v1)
* [Deep Visual Domain Adaptation: A Survey](https://arxiv.org/pdf/1802.03601)
  
### Tutorial
(Author: Sneh Pandya)

Instructor: [Sneh Pandya](https://snehjp2.github.io)

Notebook: To come
  
    
## 5. Hackathon
At the end of the Hackathon on Friday, August 8, we will have a block for presentations of work done on these topics. Forming groups is strongly encouraged!

### Prompts
* Apply the contextual bandit framework to assigning treatments in randomized medical trials. Use data from The Third International Stroke Trial: [https://datashare.ed.ac.uk/handle/10283/1931](https://datashare.ed.ac.uk/handle/10283/1931), which contains patient data (contexts), the assigned treatment, and patient outcomes. Experiment with different (non-linear!) online regression oracles. Note: because the counterfactual data is not available, to test your algorithm, you will need to build an offline model to assign any unavailable rewards to your contextual bandit algorithm.
* Lipschitz Energy Flow Networks (L-EFNs, proposed in [https://arxiv.org/abs/2311.07652](https://arxiv.org/abs/2311.07652)) extend the intuition behind EFNs, providing a lever to manage the tradeoff between performance and robustness to mismodeling. Implement L-EFNs on the quark/gluon dataset from the tutorial, and find a way to characterize this tradeoff (or take this idea and run with it on a dataset of interest to you)!
* You have thus far learned how to apply a variety of domain adaptation (DA) techniques for classification. In this hackathon, attempt to use DA for a regression problem for predicting the Einstein radius (theta_E) of strong lensing (SL) systems in using the simulated SL dataset found here. This task simulates a realistic domain shift: training a model on synthetic (noiseless) SL images in the source and applying it to noisy images that resembles image quality from modern cosmological surveys. This project will encompass all parts of the typical ML pipeline, from data access and dataset construction (see this notebook for help in constructing the dataset), to model construction, training, validation, testing, and analysis. Use the ‘source_final.zip’ as your source dataset and ‘target_final.zip’ as your target dataset. Your analysis should include typical regression metrics, as well as visualizations of the NN latent space to quantify the domain alignment.
* More to come...
* Work on your own project! 

### Datasets
* Third International Stroke Trial: [https://datashare.ed.ac.uk/handle/10283/1931](https://datashare.ed.ac.uk/handle/10283/1931)
 
### Prize Categories
* Best project (effort, presentation, use of summer school topics)
* Best visualization
* Best team effort

## NSF ACCESS Instructions

[https://github.com/alexandergagliano/summer-school-2024/tree/main/computing](https://github.com/alexandergagliano/summer-school-2024/tree/main/computing)
