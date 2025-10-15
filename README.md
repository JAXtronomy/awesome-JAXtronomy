<!--lint ignore double-link-->
# Awesome-JAXtronomy [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)[<img src="./jaxtronomy_log.png" alt="JAXtronomy Logo" align="right" height="100">](https://github.com/JAXtronomy)

<!--lint ignore double-link-->
[JAX](https://github.com/google/jax) brings automatic differentiation and the [XLA compiler](https://www.tensorflow.org/xla) together through a [NumPy](https://numpy.org/)-like API for high performance machine learning research on accelerators like GPUs and TPUs.
<!--lint enable double-link-->

This is a curated list of awesome JAX libraries, projects, and other resources specifically coming from the field of astronomy/astrophysics. Contributions are welcome!

For a broader list of JAX resources, check out the [awesome-jax](https://github.com/n2cholas/awesome-jax) repository.

## Contents

- [Awesome-JAXtronomy ](#awesome-jaxtronomy-)
  - [Contents](#contents)
  - [To add](#to-add)
  - [Useful tools](#useful-tools)
  - [Inference](#inference)
  - [Gravitational waves](#gravitational-waves)
  - [Supernovae, kilonovae, gamma-ray bursts,...](#supernovae-kilonovae-gamma-ray-bursts)
  - [Neutron stars](#neutron-stars)
  - [Cosmology](#cosmology)
  - [Galactic physics](#galaxy)
  - [Exoplanets](#exoplanets)
  - [Optics](#optics)

<a name="to-add" />

## To add

- 

<a name="useful-tools" />

## Useful tools

- 

<a name="inference" />

## Inference

- [flowMC](https://github.com/kazewong/flowMC) - Normalizing-flow enhanced sampling package for probabilistic inference in Jax. <img src="https://img.shields.io/github/stars/kazewong/flowMC?style=social" align="center">
    - Papers: [arXiv:2211.06397](https://arxiv.org/abs/2211.06397), [arXiv:2105.12603](https://arxiv.org/abs/2105.12603)
- [BlackJAX](https://github.com/blackjax-devs/blackjax) - Library of samplers for JAX (MCMC: HMC, NUTS, MALA, etc.; SMC; SGMCMC; VI) that works on CPU as well as GPU. <img src="https://img.shields.io/github/stars/blackjax-devs/blackjax?style=social" align="center">
    - PR: [#755](https://github.com/blackjax-devs/blackjax/pull/755) - includes nested sampling and slice sampling

<a name="gravitational-waves" />

## Computational Fluid Dynamics

- [simple 2D fluid solver in JAX](https://github.com/pmocz/jax-euler-benchmarks) - solves the 2D Euler equations on distributed GPU systems in 300 lines of code <img src="https://img.shields.io/github/stars/pmocz/jax-euler-benchmarks?style=social" align="center">

## Gravitational waves

- [ripple](https://github.com/tedwards2412/ripple) - Differentiable Gravitational Waveforms with JAX <img src="https://img.shields.io/github/stars/tedwards2412/ripple?style=social" align="center">
    - Paper: [arXiv:2302.05329](https://arxiv.org/abs/2302.05329)
- [jim](https://github.com/kazewong/jim) - Gravitational-wave data analysis tools in Jax <img src="https://img.shields.io/github/stars/kazewong/jim?style=social" align="center">
    - Papers: [arXiv:2302.05333](https://arxiv.org/abs/2302.05333), [arXiv:2404.11397](https://arxiv.org/abs/2404.11397)
- [ringdown](https://github.com/maxisi/ringdown/tree/main) - Black hole ringdowns with JAX and numpyro <img src="https://img.shields.io/github/stars/maxisi/ringdown?style=social" align="center">
    - Papers: [arXiv:2107.05609](https://arxiv.org/abs/2107.05609)

<a name="supernovae-etc" />

## Supernovae, kilonovae, gamma-ray bursts,...

- [fiesta](https://github.com/ThibeauWouters/fiesta) - Fast inference of electromagnetic signals and transients with JAX <img src="https://img.shields.io/github/stars/ThibeauWouters/fiesta?style=social" align="center">

<a name="neutron-stars" />

## Neutron stars

- [jester](https://github.com/tsunhopang/jester) - JAX-based EOS and TOV solver <img src="https://img.shields.io/github/stars/tsunhopang/jester?style=social" align="center">

<a name="cosmology" />

## Cosmology

- [LINX](https://github.com/cgiovanetti/LINX) - A fast, differentiable, and extensible public BBN code <img src="https://img.shields.io/github/stars/cgiovanetti/LINX?style=social" align="center">
    - Papers: [arXiv:2408.14538](https://arxiv.org/abs/2408.14538), [arXiv:2408.14531](https://arxiv.org/abs/2408.14531)
- [candl](https://github.com/Lbalkenhol/candl) - Differentiable Likelihood for CMB Analysis <img src="https://img.shields.io/github/stars/Lbalkenhol/candl?style=social" align="center">
    - Papers: [arXiv:2412.00826](https://arxiv.org/abs/2412.00826)

<a name="galaxy" />

## Galactic physics

- [synax](https://github.com/dkn16/Synax) - A GPU-accelerated automatic differentiable Galactic synchrotron simulation package <img src="https://img.shields.io/github/stars/dkn16/Synax?style=social" align="center">
    - Papers: [arXiv:2410.01136](https://arxiv.org/abs/2410.01136)

<a name="exoplanets" />

## Exoplanets

- [jaxoplanet](https://github.com/exoplanet-dev/jaxoplanet) - a
[functional-programming](https://en.wikipedia.org/wiki/Functional_programming)-forward
implementation of many features from the
[exoplanet](https://docs.exoplanet.codes/en/latest/) and
[starry](https://starry.readthedocs.io/en/latest/) packages built on top of
[JAX](https://jax.readthedocs.io/en/latest/) <img src="https://img.shields.io/github/stars/exoplanet-dev/jaxoplanet?style=social" align="center">
- [squishyplanet](https://github.com/ben-cassese/squishyplanet) - Tranists and phase curves of non-spherical exoplanets in JAX <img src="https://img.shields.io/github/stars/ben-cassese/squishyplanet?style=social" align="center">
    - Paper: [arXiv:2409.00167](https://arxiv.org/abs/2409.00167)
- [ExoJAX](https://github.com/HajimeKawahara/exojax) - differentiable spectrum model from exoplanet and substellar atmosphere <img src="https://img.shields.io/github/stars/HajimeKawahara/exojax?style=social" align="center">
    - Papers: [arXiv:2105.14782](https://arxiv.org/abs/2105.14782), [arXiv:2410.06900](https://arxiv.org/abs/2410.06900)

<a name="optics" />

## Optics

 - [∂Lux](https://louisdesdoigts.github.io/dLux/) — differentiable physical optical models from Louis Desdoigts et al. [![GitHub star count](https://img.shields.io/github/stars/louisDesdoigts/dlux?style=social)](https://github.com/louisDesdoigts/dlux)

## X-rays

 - [jaxspec](https://github.com/renecotyfanboy/jaxspec) — differentiable likelihoods for X-ray spectral fitting [![GitHub star count](https://img.shields.io/github/stars/renecotyfanboy/jaxspec?style=social)](https://github.com/renecotyfanboy/jaxspec)
   - Paper : [arxiv:2409.05757](https://arxiv.org/abs/2409.05757)
