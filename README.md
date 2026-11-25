<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/brand/brainlife-mark-on-dark.svg">
    <img src=".github/brand/brainlife-mark-on-light.svg" alt="brainlife.io" width="140">
  </picture>
</p>

<h1 align="center">Brain Connectivity Toolbox (BCT)</h1>

<p align="center">
  The MATLAB Brain Connectivity Toolbox, packaged to add as a git submodule.
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-lightgrey.svg" alt="MIT license"></a>
  <img src="https://img.shields.io/badge/Status-dormant-yellow.svg" alt="Status: dormant">
  <a href="https://brainlife.io"><img src="https://img.shields.io/badge/brainlife.io-site-3b9fd0.svg" alt="brainlife.io"></a>
  <a href="https://brainlife.io/docs"><img src="https://img.shields.io/badge/Docs-brainlife.io%2Fdocs-005981.svg" alt="Documentation"></a>
  <a href="https://doi.org/10.1038/s41592-024-02237-2"><img src="https://img.shields.io/badge/DOI-10.1038%2Fs41592--024--02237--2-e57536.svg" alt="Nature Methods paper"></a>
</p>

## 🧠 At a glance

| | |
|---|---|
| 🧭 **What** | All functions of the [Brain Connectivity Toolbox](https://sites.google.com/site/bctnet/) in `BCT/`, for use as a submodule in brainlife Apps |
| 🐍 **Python** | [bctpy](https://github.com/aestrivex/bctpy) |
| 🕰️ **Last change** | 2020-12-16 |

## 🚀 Use it in an App

```bash
git submodule add https://github.com/brainlife/BCT
```

Then `addpath(genpath('BCT'))` in MATLAB.

## 📚 Cite the toolbox

> Rubinov M, Sporns O. Complex network measures of brain connectivity: uses and interpretations. *NeuroImage* 52:1059–1069 (2010). [doi:10.1016/j.neuroimage.2009.10.003](https://doi.org/10.1016/j.neuroimage.2009.10.003)

## 📚 Citing

If you use brainlife.io in your work, please cite:

> Hayashi S, Caron BA, Heinsfeld AS, et al. brainlife.io: a decentralized and open-source cloud platform to support neuroscience research. *Nature Methods* 21:809–813 (2024). [doi:10.1038/s41592-024-02237-2](https://doi.org/10.1038/s41592-024-02237-2)

## 🤝 Contributing

Issues and pull requests are welcome in this repository. For help using brainlife.io, see the [documentation](https://brainlife.io/docs).

## ⚖️ License

[MIT](LICENSE) for this packaging; the Brain Connectivity Toolbox has its own licence (see [brain-connectivity-toolbox.net](https://sites.google.com/site/bctnet/)).

<p align="center"><sub>brainlife.io · Brain data across scales. One place to analyze, share and publish it. · The University of Texas at Austin</sub></p>
