# Machine Learning Papers

\* - essential papers

<!-- ## Bayesian ML

### Papers on Markov Chain Monte Carlo



### Papers by Emtiyaz Khan's group -->

## Causal ML

### Reviews and surveys

- [Causality for Machine Learning](https://arxiv.org/abs/1911.10500)*
- [From Statistical to Causal Learning](https://arxiv.org/abs/2204.00607)
- [Review by Glymour, Zhang and Sprites](https://pubmed.ncbi.nlm.nih.gov/31214249/)*
- [Causal Machine Learning: A Survey and Open Problems](https://arxiv.org/abs/2206.15475)
- [Towards Causal Representation Learning](https://arxiv.org/abs/2102.11107)

### The Classics

- [Greedy Equivalence Search](https://jmlr.org/papers/volume3/chickering02b/chickering02b.pdf)
- [Max-Min Hill Climbing](https://pages.mtu.edu/~lebrown/supplements/mmhc_paper/mmhc_index.html)

### Global optimization

- [Bayesian network learning with cutting planes](https://arxiv.org/abs/1202.3713)

### LiNGAM

- [LiNGAM](https://jmlr.org/papers/volume7/shimizu06a/shimizu06a.pdf)*
- [DirectLiNGAM](https://jmlr.csail.mit.edu/papers/volume12/shimizu11a/shimizu11a.pdf)
- [LiNGAM project homepage](https://www.shimizulab.org/lingam)

### Other identifiable models

- [Linear Gaussian with equal error variances](https://arxiv.org/abs/1205.2536)
- [Post-nonlinear model](https://arxiv.org/abs/1205.2599)
- [Nonlinear ANMs](https://papers.nips.cc/paper_files/paper/2008/hash/f7664060cc52bc6f3d620bcedc94a4b6-Abstract.html)*

### NOTEARS and continuous optimization
- [DAGs with NOTEARS](https://arxiv.org/abs/1803.01422)*
- [Nonlinear NOTEARS](https://arxiv.org/abs/1909.13189)
- [DAG-GNN](https://arxiv.org/abs/1904.10098)
- [Golem](https://arxiv.org/abs/2006.10201)
- [DAGs with NOFEARS](https://arxiv.org/abs/2010.09133)
- [DAGs with No Curl](https://arxiv.org/abs/2106.07197)
- [Structure Learning with Continuous Optimization: A Sober Look and Beyond](https://arxiv.org/abs/2304.02146)

### Neural DAG learning

- [GraN-DAG](https://arxiv.org/abs/1906.02226)
- [DCDI](https://arxiv.org/abs/2007.01754)*
- [DECI](https://arxiv.org/abs/2202.02195)
- [Learning Neural Causal Models from Unknown Interventions](https://arxiv.org/abs/1910.01075)

### Bayesian methods

BGe and BDe scores
- [BDe](https://arxiv.org/abs/1302.6815)
- [Learning Gaussian Networks](https://arxiv.org/abs/1302.6808)
- [BGe](https://arxiv.org/abs/2105.03248)
    - [2014 Addendum](https://arxiv.org/abs/1402.6863) (paper contains download link to supplement, which has many important details)
- [Interventional BGe](https://arxiv.org/abs/2205.02602)
- [DAG priors](https://proceedings.mlr.press/v89/eggeling19a.html)

MCMC methods
- [Structure MCMC](https://www.jstor.org/stable/1403615) (JSTOR link)
- [Order MCMC](https://arxiv.org/abs/1301.3856)
- [Partial Order sampling](https://jmlr.org/papers/volume17/15-140/15-140.pdf)
- [Markov Blanket resampling](https://jmlr.csail.mit.edu/papers/volume17/su16a/su16a.pdf)
- [Partition MCMC](https://arxiv.org/abs/1504.05006)*
- [Minimal I-MAP sampling](https://arxiv.org/abs/1803.05554)
- [BiDAG](https://arxiv.org/abs/1803.07859v4)
- [Gadget and Beeps](https://arxiv.org/abs/2010.00684)
- [BayesDAG](https://arxiv.org/abs/2307.13917)

Variational Inference
- [BCD Nets](https://arxiv.org/abs/2112.02761)* - VI for linear-Gaussian DAG posteriors
- [DDS](https://arxiv.org/abs/2203.08509) - Similar to BCD Nets, for nonlinear models
- [DiBS](https://arxiv.org/abs/2105.11839) - Model agnostic full Bayesian inference with SVGD
- [AVICI](https://arxiv.org/abs/2205.12934) - Likelihood free inference over DAGs
- [Variational Causal Networks](https://arxiv.org/abs/2106.07635) - VI for marginal posterior over DAGs using a BGe model

Generative Flow Networks
- [DAG-GFlowNet](https://arxiv.org/abs/2202.13903)* - Sampling from marginal posterior over DAGs using BGe / BDe models
- [VBG](https://arxiv.org/abs/2211.02763) - Sampling DAGs with GFlowNets and modeling parameter posteriors using VI
- [JSP-GFN](https://arxiv.org/abs/2305.19366) - Sampling both DAGs and parameters using a single GFlowNet

The role of priors in identifiability

- [Bivariate Causal Discovery using Bayesian Model Selection](https://arxiv.org/abs/2306.02931)
- [Continuous Bayesian Model Selection for Multivariate Causal Discovery](https://arxiv.org/abs/2411.10154)
- [A Meta-Learning Approach to Bayesian Causal Discovery](https://arxiv.org/abs/2412.16577)

### Modeling SDEs instead of Bayesian Networks

- [Causal Modeling with Stationary Diffusions](https://arxiv.org/abs/2310.17405)

### Active Causal Learning

- [Learning Neural Causal Models with Active Interventions](https://arxiv.org/abs/2109.02429)
- [Differentiable Multi-Target Causal Bayesian Experimental Design](https://arxiv.org/abs/2302.10607)

## Textbooks
- [Elements of Causal Inference](https://library.oapen.org/handle/20.500.12657/26040)
- [Causal Inference - The Mixtape](https://mixtape.scunning.com/)
- [Murphy's Probabilistic ML](https://github.com/probml/pml-book)
