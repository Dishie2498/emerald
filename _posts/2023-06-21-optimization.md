---
title: Optimization of Code
---
## [jax.vmap()](https://jax.readthedocs.io/en/latest/_autosummary/jax.vmap.html)
[```vmap```](https://jax.readthedocs.io/en/latest/_autosummary/jax.vmap.html) is a feature in JAX that enables efficient parallelization of functions over arrays or sequences of inputs.
- vmap stands for "vectorized map" and is a powerful feature that enables efficient parallelization of functions over arrays or sequences of inputs.
- With vmap, you can seamlessly apply a function to a batch of inputs, eliminating the need for explicit looping. This not only simplifies the code but also significantly improves performance, especially when dealing with large datasets or complex computations.

### Following is the comparison in computation times between tensor and vmap implementation 
![comparison graph](https://drive.google.com/file/d/1Y0mtv3flyzhtfjgR3P6UXl499FUUFqyA/view?usp=sharing)

### Following PRs implement vmap in calculating o-information
- [Pull request #6](https://github.com/brainets/hoi/pull/6)
- [Pull request #7](https://github.com/brainets/hoi/pull/7)

  
