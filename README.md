# An Approach Based on Fine-Tuning Small Language Models for Fake News Detection

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-orange)](https://pytorch.org/)
[![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)](https://huggingface.co/docs/transformers/index)
[![PEFT](https://img.shields.io/badge/PEFT-LoRA-green)](https://github.com/huggingface/peft)

---
## Abstract
Our study validates SLMs as a robust solution for automated fact-checking. We conducted extensive experiments on both long-form (WELFake) and short-text (LIAR) datasets. The results highlight the critical role of structural adaptation (adapters) in handling noisy, context-sparse data compared to traditional Full Fine-Tuning or LoRA.

## Citation
If you use this code or our results in your research, please cite our paper:

```bibtex
@article{phan2025approach,
  title={An Approach Based on Fine-tuning Small Language Models for Fake News Detection},
  author={Phan, Khac-Lap and Pham, Quang-Vinh and Le, Quang-Hung},
  journal={Dept. of Information Technology, Quy Nhon University},
  year={2025}
}
