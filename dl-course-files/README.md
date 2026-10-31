<div align="center">

# Deep Learning — A Mathematical Approach

**From backprop on paper to OCR in production.**
Every model here is implemented from scratch first, then rebuilt with a framework.

![Python](https://img.shields.io/badge/Python-3.11+-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-from%20scratch-013243?logo=numpy&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-later%20sections-EE4C2C?logo=pytorch&logoColor=white)
![Colab](https://img.shields.io/badge/Runs%20on-Google%20Colab-F9AB00?logo=googlecolab&logoColor=white)
![License](https://img.shields.io/badge/License-Apache%202.0-blue)

</div>

---

## Why this repo

A practical path through deep learning for people who want to understand *why* the math works, not just call `.fit()`.
The track leads toward **OCR** (Persian documents and license plates), then **NLP**, then **agentic AI**, with MLOps practices along the way.

## Rules of the game

1. **Read first, then close the tab.** Each section has one article.
2. **No copy-paste.** Code is written from understanding, not from reference implementations.
3. **Prove it works.** Every section has a "done" checklist (gradient checks, accuracy targets, explanations).
4. **Compare last.** Reference code is only opened after your own version passes.

## Roadmap

| # | Section | Core idea | Status |
|---|---------|-----------|:------:|
| 01 | [Autograd & Backprop](01_autograd/) | Computational graphs, chain rule, scalar autograd engine | 🟡 In progress |
| 02 | CNN with NumPy | Conv / pool forward & backward, im2col | ⚪ Planned |
| 03 | CNN in PyTorch | Init, BatchNorm, training diagnostics | ⚪ Planned |
| 04 | CRNN + CTC | Sequence recognition for Persian plates & digits | ⚪ Planned |
| 05 | Detection: SSD → YOLO | Anchors, IoU, NMS, field detection on documents | ⚪ Planned |
| 06 | Attention & Transformers → TrOCR / Donut | End-to-end document understanding | ⚪ Planned |
| 07 | NLP for OCR output | Persian tokenization, NER | ⚪ Planned |
| 08 | Agentic AI | Tool use, planning, evaluation | ⚪ Planned |

Status: ⚪ Planned · 🟡 In progress · 🟢 Done

## Repository layout

```
.
├── 01_autograd/
│   ├── README.md        # reading, tasks, done-criteria
│   ├── engine.py        # Value: scalar autograd
│   ├── nn.py            # Neuron, Layer, MLP
│   ├── gradcheck.py     # analytic vs numerical gradients
│   └── train.py         # training loop on a toy dataset
├── 02_cnn_numpy/
├── requirements.txt
└── README.md
```

Each section is self-contained: plain `.py` modules for the logic, notebooks only for running and plotting.

## Running on Google Colab

1. Mount Google Drive and clone this repo into it, so work survives session resets.
2. Open a notebook, `%cd` into the section folder and `import` the modules.
3. Sections 01–02 run on CPU; switch to a GPU runtime from section 03 onward.

## License

[Apache 2.0](LICENSE)
