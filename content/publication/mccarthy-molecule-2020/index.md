---
title: "Molecule Identification with Rotational Spectroscopy and Probabilistic Deep Learning"
date: 2020-04-01
publishDate: 2021-05-01T00:06:02.284639Z
authors: ["Michael McCarthy", "Kin Long Kelvin Lee"]
publication_types: ["2"]
abstract: "A proof-of-concept framework for identifying molecules of unknown elemental composition and structure using experimental rotational data and probabilistic deep learning is presented. Using a minimal set of input data determined experimentally, we describe four neural network architectures that yield information to assist in the identiﬁcation of an unknown molecule. The ﬁrst architecture translates spectroscopic parameters into Coulomb matrix eigenspectra as a method of recovering chemical and structural information encoded in the rotational spectrum. The eigenspectrum is subsequently used by three deep learning networks to constrain the range of stoichiometries, generate SMILES strings, and predict the most likely functional groups present in the molecule. In each model, we utilize dropout layers as an approximation to Bayesian sampling, which subsequently generates probabilistic predictions from otherwise deterministic models. These models are trained on a modestly sized theoretical dataset comprising ∼83 000 unique organic molecules (between 18 and 180 amu) optimized at the ωB97X-D/6-31+G(d) level of theory, where the theoretical uncertainties of the spectoscopic constants are well-understood and used to further augment training. Since chemical and structural properties depend strongly on molecular composition, we divided the dataset into four groups corresponding to pure hydrocarbons, oxygenbearing species, nitrogen-bearing species, and both oxygen- and nitrogen-bearing species, training each type of network with one of these categories, thus creating “experts” within each domain of molecules. We demonstrate how these models can then be used for practical inference on four molecules and discuss both the strengths and shortcomings of our approach and the future directions these architectures can take."
featured: true 
publication: "*The Journal of Physical Chemistry A*"
url_pdf: "https://pubs.acs.org/doi/abs/10.1021/acs.jpca.0c01376"
doi: "10.1021/acs.jpca.0c01376"
---

