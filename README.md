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

Then navigate to any algorithm folder and run its script.

---

## Algorithms

### Motor Control

| Algorithm | Folder | Issue | Hardware |
|---|---|---|---|
| FOC — Field Oriented Control | [motor-control/foc](./motor-control/foc/) | #01 | 200W PMSM air circulator |
| IPD — Initial Position Detection | [motor-control/ipd](./motor-control/ipd/) | #02 | 35W BLDC ceiling fan |
| SMO-PLL — Sensorless observer | [motor-control/smo-pll](./motor-control/smo-pll/) | #03 | 200W PMSM air circulator |

### Power Conversion

| Algorithm | Folder | Issue | Hardware |
|---|---|---|---|
| *(coming)* | [power-conversion](./power-conversion/) | — | — |

### Energy Systems

| Algorithm | Folder | Issue | Hardware |
|---|---|---|---|
| *(coming)* | [energy-systems](./energy-systems/) | — | — |

---

## Repo structure

```
algorithms-in-action/
├── README.md               ← you are here
├── requirements.txt        ← global dependencies (one install for all)
├── motor-control/
│   ├── foc/
│   │   ├── README.md       ← algorithm-specific docs + math
│   │   └── coordinate_transform.py
│   ├── ipd/
│   └── smo-pll/
├── power-conversion/
└── energy-systems/
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
