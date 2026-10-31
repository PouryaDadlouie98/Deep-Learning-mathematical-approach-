# 01 — Autograd & Backprop

Build a tiny scalar autograd engine and train a small MLP with it. Pure Python, no NumPy.

## Read

- **CS231n — Backpropagation, Intuitions**: https://cs231n.github.io/optimization-2/

## Implement

| File | What goes in it |
|------|-----------------|
| `engine.py` | `Value` class: `+`, `*`, `**`, `tanh`, `relu`, and `backward()` using a topological sort |
| `nn.py` | `Neuron`, `Layer`, `MLP`, with a `parameters()` method on each |
| `gradcheck.py` | Compare analytic gradients against central finite differences |
| `train.py` | Generate a 2-class toy dataset (circles or moons), train with SGD, report loss and accuracy |

## Done when

- [ ] Gradient check: every parameter differs from the numerical gradient by less than `1e-6`
- [ ] Loss decreases and accuracy on the toy dataset exceeds 95%
- [ ] You can explain, without notes, why gradients are accumulated with `+=` and not assigned with `=`

## Compare (only after the checklist passes)

- `karpathy/micrograd` — `engine.py` and `nn.py`
