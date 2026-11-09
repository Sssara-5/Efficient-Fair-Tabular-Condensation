# Efficient and Fair Tabular Data Condensation

This is the official implementation of our **C²TC** framework and its fair variant **Fair-C²TC**, as presented in **“Efficient and Fair Tabular Data Condensation.”**

## 📦 Installation

Follow the steps below to set up the environment.

### 1) Clone the repo

```bash
git clone https://github.com/Sssara-5/Efficient-Fair-Tabular-Condensation.git
cd Efficient-Fair-Tabular-Condensation
```

### 2) Environment (Conda recommended)

```bash
conda env create -f src/environment.yml
conda activate cctc
```

---

## 🚀 Quick start

### C²TC

```bash
cd src
bash run_pipeline.sh
```

Or without activating the shell:

```bash
cd src
conda run -n cctc --no-capture-output bash run_pipeline.sh
```

### Fair-C²TC

```bash
cd src
bash run_fair_pipeline.sh
```

Or without activating the shell:

```bash
cd src
conda run -n cctc --no-capture-output bash run_fair_pipeline.sh
```

## 🎬 C²TC Demo

[![C²TC demo](assets/demo/C2TC_demo_only.webp)](assets/demo/C2TC_demo_only.mp4)

## 📖 Citation

### ICDE 2026

S. Xu, F. Li, X. Wang, Z. Yang and X. Lin, "C2TC: A Training-Free Framework for Efficient Tabular Data Condensation," *2026 IEEE 42nd International Conference on Data Engineering (ICDE)*, Montreal, QC, Canada, 2026, pp. 2725–2738, doi: [10.1109/ICDE65706.2026.00203](https://doi.org/10.1109/ICDE65706.2026.00203).

```bibtex
@inproceedings{xu2026c2tc,
  title     = {{C2TC}: A Training-Free Framework for Efficient Tabular Data Condensation},
  author    = {Xu, Sijia and Li, Fan and Wang, Xiaoyang and Yang, Zhengyi and Lin, Xuemin},
  booktitle = {2026 IEEE 42nd International Conference on Data Engineering (ICDE)},
  pages     = {2725--2738},
  address   = {Montreal, QC, Canada},
  year      = {2026},
  doi       = {10.1109/ICDE65706.2026.00203},
  keywords  = {Modeling;Printing;Training;Resource management;Labeling;Optimization;Timing;Algorithms;Equations;Encoding;tabular data;data condensation}
}
```

### arXiv preprint

Paper: [arXiv:2602.21717](https://arxiv.org/abs/2602.21717)

```bibtex
@article{xu2026c,
  title   = {{C$^2$TC}: A Training-Free Framework for Efficient Tabular Data Condensation},
  author  = {Xu, Sijia and Li, Fan and Wang, Xiaoyang and Yang, Zhengyi and Lin, Xuemin},
  journal = {arXiv preprint arXiv:2602.21717},
  year    = {2026}
}
```

