# An Approach Based on Fine-Tuning Small Language Models for Fake News Detection

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-orange)](https://pytorch.org/)
[![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)](https://huggingface.co/docs/transformers/index)
[![PEFT](https://img.shields.io/badge/PEFT-LoRA-green)](https://github.com/huggingface/peft)

---
## Abstract
The rapid spread of fake news on digital platforms poses significant economic, political, and social risks, necessitating effective automated detection methods. Large language models (LLMs) have yielded appealing results in text classification tasks but face challenges due to computational costs, high latency, and substantial memory requirements. These hinder their deployment on edge devices or resource-constrained servers. This paper investigates the potential of small language models (SLMs) as lightweight yet effective alternatives for fake news detection. We evaluate state-of-the-art SLMs under both full and parameter-efficient fine-tuning (PEFT) strategies. Comprehensive experiments conducted on three benchmark datasets demonstrate that SLMs can obtain competitive performance with larger models while requiring substantially fewer trainable parameters, lower inference latency, and reduced hardware resources. Moreover, PEFT techniques further enhance adaptability and reduce computational cost without compromising accuracy. Our implementation is available in the following GitHub repository.

## Citation
If you use this code or our results in your research, please cite our paper:

```bibtex
@article{phan2025approach,
  title={An Approach Based on Fine-tuning Small Language Models for Fake News Detection},
  author={Phan, Khac-Lap and Pham, Quang-Vinh and Le, Quang-Hung},
  journal={Dept. of Information Technology, Quy Nhon University},
  year={2025}
}
