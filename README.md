<h1 align="center">[NeurIPS 2025] 🌴 HAWAII: Hierarchical Visual Knowledge Transfer for Efficient Vision-Language Models</h1>

<p align="center">
  <strong>NeurIPS 2025</strong>
</p>

<p align="center">
  <strong>Yimu Wang, Mozhgan Nasr Azadani, Sean Sedwards, Krzysztof Czarnecki</strong>
</p>

<p align="center">
  <em>University of Waterloo</em>
</p>

<p align="center">
  <a href="https://arxiv.org/abs/2506.19072">
    <img src="https://img.shields.io/badge/arXiv-2506.19072-b31b1b?style=for-the-badge&logo=arxiv&logoColor=white" alt="arXiv">
  </a>
  <a href="https://openreview.net/forum?id=LIGBnhb83e">
    <img src="https://img.shields.io/badge/Paper-OpenReview-b31b1b?style=for-the-badge&logo=arxiv&logoColor=white" alt="Paper">
  </a>
  <a href="https://yimuwangcs.github.io/projects/neurips25_hawaii/index.html">
    <img src="https://img.shields.io/badge/Project-Page-blue?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Project Page">
  </a>
  <!-- <a href="https://github.com/yourusername/wise-hawaii">
    <img src="https://img.shields.io/badge/Code-GitHub-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a> -->
</p>

---

## 🔥 News

- **[TODO]** The code will be released in December.
- **[Nov 2025]** Our paper has been accepted by **NeurIPS 2025**! 🎉
- **[Jun 2025]** Our paper is now available on [arXiv](https://arxiv.org/abs/2506.19072)!

---

## Abstract

Improving the visual understanding ability of vision-language models (VLMs) is crucial for enhancing their performance across various tasks. While using multiple pretrained visual experts has shown great promise, it often incurs significant computational costs during training and inference. To address this challenge, we propose **HAWAII**, a novel framework that distills knowledge from multiple visual experts into a single vision encoder, enabling it to inherit the complementary strengths of several experts with minimal computational overhead. 

To mitigate conflicts among different teachers and switch between different teacher-specific knowledge, instead of using a fixed set of adapters for multiple teachers, we propose to use teacher-specific Low-Rank Adaptation (LoRA) adapters with a corresponding router. Each adapter is aligned with a specific teacher, avoiding noisy guidance during distillation. 

To enable efficient knowledge distillation, we propose fine-grained and coarse-grained distillation. At the fine-grained level, token importance scores are employed to emphasize the most informative tokens from each teacher adaptively. At the coarse-grained level, we summarize the knowledge from multiple teachers and transfer it to the student using a set of general-knowledge LoRA adapters with a router. 

Extensive experiments on various vision-language tasks demonstrate the superiority of HAWAII, compared to the popular open-source VLMs.

## Citation

If you find HAWAII useful for your research, please cite our paper:

```bibtex
@inproceedings{
    wang2025hawaii,
    title={Hawaii: Hierarchical Visual Knowledge Transfer for Efficient Vision-Language Models},
    author={Yimu Wang, Mozhgan Nasr Azadani, Sean Sedwards, Krzysztof Czarnecki},
    booktitle={The Thirty-ninth Annual Conference on Neural Information Processing Systems},
    year={2025},
    url={https://openreview.net/forum?id=LIGBnhb83e}
}
```

---

## License

HAWAII is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## Contact

For questions or collaborations, please contact:
- Yimu Wang: [yimu.wang@uwaterloo.ca](mailto:yimu.wang@uwaterloo.ca)
