# LSTM-VQE: LSTM-Enhanced Variational Quantum Eigensolver

An implementation of a Long Short-Term Memory (LSTM) enhanced Variational Quantum Eigensolver (VQE) for optimizing UCCSD (Unitary Coupled Cluster Singles and Doubles) quantum circuit parameters. This project features two distinct approaches: our novel LSTM-FC-VQE method and a reference implementation of LSTM-VQE.

## Authors

- **YU-CHENG LIN**
- **RAN-YU CHANG**
- **PEI-CHE HSU**

## Overview

This repository contains two implementations of LSTM-enhanced VQE algorithms:

### 1. LSTM-FC-VQE (Novel Method)
Our proposed method combines LSTM with Fully Connected layers for VQE optimization, demonstrating enhanced performance in:
- Parameter optimization for UCCSD quantum circuits
- Ground state energy calculations for molecular systems
- Quantum chemistry simulations

Implementation files located in the `LSTM-FC-VQE/` directory:
- `novel_lstm_fc_vqe.ipynb`: Jupyter notebook implementation
- `novel_lstm_fc_vqe.py`: Python script version

### 2. Reference LSTM-VQE Implementation
A comparative implementation based on existing literature, located in the `Reference-LSTM-VQE/` directory:
- `lstm_vqe_original.ipynb`: Original LSTM-VQE implementation notebook
- `lstm_vqe_original.py`: Original LSTM-VQE Python script

## Technical Requirements

- Python 3.7+
- PyTorch: Deep learning framework
- PennyLane: Quantum machine learning framework
- PennyLane-QChem: Quantum chemistry package for PennyLane
- NumPy: Scientific computing library
- Pandas: Data manipulation library
- Matplotlib: Data visualization library
- Jupyter Notebook: Interactive computing environment

## Installation Guide

1. Clone the repository:
```bash
git clone https://github.com/[your-username]/LSTM-VQE.git
cd LSTM-VQE
```

2. Set up a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
# or
.\venv\Scripts\activate  # Windows
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Implementation

The project provides two implementation approaches:

1. LSTM-FC-VQE (Our Novel Method):
   ```bash
   cd LSTM-FC-VQE
   ```
   - Launch `novel_lstm_fc_vqe.ipynb` for interactive exploration
   - Or run `novel_lstm_fc_vqe.py` for script execution

2. Reference LSTM-VQE:
   ```bash
   cd Reference-LSTM-VQE
   ```
   - Use `lstm_vqe_original.ipynb` for comparative analysis
   - Or execute `lstm_vqe_original.py` for script version

## Repository Structure

```
LSTM-VQE/
├── LSTM-FC-VQE/                # Novel method implementation
│   ├── novel_lstm_fc_vqe.ipynb # Primary notebook file
│   └── novel_lstm_fc_vqe.py    # Script version of the method
│
├── Reference-LSTM-VQE/         # Reference implementation
│   ├── lstm_vqe_original.ipynb # Original LSTM-VQE notebook
│   └── lstm_vqe_original.py    # Original LSTM-VQE script
│
├── requirements.txt            # Project dependencies
├── LICENSE                     # MIT License
└── README.md                   # Project documentation
```

## Contributing Guidelines

Contributions are welcome through Pull Requests. Please ensure:
1. Adherence to PEP 8 style guidelines
2. Implementation of appropriate test coverage
3. Documentation updates reflecting modifications
4. Clear commit messages describing changes

## Technical Documentation

For detailed technical information about both implementations:
- LSTM and FC architecture specifications
- VQE parameter optimization methodology using PennyLane
- UCCSD circuit configurations and quantum chemistry simulations
- Comparative analysis between methods

Please refer to the code documentation and comments within the implementation files.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Citation

If you use this implementation in your research, please cite:

```bibtex
@software{lstm_vqe_2024,
  title = {LSTM-VQE: LSTM-Enhanced Variational Quantum Eigensolver},
  author = {Lin, Yu-Cheng and Chang, Ran-Yu and Hsu, Pei-Che},
  year = {2024},
  url = {https://github.com/[your-username]/LSTM-VQE},
  type = {Software}
}
``` 