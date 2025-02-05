# Awesome-Optimizer
Collect optimizer related papers, data, repositories

| Title                                           |  Year    | Optimizer       | Published                                  | Code                                              | Keywords                                  |
| ---------------------- | ---------------------- | ---------|-------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------|
|A Stochastic Approximation Method|1951|SGD|[projecteuclid](https://projecteuclid.org/journals/annals-of-mathematical-statistics/volume-22/issue-3/A-Stochastic-Approximation-Method/10.1214/aoms/1177729586.full)|[code](https://github.com/mlpack/ensmallen/tree/master/include/ensmallen_bits/sgd)|gradient descent|
|Some methods of speeding up the convergence of iteration methods|1964|Polyak|[sciencedirect](https://www.sciencedirect.com/science/article/abs/pii/0041555364901375)||gradient descent|
|Large-scale linearly constrained optimization|1978|MINOS|[springerlink](https://link.springer.com/article/10.1007/BF01588950)||quasi-newton|
|On the limited memory BFGS method for large scale optimization|1989|L-BFGS|[springerlink](https://link.springer.com/article/10.1007/BF01589116)||quasi-newton|
|Particle swarm optimization|1995|PSO|[ieee](https://ieeexplore.ieee.org/document/488968)||evolutionary|
|Trust region methods|2000|Sub-sampled TR|[siam](https://epubs.siam.org/doi/book/10.1137/1.9780898719857)||inexact hessian|
|Evolving Neural Networks through Augmenting Topologies|2002|NEAT|[ieee](https://ieeexplore.ieee.org/document/6790655)|[code](https://github.com/goktug97/NEAT)|evolutionary|
|A Limited Memory Algorithm for Bound Constrained Optimization|2003|L-BFGS-B|[researchgate](https://www.researchgate.net/publication/2837734_A_Limited_Memory_Algorithm_for_Bound_Constrained_Optimization)|[code](http://users.iems.northwestern.edu/\~nocedal/lbfgsb.html)|quasi-newton|
|Online convex programming and generalized infinitesimal gradient ascent|2003|OGD|[acm](https://dl.acm.org/doi/10.5555/3041838.3041955)||gradient descent|
|A Stochastic Quasi-Newton Method for Online Convex Optimization|2007|O-LBFGS|[researchgate](https://www.researchgate.net/publication/220319999_A_Stochastic_Quasi-Newton_Method_for_Online_Convex_Optimization)||quasi-newton|
|Scalable training of L1-regularized log-linear models|2007|OWL-QN|[acm](https://dl.acm.org/doi/10.1145/1273496.1273501)|[code](https://github.com/langholz/owlqn)|quasi-newton|
|A Hypercube-Based Encoding for Evolving Large-Scale Neural Networks|2009|HyperNEAT|[ieee](https://ieeexplore.ieee.org/document/6792316)||evolutionary|
|AdaDiff: Adaptive Gradient Descent with the Differential of Gradient|2010|AdaDiff|[iopscience](https://iopscience.iop.org/article/10.1088/1742-6596/2010/1/012027)||gradient descent|
|Adaptive Subgradient Methods for Online Learning and Stochastic Optimization|2011|AdaGrad|[jmlr](https://jmlr.org/papers/v12/duchi11a.html)|[code](https://github.com/mlpack/ensmallen/tree/master/include/ensmallen_bits/ada_grad)|gradient descent|
|CMA-ES: evolution strategies and covariance matrix adaptation|2011|CMA-ES|[acm](https://dl.acm.org/doi/10.1145/2001858.2002123)|[code](https://github.com/srom/cma-es)|evolutionary|
|ADADELTA: An Adaptive Learning Rate Method|2012|ADADELTA|[arxiv](https://arxiv.org/abs/1212.5701v1)|[code](https://github.com/pytorch/pytorch/blob/b7bda236d18815052378c88081f64935427d7716/torch/optim/adadelta.py\#L6)|gradient descent|
|A Stochastic Gradient Method with an Exponential Convergence Rate for Finite Training Sets|2012|SAG|[arxiv](https://arxiv.org/abs/1202.6258)||variance reduced|
|An Enhanced Hypercube-Based Encoding for Evolving the Placement, Density, and Connectivity of Neurons|2012|ES-HyperNEAT|[ieee](https://ieeexplore.ieee.org/document/6792180)|[code](https://github.com/yaricom/goESHyperNEAT)|evolutionary|
|CMA-TWEANN: efficient optimization of neural networks via self-adaptation and seamless augmentation|2012|CMA-TWEANN|[acm](https://dl.acm.org/doi/abs/10.1145/2330163.2330288)||evolutionary|
|Neural Networks for Machine Learning|2012|RMSProp|[coursera](http://www.cs.toronto.edu/\~hinton/coursera/lecture6/lec6.pdf)|[code](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/python/training/rmsprop.py)|gradient descent|
|No More Pesky Learning Rates|2012|vSGD-b|[arxiv](https://arxiv.org/abs/1206.1106)|[code](https://github.com/rlowrance/vsgd)|variance reduced|
|No More Pesky Learning Rates|2012|vSGD-g|[arxiv](https://arxiv.org/abs/1206.1106)|[code](https://github.com/rlowrance/vsgd)|variance reduced|
|No More Pesky Learning Rates|2012|vSGD-l|[arxiv](https://arxiv.org/abs/1206.1106)|[code](https://github.com/rlowrance/vsgd)|variance reduced|
|Accelerating stochastic gradient descent using predictive variance reduction|2013|SVRG|[neurips](https://papers.nips.cc/paper/2013/hash/ac1dd209cbcc5e5d1c6e28598e8cbbe8-Abstract.html)|[code](https://github.com/kilianFatras/variance_reduced_neural_networks)|variance reduced|
|Adaptive learning rates and parallelization for stochastic, sparse, non-smooth gradients|2013|vSGD-fd|[arxiv](https://arxiv.org/abs/1301.3764)||gradient descent|
|Stochastic First- and Zeroth-order Methods for Nonconvex Stochastic Programming|2013|ZO-SGD|[arxiv](https://arxiv.org/abs/1309.5549)||gradient free|
|Mini-batch Stochastic Approximation Methods for Nonconvex Stochastic Composite Optimization|2013|ZO-ProxSGD|[arxiv](https://arxiv.org/abs/1308.6594)||gradient free|
|Mini-batch Stochastic Approximation Methods for Nonconvex Stochastic Composite Optimization|2013|ZO-PSGD|[arxiv](https://arxiv.org/abs/1308.6594)||gradient free|
|Semi-Stochastic Gradient Descent Methods|2013|S2GD|[arxiv](https://arxiv.org/abs/1312.1666)||variance reduced|
|Adam: A Method for Stochastic Optimization|2014|Adam|[arxiv](https://arxiv.org/abs/1412.6980)|[code](https://paperswithcode.com/paper/adam-a-method-for-stochastic-optimization)|gradient descent|
|SAGA: A Fast Incremental Gradient Method With Support for Non-Strongly Convex Composite Objectives|2014|SAGA|[arxiv](https://arxiv.org/abs/1407.0202)|[code](https://github.com/elmahdichayti/SAGA)|variance reduced|
|A Stochastic Quasi-Newton Method for Large-Scale Optimization|2014|SQN|[arxiv](https://arxiv.org/abs/1401.7020)|[code](https://github.com/keskarnitish/minSQN)|quasi-newton|
|RES: Regularized Stochastic BFGS Algorithm|2014|Reg-oBFGS-Inf|[arxiv](https://arxiv.org/abs/1401.7625)||quasi-newton|
|A Proximal Stochastic Gradient Method with Progressive Variance Reduction|2014|Prox-SVRG|[arxiv](https://arxiv.org/abs/1403.4699)|[code](https://github.com/unc-optimization/StochasticProximalMethods)|variance reduced|
|A Computationally Efficient Limited Memory CMA-ES for Large Scale Optimization|2014|LM-CMA-ES|[arxiv](https://arxiv.org/abs/1404.5520)||evolutionary|
|Random feedback weights support learning in deep neural networks|2014|FA|[arxiv](https://arxiv.org/abs/1411.0247)|[code](https://github.com/jsalbert/biotorch)|gradient descent|
|Adam: A Method for Stochastic Optimization|2015|AdaMax|[arxiv](https://arxiv.org/abs/1412.6980)|[code](https://github.com/pytorch/pytorch/blob/b7bda236d18815052378c88081f64935427d7716/torch/optim/adamax.py#L5)|gradient descent|
|Scale-Free Algorithms for Online Linear Optimization|2015|AdaFTRL|[arxiv](https://arxiv.org/abs/1502.05744)||gradient descent|
|A Linearly-Convergent Stochastic L-BFGS Algorithm|2015|SVRG-SQN|[arxiv](https://arxiv.org/abs/1508.02087)|[code](https://github.com/pcmoritz/slbfgs)|quasi-newton|
|Accelerating SVRG via second-order information|2015|SVRG+II: LBFGS|[opt](https://opt-ml.org/oldopt/opt15/papers.html)||quasi-newton|
|Accelerating SVRG via second-order information|2015|SVRG+I: Subsampled Hessian followed by SVT|[opt](https://opt-ml.org/oldopt/opt15/papers.html)||quasi-newton|
|Probabilistic Line Searches for Stochastic Optimization|2015|ProbLS|[arxiv](https://arxiv.org/abs/1502.02846)||gradient descent|
|Optimizing Neural Networks with Kronecker-factored Approximate Curvature|2015|K-FAC|[arxiv](https://arxiv.org/abs/1503.05671)|[code](https://github.com/tensorflow/kfac)|gradient descent|
|adaQN: An Adaptive Quasi-Newton Algorithm for Training RNNs|2015|adaQN|[arxiv](https://arxiv.org/abs/1511.01169)|[code](https://github.com/david-cortes/stochQN)|quasi-newton|
|Stochastic Quasi-Newton Methods for Nonconvex Stochastic Optimization|2016|Damp-oBFGS-Inf|[arxiv](https://arxiv.org/abs/1607.01231)|[code](https://github.com/harryliew/SdLBFGS)|quasi-newton|
|Eve: A Gradient Based Optimization Method with Locally and Globally Adaptive Learning Rates|2016|Eve|[arxiv](https://arxiv.org/abs/1611.01505)|[code](https://github.com/K2OTO/Eve)|gradient descent|
|Incorporating Nesterov Momentum into Adam|2016|Nadam|[openreview](https://openreview.net/forum\?id\=OM0jvwB8jIp57ZJjtNEZ)|[code](https://github.com/rwightman/pytorch-image-models/blob/master/timm/optim/nadam.py)|gradient descent|
|The Whale Optimization Algorithm|2016|WOA|[sciencedirect](https://www.sciencedirect.com/science/article/abs/pii/S0965997816300163)|[code](https://github.com/docwza/woa)|evolutionary|
|Adaptive Learning Rate via Covariance Matrix Based Preconditioning for Deep Neural Networks|2016|SDProp|[arxiv](https://arxiv.org/abs/1605.09593)||gradient descent|
|Barzilai-Borwein Step Size for Stochastic Gradient Descent|2016|SGD-BB|[arxiv](https://arxiv.org/abs/1605.04131)|[code](https://github.com/tanconghui/Stochastic_BB)|gradient descent|
|Barzilai-Borwein Step Size for Stochastic Gradient Descent|2016|SVRG-BB|[arxiv](https://arxiv.org/abs/1605.04131)|[code](https://github.com/tanconghui/Stochastic_BB)|variance reduced|
|SGDR: Stochastic Gradient Descent with Warm Restarts|2016|SGDR|[arxiv](https://arxiv.org/abs/1608.03983)|[code](https://github.com/loshchil/SGDR)|gradient descent|
|Katyusha: The First Direct Acceleration of Stochastic Gradient Methods|2016|Katyusha|[arxiv](https://arxiv.org/abs/1603.05953)||variance reduced|
|A Comprehensive Linear Speedup Analysis for Asynchronous Stochastic Parallel Optimization from Zeroth-Order to First-Order|2016|ZO-SCD|[arxiv](https://arxiv.org/abs/1606.00498)||gradient free|
|Direct Feedback Alignment Provides Learning in Deep Neural Networks|2016|DFA|[arxiv](https://arxiv.org/abs/1609.01596)|[code](https://github.com/metataro/DirectFeedbackAlignment)|gradient descent|
|AdaBatch: Adaptive Batch Sizes for Training Deep Neural Networks|2017|AdaBatch|[arxiv](https://arxiv.org/abs/1712.02029)|[code](https://github.com/GXU-GMU-MICCAI/AdaBatch-numerical-experiments)|gradient descent|
|AdaComp : Adaptive Residual Gradient Compression for Data-Parallel Distributed Training|2017|AdaComp|[arxiv](https://arxiv.org/abs/1712.02679)||gradient descent|
|SARAH: A Novel Method for Machine Learning Problems Using Stochastic Recursive Gradient|2017|SARAH|[arxiv](https://arxiv.org/abs/1703.00102)||variance reduced|
|Sub-sampled Cubic Regularization for Non-convex Optimization|2017|SCR|[arxiv](https://arxiv.org/abs/1705.05933)|[code](https://github.com/dalab/subsampled_cubic_regularization)|inexact hessian|
|IQN: An Incremental Quasi-Newton Method with Local Superlinear Convergence Rate|2017|IQN|[arxiv](https://arxiv.org/abs/1702.00709)|[code](https://github.com/mlpack/ensmallen/tree/master/include/ensmallen_bits/iqn)|quasi-newton|
|Decoupled Weight Decay Regularization|2017|AdamW|[arxiv](https://arxiv.org/abs/1711.05101)|[code](https://github.com/loshchil/AdamW-and-SGDW)|gradient descent|
|Decoupled Weight Decay Regularization|2017|SGDW|[arxiv](https://arxiv.org/abs/1711.05101)|[code](https://github.com/loshchil/AdamW-and-SGDW)|gradient descent|
|BPGrad: Towards Global Optimality in Deep Learning via Branch and Pruning|2017|BPGrad|[arxiv](https://arxiv.org/abs/1711.06959)|[code](https://github.com/RyanCV/BPGrad)|gradient descent|
|Training Deep Networks without Learning Rates Through Coin Betting|2017|COCOB|[arxiv](https://arxiv.org/abs/1705.07795)|[code](https://github.com/bremen79/cocob)|gradient descent|
|Practical Gauss-Newton Optimisation for Deep Learning|2017|KFLR|[arxiv](https://arxiv.org/abs/1706.03662)||gradient descent|
|Practical Gauss-Newton Optimisation for Deep Learning|2017|KFRA|[arxiv](https://arxiv.org/abs/1706.03662)||gradient descent|
|Large Batch Training of Convolutional Networks|2017|LARS|[arxiv](https://arxiv.org/abs/1708.03888)|[code](https://github.com/noahgolmant/pytorch-lars)|gradient descent|
|Dissecting Adam: The Sign, Magnitude and Variance of Stochastic Gradients|2017|M-SVAG|[arxiv](https://arxiv.org/abs/1705.07774)|[code](https://github.com/lballes/msvag)|gradient descent|
|Normalized Direction-preserving Adam|2017|ND-Adam|[arxiv](https://arxiv.org/abs/1709.04546)|[code](https://github.com/zj10/ND-Adam)|gradient descent|
|Noisy Natural Gradient as Variational Inference|2017|Noisy Adam|[arxiv](https://arxiv.org/abs/1712.02390)|[code](https://github.com/gd-zhang/noisy-K-FAC)|gradient descent|
|Noisy Natural Gradient as Variational Inference|2017|Noisy K-FAC|[arxiv](https://arxiv.org/abs/1712.02390)|[code](https://github.com/gd-zhang/noisy-K-FAC)|gradient descent|
|Evolving Deep Neural Networks|2017|CoDeepNEAT|[arxiv](https://arxiv.org/abs/1703.00548)|[code](https://github.com/sbcblab/Keras-CoDeepNEAT)|evolutionary|
|Evolving Deep Convolutional Neural Networks for Image Classification|2017|EvoCNN|[arxiv](https://arxiv.org/abs/1710.10741)|[code](https://github.com/MagnusCaligo/EvoCNN)|evolutionary|
|NMODE --- Neuro-MODule Evolution|2017|NMODE|[arxiv](https://arxiv.org/abs/1701.05121)|[code](https://github.com/kzahedi/NMODE)|evolutionary|
|Online Convex Optimization with Unconstrained Domains and Losses|2017|RescaledExp|[arxiv](https://arxiv.org/abs/1703.02622)||gradient descent|
|Variants of RMSProp and Adagrad with Logarithmic Regret Bounds|2017|SC-Adagrad|[arxiv](https://arxiv.org/abs/1706.05507)|[code](https://github.com/mmahesh/variants-of-rmsprop-and-adagrad)|gradient descent|
|Variants of RMSProp and Adagrad with Logarithmic Regret Bounds|2017|SC-RMSProp|[arxiv](https://arxiv.org/abs/1706.05507)|[code](https://github.com/mmahesh/variants-of-rmsprop-and-adagrad)|gradient descent|
|Improving Generalization Performance by Switching from Adam to SGD|2017|SWATS|[arxiv](https://arxiv.org/abs/1712.07628)|[code](https://github.com/Mrpatekful/swats)|gradient descent|
|YellowFin and the Art of Momentum Tuning|2017|YellowFin|[arxiv](https://arxiv.org/abs/1706.03471)|[code](https://github.com/JianGoForIt/YellowFin)|gradient descent|
|Natasha 2: Faster Non-Convex Optimization Than SGD|2017|Natasha2|[arxiv](https://arxiv.org/abs/1708.08694)||gradient descent|
|Natasha 2: Faster Non-Convex Optimization Than SGD|2017|Natasha1.5|[arxiv](https://arxiv.org/abs/1708.08694)||gradient descent|
|Regularizing and Optimizing LSTM Language Models|2017|NT-ASGD|[arxiv](https://arxiv.org/abs/1708.02182)|[code](https://github.com/salesforce/awd-lstm-lm)|gradient descent|
|SW-SGD: The Sliding Window Stochastic Gradient Descent Algorithm|2017|SW-SGD|[sciencedirect](https://www.sciencedirect.com/science/article/pii/S1877050917306221)||gradient descent|
|Adafactor: Adaptive Learning Rates with Sublinear Memory Cost|2018|Adafactor|[arxiv](https://arxiv.org/abs/1804.04235)|[code](https://github.com/DeadAt0m/adafactor-pytorch)|gradient descent|
|Quasi-hyperbolic momentum and Adam for deep learning|2018|QHAdam|[arxiv](https://arxiv.org/abs/1810.06801)|[code](https://github.com/facebookresearch/qhoptim)|gradient descent|
|Online Adaptive Methods, Universality and Acceleration|2018|AcceleGrad|[arxiv](https://arxiv.org/abs/1809.02864)||gradient descent|
|Bayesian filtering unifies adaptive and non-adaptive neural network optimization methods|2018|AdaBayes|[arxiv](https://arxiv.org/abs/1807.07540)|[code](https://github.com/LaurenceA/adabayes)|gradient descent|
|On the Convergence of A Class of Adam-Type Algorithms for Non-Convex Optimization|2018|AdaFom|[arxiv](https://arxiv.org/abs/1808.02941)||gradient descent|
|Fast Approximate Natural Gradient Descent in a Kronecker-factored Eigenbasis|2018|EKFAC|[arxiv](https://arxiv.org/abs/1806.03884)|[code](https://github.com/Thrandis/EKFAC-pytorch)|gradient descent|
|AdaShift: Decorrelation and Convergence of Adaptive Learning Rate Methods|2018|AdaShift|[arxiv](https://arxiv.org/abs/1810.00143)|[code](https://github.com/MichaelKonobeev/adashift)|gradient descent|
|Practical Bayesian Learning of Neural Networks via Adaptive Optimisation Methods|2018|BADAM|[arxiv](https://arxiv.org/abs/1811.03679)|[code](https://github.com/skezle/BADAM)|gradient descent|
|Small steps and giant leaps: Minimal Newton solvers for Deep Learning|2018|Curveball|[arxiv](https://arxiv.org/abs/1805.08095)|[code](https://github.com/jotaf98/curveball)|gradient descent|
|GADAM: Genetic-Evolutionary ADAM for Deep Neural Network Optimization|2018|GADAM|[arxiv](https://arxiv.org/abs/1805.07500)||gradient descent|
|HyperAdam: A Learnable Task-Adaptive Adam for Network Training|2018|HyperAdam|[arxiv](https://arxiv.org/abs/1811.08996)|[code](https://github.com/ShipengWang/HyperAdam)|gradient descent|
|L4: Practical loss-based stepsize adaptation for deep learning|2018|L4Adam|[arxiv](https://arxiv.org/abs/1802.05074)|[code](https://github.com/martius-lab/l4-optimizer)|gradient descent|
|L4: Practical loss-based stepsize adaptation for deep learning|2018|L4Momentum|[arxiv](https://arxiv.org/abs/1802.05074)|[code](https://github.com/martius-lab/l4-optimizer)|gradient descent|
|Nostalgic Adam: Weighting more of the past gradients when designing the adaptive learning rate|2018|NosAdam|[arxiv](https://arxiv.org/abs/1805.07557)|[code](https://github.com/andrehuang/NostalgicAdam-NosAdam)|gradient descent|
|Closing the Generalization Gap of Adaptive Gradient Methods in Training Deep Neural Networks|2018|Padam|[arxiv](https://arxiv.org/abs/1806.06763)|[code](https://github.com/uclaml/Padam)|gradient descent|
|Quasi-hyperbolic momentum and Adam for deep learning|2018|QHM|[arxiv](https://arxiv.org/abs/1810.06801)|[code](https://github.com/facebookresearch/qhoptim)|gradient descent|
|Optimal Adaptive and Accelerated Stochastic Gradient Descent|2018|A2GradExp|[arxiv](https://arxiv.org/abs/1810.00553)|[code](https://github.com/severilov/A2Grad_optimizer)|gradient descent|
|Optimal Adaptive and Accelerated Stochastic Gradient Descent|2018|A2GradInc|[arxiv](https://arxiv.org/abs/1810.00553)|[code](https://github.com/severilov/A2Grad_optimizer)|gradient descent|
|Optimal Adaptive and Accelerated Stochastic Gradient Descent|2018|A2GradUni|[arxiv](https://arxiv.org/abs/1810.00553)|[code](https://github.com/severilov/A2Grad_optimizer)|gradient descent|
|Shampoo: Preconditioned Stochastic Tensor Optimization|2018|Shampoo|[arxiv](https://arxiv.org/abs/1802.09568)|[code](https://github.com/Daniil-Selikhanovych/Shampoo_optimizer)|gradient descent|
|signSGD: Compressed Optimisation for Non-Convex Problems|2018|signSGD|[arxiv](https://arxiv.org/abs/1802.04434)|[code](https://github.com/jxbz/signSGD)|gradient descent|
|Fast and Scalable Bayesian Deep Learning by Weight-Perturbation in Adam|2018|VAdam|[arxiv](https://arxiv.org/abs/1806.04854)|[code](https://github.com/emtiyaz/vadam)|gradient descent|
|VR-SGD: A Simple Stochastic Variance Reduction Method for Machine Learning|2018|VR-SGD|[arxiv](https://arxiv.org/abs/1802.09932)|[code](https://github.com/jnhujnhu/VR-SGD)|gradient descent|
|WNGrad: Learn the Learning Rate in Gradient Descent|2018|WNGrad|[arxiv](https://arxiv.org/abs/1803.02865)|[code](https://github.com/mlpack/ensmallen/tree/master/include/ensmallen_bits/wn_grad)|gradient descent|
|Adaptive Methods for Nonconvex Optimization|2018|Yogi|[neurips](https://papers.nips.cc/paper/2018/hash/90365351ccc7437a1309dc64e4db32a3-Abstract.html)|[code](https://github.com/4rtemi5/Yogi-Optimizer_Keras)|gradient descent|
|First-order Stochastic Algorithms for Escaping From Saddle Points in Almost Linear Time|2018|NEON|[arxiv](https://arxiv.org/abs/1711.01944)||gradient descent|
|Katyusha X: Practical Momentum Method for Stochastic Sum-of-Nonconvex Optimization|2018|Katyusha X|[arxiv](https://arxiv.org/abs/1802.03866)||variance reduced|
|PSA-CMA-ES: CMA-ES with population size adaptation|2018|PSA-CMA-ES|[acm](https://dl.acm.org/doi/10.1145/3205455.3205467)||evolutionary|
|AdaGrad Stepsizes: Sharp Convergence Over Nonconvex Landscapes|2018|AdaGrad-Norm|[arxiv](https://arxiv.org/abs/1806.01811)|[code](https://github.com/xwuShirley/pytorch/blob/master/torch/optim/adagradnorm.py)|gradient descent|
|Aggregated Momentum: Stability Through Passive Damping|2018|AggMo|[arxiv](https://arxiv.org/abs/1804.00325)|[code](https://github.com/AtheMathmo/AggMo)|gradient descent|
|Accelerating SGD with momentum for over-parameterized learning|2018|MaSS|[arxiv](https://arxiv.org/abs/1810.13395)|[code](https://github.com/ts66395/MaSS)|gradient descent|
|SADAGRAD: Strongly Adaptive Stochastic Gradient Methods|2018|SADAGRAD|[mlr](http://proceedings.mlr.press/v80/chen18m.html)||gradient descent|
|Deep Frank-Wolfe For Neural Network Optimization|2018|DFW|[arxiv](https://arxiv.org/abs/1811.07591)|[code](https://github.com/oval-group/dfw)|gradient descent|
|On the Convergence of AdaGrad with Momentum for Training Deep Neural Networks|2018|AdaHB|[deepai](https://deepai.org/publication/on-the-convergence-of-adagrad-with-momentum-for-training-deep-neural-networks)||gradient descent|
|On the Convergence of AdaGrad with Momentum for Training Deep Neural Networks|2018|AdaNAG|[deepai](https://deepai.org/publication/on-the-convergence-of-adagrad-with-momentum-for-training-deep-neural-networks)||gradient descent|
|Kalman Gradient Descent: Adaptive Variance Reduction in Stochastic Optimization|2018|KGD|[arxiv](https://arxiv.org/abs/1810.12273)|[code](https://github.com/jamesvuc/KGD)|gradient descent|
|On the Convergence of Adam and Beyond|2019|AMSGrad|[arxiv](https://arxiv.org/abs/1904.09237)|[code](https://github.com/pytorch/pytorch/blob/b7bda236d18815052378c88081f64935427d7716/torch/optim/adam.py#L6)|gradient descent|
|Local AdaAlter: Communication-Efficient Stochastic Gradient Descent with Adaptive Learning Rates|2019|AdaAlter|[arxiv](https://arxiv.org/abs/1911.09030)|[code](https://github.com/xcgoner/AISTATS2020-AdaAlter-GluonNLP)|gradient descent|
|Adaptive Gradient Methods with Dynamic Bound of Learning Rate|2019|AdaBound|[arxiv](https://arxiv.org/abs/1902.09843)|[code](https://github.com/Luolc/AdaBound)|gradient descent|
|Does Adam optimizer keep close to the optimal point?|2019|AdaFix|[arxiv](https://arxiv.org/abs/1911.00289)||gradient descent|
|Adaloss: Adaptive Loss Function for Landmark Localization|2019|Adaloss|[arxiv](https://arxiv.org/abs/1908.01070)||gradient descent|
|A new perspective in understanding of Adam-Type algorithms and beyond|2019|AdamAL|[openreview](https://openreview.net/forum\?id\=SyxM51BYPB)|[code](https://www.dropbox.com/s/qgqhg6znuimzci9/adamAL.py\?dl\=0)|gradient descent|
|On the Convergence of Adam and Beyond|2019|AdamNC|[arxiv](https://arxiv.org/abs/1904.09237)||gradient descent|
|Lookahead Optimizer: k steps forward, 1 step back|2019|Lookahead|[arxiv](https://arxiv.org/abs/1907.08610)|[code](https://github.com/michaelrzhang/lookahead)|gradient descent|
|On Higher-order Moments in Adam|2019|HAdam|[arxiv](https://arxiv.org/abs/1910.06878)||gradient descent|
|An Adaptive and Momental Bound Method for Stochastic Learning|2019|AdaMod|[arxiv](https://arxiv.org/abs/1910.12249)|[code](https://github.com/lancopku/AdaMod)|gradient descent|
|On the Convergence Proof of AMSGrad and a New Version|2019|AdamX|[arxiv](https://arxiv.org/abs/1904.03590)||gradient descent|
|Second-order Information in First-order Optimization Methods|2019|AdaSqrt|[arxiv](https://arxiv.org/abs/1912.09926)|[code](https://github.com/OSI-Group/AdaSqrt)|gradient descent|
|Adathm: Adaptive Gradient Method Based on Estimates of Third-Order Moments|2019|Adathm|[ieee](https://ieeexplore.ieee.org/document/8923615)||gradient descent|
|Domain-independent Dominance of Adaptive Methods|2019|Delayed Adam|[arxiv](https://arxiv.org/abs/1912.01823)|[code](https://github.com/lolemacs/avagrad)|gradient descent|
|Domain-independent Dominance of Adaptive Methods|2019|AvaGrad|[arxiv](https://arxiv.org/abs/1912.01823)|[code](https://github.com/lolemacs/avagrad)|gradient descent|
|Painless Stochastic Gradient: Interpolation, Line-Search, and Convergence Rates|2019|ArmijoLS|[arxiv](https://arxiv.org/abs/1905.09997)|[code](https://github.com/IssamLaradji/sls)|gradient descent|
|An Adaptive Remote Stochastic Gradient Method for Training Neural Networks|2019|ARSG|[arxiv](https://arxiv.org/abs/1905.01422)|[code](https://github.com/rationalspark/NAMSG)|gradient descent|
|BGADAM: Boosting based Genetic-Evolutionary ADAM for Neural Network Optimization|2019|BGADAM|[arxiv](https://arxiv.org/abs/1908.08015)||gradient descent|
|CProp: Adaptive Learning Rate Scaling from Past Gradient Conformity|2019|CProp|[arxiv](https://arxiv.org/abs/1912.11493)|[code](https://github.com/phizaz/cprop)|gradient descent|
|DADAM: A Consensus-based Distributed Adaptive Gradient Method for Online Optimization|2019|DADAM|[arxiv](https://arxiv.org/abs/1901.09109)|[code](https://github.com/Tarzanagh/DADAM)|gradient descent|
|diffGrad: An Optimization Method for Convolutional Neural Networks|2019|diffGrad|[arxiv](https://arxiv.org/abs/1909.11015)|[code](https://github.com/shivram1987/diffGrad)|gradient descent|
|Gradient-only line searches: An Alternative to Probabilistic Line Searches|2019|GOLS-I|[arxiv](https://arxiv.org/abs/1903.09383)||gradient descent|
|Large Batch Optimization for Deep Learning: Training BERT in 76 minutes|2019|LAMB|[arxiv](https://arxiv.org/abs/1904.00962)|[code](https://github.com/tensorflow/addons/blob/master/tensorflow_addons/optimizers/lamb.py)|gradient descent|
|An Adaptive Remote Stochastic Gradient Method for Training Neural Networks|2019|NAMSB|[arxiv](https://arxiv.org/abs/1905.01422)|[code](https://github.com/rationalspark/NAMSG)|gradient descent|
|An Adaptive Remote Stochastic Gradient Method for Training Neural Networks|2019|NAMSG|[arxiv](https://arxiv.org/abs/1905.01422)|[code](https://github.com/rationalspark/NAMSG)|gradient descent|
|Stochastic Gradient Methods with Layer-wise Adaptive Moments for Training of Deep Networks|2019|Novograd|[arxiv](https://arxiv.org/abs/1905.11286)|[code](https://github.com/convergence-lab/novograd)|gradient descent|
|Fast-DENSER++: Evolving Fully-Trained Deep Artificial Neural Networks|2019|F-DENSER++|[arxiv](https://arxiv.org/abs/1905.02969)|[code](https://github.com/fillassuncao/fast-denser)|evolutionary|
|Fast DENSER: Efficient Deep NeuroEvolution|2019|F-DENSER|[researchgate](https://www.researchgate.net/publication/332306893_Fast_DENSER_Efficient_Deep_NeuroEvolution)|[code](https://github.com/fillassuncao/fast-denser)|evolutionary|
|Parabolic Approximation Line Search for DNNs|2019|PAL|[arxiv](https://arxiv.org/abs/1903.11991)|[code](https://github.com/cogsys-tuebingen/PAL)|gradient descent|
|The Role of Memory in Stochastic Optimization|2019|PolyAdam|[arxiv](https://arxiv.org/abs/1907.01678)||gradient descent|
|PowerSGD: Practical Low-Rank Gradient Compression for Distributed Optimization|2019|PowerSGD|[arxiv](https://arxiv.org/abs/1905.13727)|[code](https://github.com/epfml/powersgd)|gradient descent|
|PowerSGD: Practical Low-Rank Gradient Compression for Distributed Optimization|2019|PowerSGDM|[arxiv](https://arxiv.org/abs/1905.13727)|[code](https://github.com/epfml/powersgd)|gradient descent|
|On the Variance of the Adaptive Learning Rate and Beyond|2019|RAdam|[arxiv](https://arxiv.org/abs/1908.03265)|[code](https://github.com/LiyuanLucasLiu/RAdam)|gradient descent|
|Matrix-Free Preconditioning in Online Learning|2019|RecursiveOptimizer|[arxiv](https://arxiv.org/abs/1905.12721)|[code](https://github.com/google-research/google-research/tree/master/recursive_optimizer)|gradient descent|
|On Empirical Comparisons of Optimizers for Deep Learning|2019|RMSterov|[arxiv](https://arxiv.org/abs/1910.05446)||gradient descent|
|SAdam: A Variant of Adam for Strongly Convex Functions|2019|SAdam|[arxiv](https://arxiv.org/abs/1905.02957)|[code](https://github.com/SAdam-ICLR2020/codes)|gradient descent|
|Calibrating the Adaptive Learning Rate to Improve Convergence of ADAM|2019|Sadam|[arxiv](https://arxiv.org/abs/1908.00700)|[code](https://github.com/neilliang90/Sadam)|gradient descent|
|Calibrating the Adaptive Learning Rate to Improve Convergence of ADAM|2019|SAMSGrad|[arxiv](https://arxiv.org/abs/1908.00700)|[code](https://github.com/neilliang90/Sadam)|gradient descent|
|signADAM: Learning Confidences for Deep Neural Networks|2019|signADAM|[arxiv](https://arxiv.org/abs/1907.09008)|[code](https://github.com/DongWanginxdu/signADAM-Learn-by-Confidence)|gradient descent|
|signADAM: Learning Confidences for Deep Neural Networks|2019|signADAM++|[arxiv](https://arxiv.org/abs/1907.09008)|[code](https://github.com/DongWanginxdu/signADAM-Learn-by-Confidence)|gradient descent|
|Memory-Efficient Adaptive Optimization|2019|SM3|[arxiv](https://arxiv.org/abs/1901.11150)|[code](https://github.com/google-research/google-research/tree/master/sm3)|gradient descent|
|Momentum-Based Variance Reduction in Non-Convex SGD|2019|STORM|[arxiv](https://arxiv.org/abs/1905.10018)|[code](https://github.com/google-research/google-research/tree/master/storm_optimizer)|gradeint descent|
|ZO-AdaMM: Zeroth-Order Adaptive Momentum Method for Black-Box Optimization|2019|ZO-AdaMM|[arxiv](https://arxiv.org/abs/1910.06513)|[code](https://github.com/KaidiXu/ZO-AdaMM)|gradient free|
|signSGD via Zeroth-Order Oracle|2019|ZO-signSGD|[openreview](https://openreview.net/forum\?id\=BJe-DsC5Fm)||gradient free|
|Demon: Improved Neural Network Training with Momentum Decay|2019|Demon SGDM|[arxiv](https://arxiv.org/abs/1910.04952)|[code](https://github.com/autasi/demon_sgd)|gradient descent|
|Demon: Improved Neural Network Training with Momentum Decay|2019|Demon Adam|[arxiv](https://arxiv.org/abs/1910.04952)|[code](https://github.com/autasi/demon_sgd)|gradient descent|
|An Optimistic Acceleration of AMSGrad for Nonconvex Optimization|2019|OPT-AMSGrad|[arxiv](https://arxiv.org/abs/1903.01435)||gradient descent|
|UniXGrad: A Universal, Adaptive Algorithm with Optimal Guarantees for Constrained Optimization|2019|UniXGrad|[arxiv](https://arxiv.org/abs/1910.13857)||gradient descent|
|An Adaptive Optimization Algorithm Based on Hybrid Power and Multidimensional Update Strategy|2019|AdaHMG|[ieee](https://ieeexplore.ieee.org/abstract/document/8635473)||gradient descent|
|ProxSGD: Training Structured Neural Networks under Regularization and Constraints|2019|ProxSGD|[openreview](https://openreview.net/forum\?id\=HygpthEtvr)|[code](https://github.com/optyang/proxsgd)|gradient descent|
|Efficient Learning Rate Adaptation for Convolutional Neural Network Training|2019|e-AdLR|[ieee](https://ieeexplore.ieee.org/abstract/document/8852033)||gradient descent|
|AdaBelief Optimizer: Adapting Stepsizes by the Belief in Observed Gradients|2020|AdaBelief|[arxiv](https://arxiv.org/abs/2010.07468)|[code](https://github.com/juntang-zhuang/Adabelief-Optimizer)|gradient descent|
|ADAHESSIAN: An Adaptive Second Order Optimizer for Machine Learning|2020|ADAHESSIAN|[arxiv](https://arxiv.org/abs/2006.00719)|[code](https://github.com/amirgholami/adahessian)|gradient descent|
|Adai: Separating the Effects of Adaptive Learning Rate and Momentum Inertia|2020|Adai|[arxiv](https://arxiv.org/abs/2006.15815)|[code](https://github.com/zeke-xie/adaptive-inertia-adai)|gradient descent|
|Adam<sup>+</sup>: A Stochastic Method with Adaptive Variance Reduction|2020|Adam<sup>+</sup>|[arxiv](https://arxiv.org/abs/2011.11985)||gradient descent|
|Adam with Bandit Sampling for Deep Learning|2020|Adambs|[arxiv](https://arxiv.org/abs/2010.12986)|[code](https://github.com/forestliurui/Adam-with-Bandit-Sampling)|gradient descent|
|Why are Adaptive Methods Good for Attention Models?|2020|ACClip|[arxiv](https://arxiv.org/abs/1912.03194)||gradient descent|
|AdamP: Slowing Down the Slowdown for Momentum Optimizers on Scale-invariant Weights|2020|AdamP|[arxiv](https://arxiv.org/abs/2006.08217)|[code](https://github.com/clovaai/AdamP)|gradient descent|
|On the Trend-corrected Variant of Adaptive Stochastic Optimization Methods|2020|AdamT|[arxiv](https://arxiv.org/abs/2001.06130)|[code](https://github.com/xuebin-zh/AdamT)|gradient descent|
|AdaS: Adaptive Scheduling of Stochastic Gradients|2020|AdaS|[arxiv](https://arxiv.org/abs/2006.06587)|[code](https://github.com/mahdihosseini/AdaS)|gradient descent|
|AdaScale SGD: A User-Friendly Algorithm for Distributed Training|2020|AdaScale|[arxiv](https://arxiv.org/abs/2007.05105)||gradient descent|
|AdaSGD: Bridging the gap between SGD and Adam|2020|AdaSGD|[arxiv](https://arxiv.org/abs/2006.16541)||gradient descent|
|AdaX: Adaptive Gradient Descent with Exponential Long Term Memory|2020|AdaX|[arxiv](https://arxiv.org/abs/2004.09740)|[code](https://github.com/switchablenorms/AdaX)|gradient descent|
|AdaX: Adaptive Gradient Descent with Exponential Long Term Memory|2020|AdaX-W|[arxiv](https://arxiv.org/abs/2004.09740)|[code](https://github.com/switchablenorms/AdaX)|gradient descent|
|AEGD: Adaptive Gradient Descent with Energy|2020|AEGD|[arxiv](https://arxiv.org/abs/2010.05109)|[code](https://github.com/txping/AEGD)|gradient descent|
|Biased Stochastic Gradient Descent for Conditional Stochastic Optimization|2020|BSGD|[arxiv](https://arxiv.org/abs/2002.10790)||gradient descent|
|Compositional ADAM: An Adaptive Compositional Solver|2020|C-ADAM|[arxiv](https://arxiv.org/abs/2002.03755)||gradient descent|
|CADA: Communication-Adaptive Distributed Adam|2020|CADA|[arxiv](https://arxiv.org/abs/2012.15469)|[code](https://github.com/ChrisYZZ/CADA-master)|gradient descent|
|CoolMomentum: A Method for Stochastic Optimization by Langevin Dynamics with Simulated Annealing|2020|CoolMomentum|[arxiv](https://arxiv.org/abs/2005.14605)|[code](https://github.com/borbysh/coolmomentum)|gradient descent|
|EAdam Optimizer: How ε Impact Adam|2020|EAdam|[arxiv](https://arxiv.org/abs/2011.02150)|[code](https://github.com/yuanwei2019/EAdam-optimizer)|gradient descent|
|Expectigrad: Fast Stochastic Optimization with Robust Convergence Properties|2020|Expectigrad|[arxiv](https://arxiv.org/abs/2010.01356)|[code](https://github.com/brett-daley/expectigrad)|gradient descent|
|Stochastic Gradient Descent with Nonlinear Conjugate Gradient-Style Adaptive Momentum|2020|FRSGD|[arxiv](https://arxiv.org/abs/2012.02188)||gradient descent|
|Iterative Averaging in the Quest for Best Test Error|2020|Gadam|[arxiv](https://arxiv.org/abs/2003.01247)||gradient descent|
|A Variant of Gradient Descent Algorithm Based on Gradient Averaging|2020|Grad-Avg|[arxiv](https://arxiv.org/abs/2012.02387)||gradient descent|
|Gravilon: Applications of a New Gradient Descent Method to Machine Learning|2020|Gravilon|[arxiv](https://arxiv.org/abs/2008.11370)||gradient descent|
|Practical Quasi-Newton Methods for Training Deep Neural Networks|2020|K-BFGS|[arxiv](https://arxiv.org/abs/2006.08877)|[code](https://github.com/renyiryry/kbfgs_neurips2020_public)|gradient descent|
|Practical Quasi-Newton Methods for Training Deep Neural Networks|2020|K-BFGS(L)|[arxiv](https://arxiv.org/abs/2006.08877)|[code](https://github.com/renyiryry/kbfgs_neurips2020_public)|gradient descent|
|LaProp: Separating Momentum and Adaptivity in Adam|2020|LaProp|[arxiv](https://arxiv.org/abs/2002.04839)|[code](https://github.com/Z-T-WANG/LaProp-Optimizer)|gradient descent|
|Mixing ADAM and SGD: a Combined Optimization Method|2020|MAS|[arxiv](https://arxiv.org/abs/2011.08042)|[code](https://gitlab.com/nicolalandro/multi_optimizer)|gradient descent|
|Self-Tuning Stochastic Optimization with Curvature-Aware Gradient Filtering|2020|MEKA|[arxiv](https://arxiv.org/abs/2011.04803)||gradient descent|
|MTAdam: Automatic Balancing of Multiple Training Loss Terms|2020|MTAdam|[arxiv](https://arxiv.org/abs/2006.14683)|[code](https://github.com/ItzikMalkiel/MTAdam)|gradient descent|
|Momentum with Variance Reduction for Nonconvex Composition Optimization|2020|MVRC-1|[arxiv](https://arxiv.org/abs/2005.07755)||gradient descent|
|Momentum with Variance Reduction for Nonconvex Composition Optimization|2020|MVRC-2|[arxiv](https://arxiv.org/abs/2005.07755)||gradient descent|
|PAGE: A Simple and Optimal Probabilistic Gradient Estimator for Nonconvex Optimization|2020|PAGE|[arxiv](https://arxiv.org/abs/2008.10898)||gradient descent|
|Momentum-based variance-reduced proximal stochastic gradient method for composite nonconvex stochastic optimization|2020|PSTorm|[arxiv](https://arxiv.org/abs/2006.00425)||gradient descent|
|Ranger-Deep-Learning-Optimizer|2020|Ranger|[github](https://github.com/lessw2020/Ranger-Deep-Learning-Optimizer)|[code](https://github.com/lessw2020/Ranger-Deep-Learning-Optimizer)|gradient descent|
|Gradient Centralization: A New Optimization Technique for Deep Neural Networks|2020|GC|[arxiv](https://arxiv.org/abs/2004.01461)|[code](https://github.com/Yonghongwei/Gradient-Centralization)|gradient descent|
|S-SGD: Symmetrical Stochastic Gradient Descent with Weight Noise Injection for Reaching Flat Minima|2020|S-SGD|[arxiv](https://arxiv.org/abs/2009.02479)||gradient descent|
|SALR: Sharpness-aware Learning Rate Scheduler for Improved Generalization|2020|SALR|[arxiv](https://arxiv.org/abs/2011.05348)||gradient descent|
|Sharpness-aware Minimization for Efficiently Improving Generalization|2020|SAM|[arxiv](https://arxiv.org/abs/2010.01412)|[code](https://github.com/google-research/sam)|gradient descent|
|Stochastic Runge-Kutta methods and adaptive SGD-G2 stochastic gradient descent|2020|SGD-G2|[arxiv](https://arxiv.org/abs/2002.09304)||gradient descent|
|A New Accelerated Stochastic Gradient Method with Momentum|2020|SGDM|[arxiv](https://arxiv.org/abs/2006.00423)||gradient descent|
|Scheduled Restart Momentum for Accelerated Stochastic Gradient Descent|2020|SRSGD|[arxiv](https://arxiv.org/abs/2002.10583)|[code](https://github.com/minhtannguyen/SRSGD)|gradient descent|
|Adaptive Gradient Methods Can Be Provably Faster than SGD after Finite Epochs|2020|SHAdaGrad|[arxiv](https://arxiv.org/abs/2006.07037)||gradient descent|
|Enhance Curvature Information by Structured Stochastic Quasi-Newton Methods|2020|SKQN|[arxiv](https://arxiv.org/abs/2006.09606)||gradient descent|
|Enhance Curvature Information by Structured Stochastic Quasi-Newton Methods|2020|S4QN|[arxiv](https://arxiv.org/abs/2006.09606)||gradient descent|
|SMG: A Shuffling Gradient-Based Method with Momentum|2020|SMG|[arxiv](https://arxiv.org/abs/2011.11884)||gradient descent|
|Stochastic Normalized Gradient Descent with Momentum for Large Batch Training|2020|SNGM|[arxiv](https://arxiv.org/abs/2007.13985)||gradient descent|
|TAdam: A Robust Stochastic Gradient Optimizer|2020|TAdam|[arxiv](https://arxiv.org/abs/2003.00179)|[code](https://github.com/Mahoumaru/TAdam)|gradient descent|
|Eigenvalue-corrected Natural Gradient Based on a New Approximation|2020|TEKFAC|[arxiv](https://arxiv.org/abs/2011.13609)||gradient descent|
|pbSGD: Powered Stochastic Gradient Descent Methods for Accelerated Non-Convex Optimization|2020|pbSGD|[ijcai](https://www.ijcai.org/proceedings/2020/451)|[code](https://github.com/HAIRLAB/pbSGD)|gradient descent|
|Apollo: An Adaptive Parameter-wise Diagonal Quasi-Newton Method for Nonconvex Stochastic Optimization|2020|Apollo|[arxiv](https://arxiv.org/abs/2009.13586)|[code](https://github.com/XuezheMax/apollo)|quasi-newton|
|Apollo: An Adaptive Parameter-wise Diagonal Quasi-Newton Method for Nonconvex Stochastic Optimization|2020|ApolloW|[arxiv](https://arxiv.org/abs/2009.13586)|[code](https://github.com/XuezheMax/apollo)|quasi-newton|
|Slime mould algorithm: A new method for stochastic optimization|2020|SMA|[sciencedirect](https://www.sciencedirect.com/science/article/abs/pii/S0167739X19320941)|[code](http://mdm.wzu.edu.cn/SMA.html)|evolutionary|
|AdaSwarm: Augmenting Gradient-Based optimizers in Deep Learning with Swarm Intelligence|2020|AdaSwarm|[arxiv](https://arxiv.org/abs/2006.09875)|[code](https://github.com/anuwu/PSO-Stuff)|evolutionary|
|Adaptive Gradient Methods for Constrained Convex Optimization and Variational Inequalities|2020|AdaACSA|[arxiv](https://arxiv.org/abs/2007.08840)||gradient descent|
|Adaptive Gradient Methods for Constrained Convex Optimization and Variational Inequalities|2020|AdaAGD+|[arxiv](https://arxiv.org/abs/2007.08840)||gradient descent|
|SCW-SGD: Stochastically Confidence-Weighted SGD|2020|SCWSGD|[ieee](https://ieeexplore.ieee.org/abstract/document/9190992)||gradient descent|
|An Improved Adaptive Optimization Technique for Image Classification|2020|Mean-ADAM|[ieee](https://ieeexplore.ieee.org/abstract/document/9306620)||gradient descent|
|Towards Better Generalization of Adaptive Gradient Methods|2020|SAGD|[neurips](https://proceedings.neurips.cc/paper/2020/hash/08fb104b0f2f838f3ce2d2b3741a12c2-Abstract.html)||gradient descent|
|Stochastic Approximate Gradient Descent via the Langevin Algorithm|2020|SAGD|[arxiv](https://arxiv.org/abs/2002.05519)||gradient descent|
|Gravity Optimizer: a Kinematic Approach on Optimization in Deep Learning|2021|Gravity|[arxiv](https://arxiv.org/abs/2101.09192)|[code](https://github.com/dariush-bahrami/gravity.optimizer)|gradient descent|
|Comment on Stochastic Polyak Step-Size: Performance of ALI-G|2021|ALI-G|[arxiv](https://arxiv.org/abs/2105.10011)||gradient descent|
|Random-reshuffled SARAH does not need a full gradient computations|2021|Shuffled-SARAH|[arxiv](https://arxiv.org/abs/2111.13322)||variance reduction|
|SUPER-ADAM: Faster and Universal Framework of Adaptive Gradients|2021|SUPER-ADAM|[arxiv](https://arxiv.org/abs/2106.08208)|[code](https://github.com/lijunyi95/superadam)|gradient descent|
|Faster Perturbed Stochastic Gradient Methods for Finding Local Minima|2021|Pullback|[arxiv](https://arxiv.org/abs/2110.13144)||perturbed gradient|
|AngularGrad: A New Optimization Technique for Angular Convergence of Convolutional Neural Networks|2021|AngularGrad|[arxiv](https://arxiv.org/abs/2105.10190)|[code](https://github.com/mhaut/AngularGrad)|gradient descent|
|ASAM: Adaptive Sharpness-Aware Minimization for Scale-Invariant Learning of Deep Neural Networks|2021|ASAM|[arxiv](https://arxiv.org/abs/2102.11600)|[code](https://github.com/SamsungLabs/ASAM)|gradient descent|
|AutoLRS: Automatic Learning-Rate Schedule by Bayesian Optimization on the Fly|2021|AutoLRS|[arxiv](https://arxiv.org/abs/2105.10762)|[code](https://github.com/YuchenJin/autolrs)|gradient descent|
|FastAdaBelief: Improving Convergence Rate for Belief-based Adaptive Optimizers by Exploiting Strong Convexity|2021|FastAdaBelief|[arxiv](https://arxiv.org/abs/2104.13790)||gradient descent|
|Generalized AdaGrad (G-AdaGrad) and Adam: A State-Space Perspective|2021|G-AdaGrad|[arxiv](https://arxiv.org/abs/2106.00092)||gradient descent|
|GOALS: Gradient-Only Approximations for Line Searches Towards Robust and Consistent Training of Deep Neural Networks|2021|GOALS|[arxiv](https://arxiv.org/abs/2105.10915)||gradient descent|
|Learning in Deep Neural Networks Using a Biologically Inspired Optimizer|2021|GRAPES|[arxiv](https://arxiv.org/abs/2104.11604)||gradient descent|
|Kronecker-factored Quasi-Newton Methods for Convolutional Neural Networks|2021|KF-QN-CNN|[arxiv](https://arxiv.org/abs/2102.06737)||gradient descent|
|A Generalizable Approach to Learning Optimizers|2021|LHOPT|[arxiv](https://arxiv.org/abs/2106.00958)|[code](https://github.com/openai/LHOPT)|gradient descent|
|Adaptivity without Compromise: A Momentumized, Adaptive, Dual Averaged Gradient Method for Stochastic Optimization|2021|MADGRAD|[arxiv](https://arxiv.org/abs/2101.11075)|[code](https://github.com/facebookresearch/madgrad)|gradient descent|
|Learning by Turning: Neural Architecture Aware Optimisation|2021|Nero|[arxiv](https://arxiv.org/abs/2102.07227)|[code](https://github.com/jxbz/nero)|gradient descent|
|Noisy Truncated SGD: Optimization and Generalization|2021|NT-SGD|[arxiv](https://arxiv.org/abs/2103.00075)||gradient descent|
|A Probabilistically Motivated Learning Rate Adaptation for Stochastic Optimization|2021|Probabilistic Polyak|[arxiv](https://arxiv.org/abs/2102.10880)||gradient descent|
|Ranger21 - integrating the latest deep learning components into a single optimizer|2021|Ranger21|[github](https://github.com/lessw2020/Ranger21)|[code](https://github.com/lessw2020/Ranger21)|gradient descent|
|On the Generalization of Stochastic Gradient Descent with Momentum|2021|SGDEM|[arxiv](https://arxiv.org/abs/2102.13653)||gradient descent|
|Positive-Negative Momentum: Manipulating Stochastic Gradient Noise to Improve Generalization|2021|PNM|[arxiv](https://arxiv.org/abs/2103.17182)|[code](https://github.com/zeke-xie/Positive-Negative-Momentum)|gradient descent|
|Positive-Negative Momentum: Manipulating Stochastic Gradient Noise to Improve Generalization|2021|AdaPNM|[arxiv](https://arxiv.org/abs/2103.17182)|[code](https://github.com/zeke-xie/Positive-Negative-Momentum)|gradient descent|
|Better SGD using Second-order Momentum|2021|SGDHess|[arxiv](https://arxiv.org/abs/2103.03265)|[code](https://github.com/tranhp98/SGDHess)|gradient descent|
|Second-order step-size tuning of SGD for non-convex optimization|2021|Step-Tuned SGD|[arxiv](https://arxiv.org/abs/2103.03570)|[code](https://github.com/Abdoulaye-Koroko/Second-order-step-size-tuning-of-SGD-for-non-convex-optimization)|gradient descent|
|AdamD: Improved bias-correction in Adam|2021|AdamD|[arxiv](https://arxiv.org/abs/2110.10828)|[code](https://github.com/kozistr/pytorch_optimizer)|gradient descent|
|Adaptive shot allocation for fast convergence in variational quantum algorithms|2021|gCANS|[arxiv](https://arxiv.org/abs/2108.10434)||gradient descent|
|AdaLoss: A computationally-efficient and provably convergent adaptive gradient method|2021|AdaLoss|[arxiv](https://arxiv.org/abs/2109.08282)||gradient descent|
|AdaLoss: A computationally-efficient and provably convergent adaptive gradient method|2021|AdamLoss|[arxiv](https://arxiv.org/abs/2109.08282)||gradient descent|
|STORM+: Fully Adaptive SGD with Momentum for Nonconvex Optimization|2021|STORM+|[arxiv](https://arxiv.org/abs/2111.01040)||gradient descent|
|Adadb: Adaptive Diff-Batch Optimization Technique for Gradient Descent|2021|Adadb|[ieee](https://ieeexplore.ieee.org/abstract/document/9481902)||gradient descent|
|MaxVA: Fast Adaptation of Step Sizes by Maximizing Observed Variance of Gradients|2021|MaxVA|[arxiv](https://arxiv.org/abs/2006.11918)|[code](https://github.com/zhuchen03/maxva)|gradient descent|
|A New Adaptive Gradient Method with Gradient Decomposition|2021|DecGD|[arxiv](https://arxiv.org/abs/2107.08377)||gradient descent|
|AdaL: Adaptive Gradient Transformation Contributes to Convergences and Generalizations|2021|AdaL|[arxiv](https://arxiv.org/abs/2107.01525)||gradient descent|
|AdaDB: An adaptive gradient method with data-dependent bound|2021|AdaDB|[sciencedirect](https://www.sciencedirect.com/science/article/abs/pii/S0925231220311784)|[code](https://github.com/ZJULearning/AdaDB)|gradient descent|
|Convergence of the RMSProp deep learning method with penalty for nonconvex optimization|2021|RMSPropW|[sciencedirect](https://www.sciencedirect.com/science/article/abs/pii/S0893608021000538)||gradient descent|
|AG-SGD: Angle-Based Stochastic Gradient Descent|2021|AG-SGD|[ieee](https://ieeexplore.ieee.org/abstract/document/9343305)||gradient descent|
|AdaCN: An Adaptive Cubic Newton Method for Nonconvex Stochastic Optimization|2021|AdaCN|[researchgate](https://www.researchgate.net/publication/356140884_AdaCN_An_Adaptive_Cubic_Newton_Method_for_Nonconvex_Stochastic_Optimization)||gradient descent|
|Extending AdamW by Leveraging Its Second Moment and Magnitude|2021|Aida|[arxiv](https://arxiv.org/abs/2112.06125)||gradient descent|
|Painless step size adaptation for SGD|2021|LIGHT|[arxiv](https://arxiv.org/abs/2102.00853)|[code](https://github.com/yukinoi/light-diagnostic-function)|gradient descent|
|Dynamic Game Theoretic Neural Optimizer|2021|DGNOpt|[arxiv](https://arxiv.org/abs/2105.03788)||gradient descent|
|Complex Momentum for Optimization in Games|2021|Complex Adam|[arxiv](https://arxiv.org/abs/2102.08431)||gradient descent|
|LightAdam: Towards a Fast and Accurate Adaptive Momentum Online Algorithm|2022|LightAdam|[springerlink](https://link.springer.com/article/10.1007/s12559-021-09985-9)||gradient descent|
|Step-size Adaptation Using Exponentiated Gradient Updates|2022|Funneled AdaGrad|[arxiv](https://arxiv.org/abs/2202.00145)||gradient descent|
|Nesterov Accelerated Shuffling Gradient Method for Convex Optimization|2022|NASG|[arxiv](https://arxiv.org/abs/2202.03525)||gradient descent|
|MSTGD:A Memory Stochastic sTratified Gradient Descent Method with an Exponential Convergence Rate|2022|MSTGD|[arxiv](https://arxiv.org/abs/2202.10923)||variance reduced|
|Cutting Some Slack for SGD with Adaptive Polyak Stepsizes|2022|SPSL1|[arxiv](https://arxiv.org/abs/2202.12328)||gradient descent|
|Cutting Some Slack for SGD with Adaptive Polyak Stepsizes|2022|SPSL2|[arxiv](https://arxiv.org/abs/2202.12328)||gradient descent|
|AdaFamily: A family of Adam-like adaptive gradient methods|2022|AdaFamily|[arxiv](https://arxiv.org/abs/2203.01603)||gradient descent|
|Exploiting Explainable Metrics for Augmented SGD|2022|RMSGD|[arxiv](https://arxiv.org/abs/2203.16723)|[code](https://github.com/mahdihosseini/RMSGD)|gradient descent|
|Neuroevolution-Enhanced Multi-Objective Optimization for Mixed-Precision Quantization|2022|NEMO|[arxiv](https://arxiv.org/abs/2106.07611)||evolutionary|
|Learning to Accelerate by the Methods of Step-size Planning|2022|Csawg|[arxiv](https://arxiv.org/abs/2204.01705)||gradient descent|
|High-performance Evolutionary Algorithms for Online Neuron Control|2022|SphereCMA|[arxiv](https://arxiv.org/abs/2204.06765)|[code](https://github.com/animadversio/actmax-optimizer-dev)|evolutionary|
|RankNEAT: Outperforming Stochastic Gradient Search in Preference Learning Tasks|2022|RankNEAT|[arxiv](https://arxiv.org/abs/2204.06901)||evolutionary|
|AdaTerm: Adaptive T-Distribution Estimated Robust Moments towards Noise-Robust Stochastic Gradient Optimizer|2022|AdaTerm|[arxiv](https://arxiv.org/abs/2201.06714)||gradient descent|
|Adan: Adaptive Nesterov Momentum Algorithm for Faster Optimizing Deep Models|2022|Adan|[arxiv](https://arxiv.org/abs/2208.06677)|[code](https://github.com/sail-sg/Adan)|gradient descent|