# Quantum Gate Visualizer

A visual exploration of quantum gates using the Bloch sphere. Each gate is applied to a qubit and its effect is shown as an arrow on a 3D sphere, making abstract quantum operations intuitive and easy to understand.

## What is a Bloch Sphere?

A Bloch sphere is a unit sphere where every point represents a possible state of a qubit. The north pole is |0⟩, the south pole is |1⟩, and the equator represents superposition — equally between both states.


## Key Insight

Y, Z, and S gates show no visible effect when starting from |0⟩ because the qubit sits at the north pole. Apply the H gate first to move to the equator, then apply these gates to see their full effect.

## Tech Stack

- Python
- Qiskit
- Matplotlib

## Setup

```bash
pip install qiskit matplotlib
```

Open `main.ipynb` in Jupyter Notebook and run all cells in order.