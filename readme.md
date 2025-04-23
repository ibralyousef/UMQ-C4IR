**This workshop was presented by UMQ, Join us!**
![UMQ Joining](https://github.com/user-attachments/assets/9e010933-53b2-4cc7-97c0-b20760376831)


# Calibration Verifications Using QuTiP

This repository provides a Jupyter notebook (`C4IR_Workshop.ipynb`) for simulating and visualizing calibration procedures in superconducting qubit systems using [QuTiP](http://qutip.org/) and [scqubits](https://scqubits.readthedocs.io/).

## Features

- **Frequency Domain**: Coupled qubit-resonator Hamiltonian, energy levels, resonator spectroscopy.
- **Two-Tone Spectroscopy**: Simulated extraction of qubit and resonator frequencies.
- **Time Domain**: Rabi oscillations, fitting routines, and visualization.
- **Qubit Characterization**: T1 (relaxation) and T2* (coherence) measurements and fits.

## Usage

**Simulation cells are commented out** to avoid long runtimes. Instead, precomputed results are provided as pickled files in the `sim_data/` directory. The notebook loads these files for immediate plotting and analysis.

To re-run simulations, simply uncomment the relevant code cells.

### Provided Pickled Outputs

- `sim_data/output_r_spectroscopy.pkl` — Resonator spectroscopy
- `sim_data/output_two_tone.pkl` — Two-tone spectroscopy
- `sim_data/output_chevron.pkl` — Rabi measurement
- `sim_data/output_T1.pkl` — T1 relaxation
- `sim_data/output_T2_start.pkl` — T2* (Ramsey)

## Requirements

- Python 3.7+
- qutip, scqubits, numpy, matplotlib, joblib, tqdm

Install with:
```sh
pip install qutip scqubits numpy matplotlib joblib tqdm
```

## How to Run

1. Open `C4IR_Workshop.ipynb` in Jupyter or VS Code.
2. Run the notebook. Simulation cells are commented; uncomment to re-run if needed.
3. Plots and analysis will use the provided pickled data.

---

**Author:**  
Ibraheem AlYousef
