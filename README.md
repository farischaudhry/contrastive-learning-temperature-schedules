# Global Convergence and Geometry of Contrastive Learning through Temperature Annealing

A PyTorch implementation and empirical study of how different temperature‐annealing schedules affect contrastive representation learning on CIFAR‑10. We demonstrate that (1) the shape of the annealing schedule critically impacts final linear‐probe accuracy and loss dynamics, and (2) improperly chosen (fixed) temperatures can lead to “freezing” in suboptimal minima.

Made for use on Google Colab.

Please use the cifar10_results_sgd.zip version for results most aligned to the paper. 

---

## 📥 Downloading the results

> **⚠️ This repository uses Git LFS for CIFAR‑10 results and pretrained backbones.**

```bash
git clone https://github.com/your‑org/contrastive‑annealing.git
cd contrastive‑annealing
git lfs install
git lfs pull
```
