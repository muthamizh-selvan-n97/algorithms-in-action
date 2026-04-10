# Algorithms in Action
**By Muthamil Selvan N — Principal Engineer - Motor Control & Embedded Systems**
> *Deep dives on algorithms that power, control, and learn — implemented on motors, converters, and energy systems.*

Companion repository for the [Algorithms in Action](https://www.linkedin.com/newsletters/algorithms-in-action-7404786715468402688/) newsletter on LinkedIn.

Each algorithm gets a working visualizer — runnable on any machine with Python. Not textbook implementations. Every algorithm here has been run on real hardware.

---

## Quick start

```bash
git clone https://github.com/muthamizh-selvan-n97/algorithms-in-action.git
cd algorithms-in-action
pip install -r requirements.txt
```

Or open any notebook directly in Google Colab — no install needed.

---

## Algorithms

### Motor Control

| Issue | Algorithm | Folder | Colab |
|---|---|---|---|
| #01 | Coordinate Transformation | [motor-control/foc](./motor-control/foc/) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/muthamizh-selvan-n97/algorithms-in-action/blob/main/motor-control/foc/coordinate_transform.ipynb) |

### Power Conversion

| Issue | Algorithm | Folder |
|---|---|---|
| *(coming)* | — | — |

### Energy Systems

| Issue | Algorithm | Folder |
|---|---|---|
| *(coming)* | — | — |

---

## Repo structure

```
algorithms-in-action/
├── README.md                    ← you are here
├── requirements.txt             ← global dependencies (one install for all)
├── assets/                      ← GIFs and images for READMEs
└── motor-control/
    └── foc/
        ├── README.md            ← algorithm-specific docs + math reference
        └── coordinate_transform.ipynb
```

---

## Dependencies

```
numpy, matplotlib, pillow, scipy
```

Install once from the root:
```bash
pip install -r requirements.txt
```

---

## License

MIT — use freely, credit appreciated.
