# Minimal Snakemake workflow

## What it does 
Creates file `result.txt` with one line:
`Hello from workflow!`

## Requirements
- Debian/Linux (or Docker with Debian)
- Git
- Python 3 + pip
- Snakemake

## Setup
```bash
apt-get update
apt-get install -y python3-venv python3-pip
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -U pip
python -m pip install snakemake

# Homework1337 (Khaustov Maxim)
