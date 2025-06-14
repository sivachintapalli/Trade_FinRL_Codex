
# Trade FinRL Codex

Trade FinRL Codex is a FinRL-based trading analysis platform. The goal of the project is to provide tools and examples for building algorithmic trading strategies using the open-source [FinRL](https://github.com/AI4Finance-Foundation/FinRL) framework.

## Installation

1. Install Python 3.10 or newer.
2. Create a virtual environment and activate it:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Directory Structure

```
Trade_FinRL_Codex/
├── data/          # Datasets for training and evaluation
├── notebooks/     # Example Jupyter notebooks
├── src/           # Python modules
└── tests/         # Unit tests
```

## Usage

Run the main application:
```bash
python src/main.py
```

Run the test suite:
```bash
pytest
```
