
# Quantum VQE Simulation for LiH Molecule

This project illustrates a Variational Quantum Eigensolver (VQE) simulation of the lithium hydride (LiH) molecule with IBM's Qiskit. It contains implementations on a quantum simulator, as well as code optimized for execution on real quantum hardware and error correction.

---

## Project Structure

| File | Description |
|------|-------------|
| `LiH VQE.ipynb` | Complete VQE implementation using Qiskit simulator with results |
| `Error Mitigation.ipynb` | Code for applying error mitigation strategies |
| `Real Hardware.ipynb` | Code for running VQE on IBM Quantum hardware |
| `requirements.txt` | All required packages and dependencies |

---

## Work

- Constructed and simulated LiH molecule using **Qiskit Nature**
- Applied **VQE algorithm** with a UCC ansatz
- Used classical optimizer (`SLSQP`) to find the ground state energy
- Verified convergence and plotted energy evolution

- **Error Mitigation Techniques**: Includes code snippets using Ignis tools like measurement error mitigation.
- **Real Hardware Execution**: Provides code structure to submit circuits to IBM Quantum backend via `qiskit-ibm-provider`.

The above two sections are scaffolded for future work and extension.

---

## How to Run

1. **Clone the repo**:
   ```bash
   git clone https://github.com/Ujjwal21293/Ground-State-Energy-Estimation.git
   cd Ground-State-Energy-Estimation

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the notebook**:
   Open `LiH VQE.ipynb` in JupyterLab or VSCode and run all cells.

---

## Future Enhancements

- Run error mitigation routines and evaluate improvements
- Execute on real hardware and compare results with simulation
- Add automatic transpilation benchmarking
