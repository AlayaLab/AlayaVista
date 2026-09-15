<h1 align="center">AlayaVista</h1>
<h3 align="center">Streaming World Modeling from Panoramic States to Perspective Video</h3>

<p align="center"><a href="https://alayalab.ai/"><b>Alaya Lab</b></a></p>

<p align="center">
  <a href="https://alaya-lab.github.io/AlayaVista/"><img src="https://img.shields.io/badge/Project-Page-blue" alt="Project Page"></a>
  <a href="https://arxiv.org/abs/2609.14462"><img src="https://img.shields.io/badge/Paper-arXiv-red" alt="Paper on arXiv"></a>
</p>

<p align="center">
  <img src="assets/teaser.webp" width="100%" alt="AlayaVista evolves panoramic states under camera control and renders and refines the requested perspective views.">
</p>

<p align="center"><i>Maintain panoramic context. Refine the view you choose.</i></p>

**AlayaVista** is a camera-controllable streaming video world model that starts from a single perspective image. It constructs a 360° scene prior, evolves camera-conditioned panoramic latent states, and synthesizes the requested perspective video through latent viewport rendering and local refinement. Chunk-autoregressive generation and few-step distillation enable efficient streaming while concentrating high-fidelity synthesis on the selected viewport.

## 📰 News

- The [project page](https://alaya-lab.github.io/AlayaVista/) and [paper](https://arxiv.org/abs/2609.14462) are available.

## 🚀 Release Roadmap

- [x] Project page
- [x] Technical report
- [ ] Inference code
- [ ] Pretrained weights

## Citation

```bibtex
@misc{tan2026alayavistastreamingworldmodeling,
      title={AlayaVista: Streaming World Modeling from Panoramic States to Perspective Video},
      author={Jiaming Tan and Mingliang Zhai and Zhen Li and Yuwei Wu and Chuanhao Li and Kaipeng Zhang},
      year={2026},
      eprint={2609.14462},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2609.14462},
}
```
