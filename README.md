# An Approach Based on Fine-Tuning Small Language Models for Fake News Detection

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-orange)](https://pytorch.org/)
[![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)](https://huggingface.co/docs/transformers/index)
[![PEFT](https://img.shields.io/badge/PEFT-LoRA-green)](https://github.com/huggingface/peft)

---
## Abstract
To address the trade-off between accuracy and computational cost in fake news detection, this study investigates the potential of Small Language Models (SLMs). By employing an adaptive fine-tuning pipeline on DistilBERT, MiniLM, and ALBERT architectures, we benchmark the efficacy of Full Fine-Tuning against PEFT techniques such as LoRA and Adapters. Our research demonstrates that SLMs not only achieve accuracy comparable to large models on standard benchmarks ($F_1 > 99\%$ on WELFake) but also offer superior inference speed with MiniLM. Notably, we identify a "model collapse" phenomenon on the short-text LIAR dataset and demonstrate that Bottleneck Adapters are the sole strategy capable of maintaining stability ($F_1 \approx 68\%$), significantly outperforming LoRA and Prompt Tuning. These findings validate that SLMs, when paired with appropriate fine-tuning strategies, serve as an optimal alternative to

## Citation
If you use this code or our results in your research, please cite our paper:

```bibtex
@article{phan2025approach,
  title={An Approach Based on Fine-tuning Small Language Models for Fake News Detection},
  author={Phan, Khac-Lap and Pham, Quang-Vinh and Le, Quang-Hung},
  journal={Dept. of Information Technology, Quy Nhon University},
  year={2025}
}
