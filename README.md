# Awesome-Optimizer
Collect optimizer related papers, data, repositories

| Title                                           |  Year    | Optimizer       | Published                                  | Code                                              | Keywords                                  |
| ---------------------- | ---------------------- | ---------|-------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------|
|Some methods of speeding up the convergence of iteration methods|1964|Polyak|[sciencedirect](https://www.sciencedirect.com/science/article/abs/pii/0041555364901375)||gradient descent|
|Trust region methods|2000|Sub-sampled TR|[siam](https://epubs.siam.org/doi/book/10.1137/1.9780898719857)||inexact hessian|
|Adaptive Subgradient Methods for Online Learning and Stochastic Optimization|2011|AdaGrad|[jmlr](https://jmlr.org/papers/v12/duchi11a.html)|[code](https://github.com/mlpack/ensmallen/tree/master/include/ensmallen_bits/ada_grad)|gradient descent|
|ADADELTA: An Adaptive Learning Rate Method|2012|ADADELTA|[arxiv](https://arxiv.org/abs/1212.5701v1)|[code](https://github.com/pytorch/pytorch/blob/b7bda236d18815052378c88081f64935427d7716/torch/optim/adadelta.py\#L6)|gradient descent|
|A Stochastic Gradient Method with an Exponential Convergence Rate for Finite Training Sets|2012|SAG|[arxiv](https://arxiv.org/abs/1202.6258)||variance reduced|
|Accelerating stochastic gradient descent using predictive variance reduction|2013|SVRG|[neurips](https://papers.nips.cc/paper/2013/hash/ac1dd209cbcc5e5d1c6e28598e8cbbe8-Abstract.html)|[code](https://github.com/kilianFatras/variance_reduced_neural_networks)|variance reduced|
|Adam: A Method for Stochastic Optimization|2014|Adam|[arxiv](https://arxiv.org/abs/1412.6980)|[code](https://paperswithcode.com/paper/adam-a-method-for-stochastic-optimization)|gradient descent|
|SAGA: A Fast Incremental Gradient Method With Support for Non-Strongly Convex Composite Objectives|2014|SAGA|[arxiv](https://arxiv.org/abs/1407.0202)|[code](https://github.com/elmahdichayti/SAGA)|variance reduced|
|A Stochastic Quasi-Newton Method for Large-Scale Optimization|2014|SQN|[arxiv](https://arxiv.org/abs/1401.7020)|[code](https://github.com/keskarnitish/minSQN)|quasi-newton|
|RES: Regularized Stochastic BFGS Algorithm|2014|Reg-oBFGS-Inf|[arxiv](https://arxiv.org/abs/1401.7625)||quasi-newton|
|Adam: A Method for Stochastic Optimization|2015|AdaMax|[arxiv](https://arxiv.org/abs/1412.6980)|[code](https://github.com/pytorch/pytorch/blob/b7bda236d18815052378c88081f64935427d7716/torch/optim/adamax.py#L5)|gradient descent|
|Scale-Free Algorithms for Online Linear Optimization|2015|AdaFTRL|[arxiv](https://arxiv.org/abs/1502.05744)||gradient descent|
|A Linearly-Convergent Stochastic L-BFGS Algorithm|2015|SVRG-SQN|[arxiv](https://arxiv.org/abs/1508.02087)|[code](https://github.com/pcmoritz/slbfgs)|quasi-newton|
|Accelerating SVRG via second-order information|2015|SVRG+II: LBFGS|[opt](https://opt-ml.org/oldopt/opt15/papers.html)||quasi-newton|
|Accelerating SVRG via second-order information|2015|SVRG+I: Subsampled Hessian followed by SVT|[opt](https://opt-ml.org/oldopt/opt15/papers.html)||quasi-newton|
|Probabilistic Line Searches for Stochastic Optimization|2015|ProbLS|[arxiv](https://arxiv.org/abs/1502.02846)||gradient descent|
|Stochastic Quasi-Newton Methods for Nonconvex Stochastic Optimization|2016|Damp-oBFGS-Inf|[arxiv](https://arxiv.org/abs/1607.01231)|[code](https://github.com/harryliew/SdLBFGS)|quasi-newton|
|AdaBatch: Adaptive Batch Sizes for Training Deep Neural Networks|2017|AdaBatch|[arxiv](https://arxiv.org/abs/1712.02029)|[code](https://github.com/GXU-GMU-MICCAI/AdaBatch-numerical-experiments)|gradient descent|
|AdaComp : Adaptive Residual Gradient Compression for Data-Parallel Distributed Training|2017|AdaComp|[arxiv](https://arxiv.org/abs/1712.02679)||gradient descent|
|SARAH: A Novel Method for Machine Learning Problems Using Stochastic Recursive Gradient|2017|SARAH|[arxiv](https://arxiv.org/abs/1703.00102)||variance reduced|
|Sub-sampled Cubic Regularization for Non-convex Optimization|2017|SCR|[arxiv](https://arxiv.org/abs/1705.05933)|[code](https://github.com/dalab/subsampled_cubic_regularization)|inexact hessian|
|IQN: An Incremental Quasi-Newton Method with Local Superlinear Convergence Rate|2017|IQN|[arxiv](https://arxiv.org/abs/1702.00709)|[code](https://github.com/mlpack/ensmallen/tree/master/include/ensmallen_bits/iqn)|quasi-newton|
|Decoupled Weight Decay Regularization|2017|AdamW|[arxiv](https://arxiv.org/abs/1711.05101)|[code](https://github.com/loshchil/AdamW-and-SGDW)|gradient descent|
|Decoupled Weight Decay Regularization|2017|SGDW|[arxiv](https://arxiv.org/abs/1711.05101)|[code](https://github.com/loshchil/AdamW-and-SGDW)|gradient descent|
|Adafactor: Adaptive Learning Rates with Sublinear Memory Cost|2018|Adafactor|[arxiv](https://arxiv.org/abs/1804.04235)|[code](https://github.com/DeadAt0m/adafactor-pytorch)|gradient descent|
|Quasi-hyperbolic momentum and Adam for deep learning|2018|QHAdam|[arxiv](https://arxiv.org/abs/1810.06801)|[code](https://github.com/facebookresearch/qhoptim)|gradient descent|
|Online Adaptive Methods, Universality and Acceleration|2018|AcceleGrad|[arxiv](https://arxiv.org/abs/1809.02864)||gradient descent|
|Bayesian filtering unifies adaptive and non-adaptive neural network optimization methods|2018|AdaBayes|[arxiv](https://arxiv.org/abs/1807.07540)|[code](https://github.com/LaurenceA/adabayes)|gradient descent|
|On the Convergence of A Class of Adam-Type Algorithms for Non-Convex Optimization|2018|AdaFom|[arxiv](https://arxiv.org/abs/1808.02941)||gradient descent|
|Fast Approximate Natural Gradient Descent in a Kronecker-factored Eigenbasis|2018|EKFAC|[arxiv](https://arxiv.org/abs/1806.03884)|[code](https://github.com/Thrandis/EKFAC-pytorch)|gradient descent|
|AdaShift: Decorrelation and Convergence of Adaptive Learning Rate Methods|2018|AdaShift|[arxiv](https://arxiv.org/abs/1810.00143)|[code](https://github.com/MichaelKonobeev/adashift)|gradient descent|
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
|Gravity Optimizer: a Kinematic Approach on Optimization in Deep Learning|2021|Gravity|[arxiv](https://arxiv.org/abs/2101.09192)|[code](https://github.com/dariush-bahrami/gravity.optimizer)|gradient descent|
|Dynamic Game Theoretic Neural Optimizer|2021|DGNOpt|[arxiv](https://arxiv.org/abs/2105.03788)||gradient descent|
