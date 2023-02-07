# FairML_Reading
Collection of Fair Machine Learning papers

- Many papers credit to [Richard Zemel](https://www.cs.columbia.edu/~zemel/)'s seminar
- I will keep updating the paper list about fair machine learning + Diversity, Equity, Inclusion (DEI)

## Table of Contents
- [Survey Paper](#survey-paper)
- [Source of Bias](#source-of-bias)
- [Definition and Trade-offs](#definitions-and-trade-offs)
- [Fairness Representations](#fairness-representations)
- [Domain Generalization Methods](#domain-generalization-methods)
- [Causality / Structural Causal Models](#causality--structural-causal-models)
- [Fairness without Group Labels](#fairness-without-group-labels)

## Survey Paper
- [Fairness in Learning-Based Sequential Decision Algorithms: A Survey](https://arxiv.org/abs/2001.04861)
- [Fairness Machine Learning](https://fairmlbook.org/), Solon Barocas, Moritz Hardt, Arvind Narayanan


## Source of Bias
- [Semantics derived automatically from language corpora contain human-like biases](https://researchportal.bath.ac.uk/en/publications/semantics-derived-automatically-from-language-corpora-necessarily), Caliskan, Aylin, Joanna J. Bryson, and Arvind Narayanan, Science. 
- [Unbiased look at dataset bias](https://people.csail.mit.edu/torralba/publications/datasets_cvpr11.pdf)
- [A large-scale analysis of racial disparities in police stops across the United States](https://5harad.com/papers/traffic-stops.pdf), Pierson, Emma, Nature Human Behaviour
- [Why is my classifier discriminatory?](https://arxiv.org/pdf/1805.12002.pdf), Chen, Irene, Fredrik D. Johansson, and David Sontag. Advances in NIPS (2018).
- [Man is to computer programmer as woman is to homemaker? Debiasing word embeddings](https://arxiv.org/pdf/1607.06520.pdf)
- [Understanding undesirable word embedding associations](https://arxiv.org/pdf/1908.06361.pdf)


## Definitions and Trade-offs
- [Simplicity Creates Inequity: Implications for Fairness, Stereotypes and Interpretability](https://arxiv.org/pdf/1809.04578.pdf), Kleinberg, Jon, and Sendhil Mullainathan. ACM Economics and Computation. 2019.
- [Inherent Trade-Offs in the Fair Determination of Risk Scores](https://arxiv.org/pdf/1609.05807.pdf)
- [Fair prediction with disparate impact](https://www.liebertpub.com/doi/pdf/10.1089/big.2016.0047), Chouldechova, Alexandra. Big data (2017)
- [Inherent Tradeoffs in Learning Fair Representation](https://proceedings.neurips.cc/paper/2019/file/b4189d9de0fb2b9cce090bd1a15e3420-Paper.pdf), Zhao, Han, and Geoff Gordon. NIPS 2019
- [On the Impossibility of Fairness](https://arxiv.org/pdf/1609.07236.pdf)
- [Fairness Under Composition](https://arxiv.org/pdf/1806.06122.pdf)
- [Fairness-Efficiency Tradeoffs in Dynamic Fair Division](https://arxiv.org/pdf/1907.11672.pdf), Zeng, David, and Alexandros Psomas. ACM Economics and Computation. 2020.


## Fairness Representations
- [Learning Controllable Fair Representaions](https://arxiv.org/pdf/1812.04218.pdf), Song, Jiaming, Pratyusha Kalluri, Aditya Grover, Shengjia Zhao, and Stefano Ermon. AISTATS. PMLR, 2019.
- [Fairness Through Awareness](https://arxiv.org/pdf/1104.3913.pdf), Dwork, Cynthia, Moritz Hardt, Toniann Pitassi, Omer Reingold, and Richard Zemel. In Proceedings of the 3rd innovations in theoretical computer science conference. 2012.
- [Learning adversarially fair and transferable representations](https://arxiv.org/pdf/1802.06309.pdf), Madras, David, Elliot Creager, Toniann Pitassi, and Richard Zemel. ICML. PMLR, 2018.
- [Optimized data pre-processing for discrimination prevention](https://arxiv.org/pdf/1704.03354.pdf)
- [Certifying and removing disparate impact](https://arxiv.org/pdf/1412.3756.pdf), Feldman, Michael, Sorelle A. Friedler, John Moeller, Carlos Scheidegger, and Suresh Venkatasubramanian. KDD 2015.
- [Invariant representations without adversarial training](https://arxiv.org/pdf/1805.09458.pdf), Moyer, Daniel, Shuyang Gao, Rob Brekelmans, Aram Galstyan, and Greg Ver Steeg. NIPS 2018.


## Domain Generalization Methods
- [Distributionally robust neural networks for group shifts: On the importance of regularization for worst-case generalization](https://arxiv.org/abs/1911.08731?context=cs.LG), Sagawa, Shiori, Pang Wei Koh, Tatsunori B. Hashimoto, and Percy Liang. 2019.
- [Conditional variance penalties and domain shift robustness](https://arxiv.org/pdf/1710.11469.pdf), Heinze-Deml, Christina, and Nicolai Meinshausen. 2017.
- [Out-of-Distribution Generalization via Risk Extrapolation](https://arxiv.org/abs/2003.00688) Krueger, David, et al. ICML, 2021.
- [Conditional value-at-risk for general loss distributions](https://www.sciencedirect.com/science/article/pii/S0378426602002716) Rockafellar, R. Tyrrell, and Stanislav Uryasev. Journal of banking & finance (2002)
- [In search of lost domain generalization](https://arxiv.org/abs/2007.01434) Gulrajani, Ishaan, and David Lopez-Paz. arXiv preprint (2020).


## Causality / Structural Causal Models
- [On Pearl’s Hierarchy and the Foundations of Causal Inference](https://causalai.net/r60.pdf), Bareinboim, Elias, Juan D. Correa, Duligur Ibeling, and Thomas Icard. In Probabilistic and Causal Inference: The Works of Judea Pearl 2022.
- [Causal inference by using invariant prediction: identification and confidence intervals](https://arxiv.org/abs/1501.01332)
- [Counterfactual fairness](https://arxiv.org/abs/1703.06856), Kusner, Matt J., Joshua Loftus, Chris Russell, and Ricardo Silva. NIPS 2017
- [Causally Motivated Shortcut Removal Using Auxiliary Labels](https://arxiv.org/abs/2105.06422), Makar, Maggie, Ben Packer, Dan Moldovan, Davis Blalock, Yoni Halpern, and Alexander D’Amour. AISTATS PMLR, 2022.
- [Counterfactual Invariance to Spurious Correlations: Why and How to Pass Stress Tests](https://arxiv.org/abs/2106.00545)
- [Invariant Risk Minimization](https://arxiv.org/abs/1907.02893) Arjovsky, Martin, et al. (2019).
- [The Risks of Invariant Risk Minimization](https://arxiv.org/abs/2010.05761) Rosenfeld, Elan, Pradeep Ravikumar, and Andrej Risteski (2020)
- [Does invariant risk minimization capture invariance?](https://arxiv.org/abs/2101.01134) Kamath, Pritish, et al. AISTATS. 2021.

## Fairness without Group Labels
- [Fairness without Demographics through Adversarially Reweighted Learning](https://arxiv.org/abs/2006.13114) Lahoti, Preethi, et al. NIPS 2020
- [An Empirical Study of Rich Subgroup Fairness for Machine Learning](https://arxiv.org/abs/1808.08166) Kearns, Michael, et al. Proceedings of the conference on fairness, accountability, and transparency. 2019.
- [Fairness without demographics in repeated loss minimization](https://arxiv.org/abs/1806.08010) Hashimoto, Tatsunori, et al. ICML, 2018.
- [Calibration for the (computationally-identifiable) masses](https://arxiv.org/abs/1711.08513) Hébert-Johnson, Ursula, et al. ICML, 2018.