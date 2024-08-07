---
title: "Bias-Variance Trade-off in Physics-Informed Neural Networks with Randomized Smoothing for High-Dimensional PDEs"
collection: publications
permalink: /publication/Bias-Variance Trade-off in Physics-Informed Neural Networks with Randomized Smoothing for High-Dimensional PDEs
date: 2023.11.26
venue: 'SIAM Journal of Computational Physics (under review)'
citation: 'Z. Hu, Z. Yang, Y. Wang, G.E. Karniadakis, K. Kawaguchi, Bias-variance trade-off in physics-informed neural networks with randomized smoothing for high-dimensional PDEs, 2023, arXiv preprint arXiv:2311.15283.'
---
Abstract:  Physics-Informed Neural Networks (PINNs) have triggered a paradigm shift in scientific computing, leveraging
 mesh-free properties and robust approximation capabilities. While proving effective for low-dimensional partial
 differential equations (PDEs), the computational cost of PINNs remains a hurdle in high-dimensional scenarios. This
 is particularly pronounced when computing high-order and high-dimensional derivatives in the physics-informed loss.
 Randomized Smoothing PINN (RS-PINN) introduces Gaussian noise for stochastic smoothing of the original neural
 net model, enabling the use of Monte Carlo methods for derivative approximation, which eliminates the need for costly
 automatic differentiation. Despite its computational efficiency, especially in the approximation of high-dimensional
 derivatives, RS-PINN introduces biases in both loss and gradients, negatively impacting convergence, especially
 when coupled with stochastic gradient descent (SGD) algorithms. We present a comprehensive analysis of biases
 in RS-PINN, attributing them to the nonlinearity of the Mean Squared Error (MSE) loss as well as the intrinsic
 nonlinearity of the PDE itself. We propose tailored bias correction techniques, delineating their application based
 on the order of PDE nonlinearity. The derivation of an unbiased RS-PINN allows for a detailed examination of its
 advantages and disadvantages compared to the biased version. Specifically, the biased version has a lower variance
 and runs faster than the unbiased version, but it is less accurate due to the bias. To optimize the bias-variance
 trade-off, we combine the two approaches in a hybrid method that balances the rapid convergence of the biased
 version with the high accuracy of the unbiased version. In addition to methodological contributions, we present
 an enhanced implementation of RS-PINN. Extensive experiments on diverse high-dimensional PDEs, including
 Fokker-Planck, Hamilton-Jacobi-Bellman (HJB), viscous Burgers’, Allen-Cahn, and Sine-Gordon equations, illustrate
 the bias-variance trade-off and highlight the effectiveness of the hybrid RS-PINN. Empirical guidelines are provided
 for selecting biased, unbiased, or hybrid versions, depending on the dimensionality and nonlinearity of the specific
 PDE problem.

[Download paper here](http://Zhouhao-Yang.github.io/files/Bias-Variance Trade-off in Physics-Informed Neural Networks with Randomized Smoothing for High-dim PDEs.pdf)
