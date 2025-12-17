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

## How to use

### Clone repository to your setup
```bash
git clone https://github.com/maxhaustov13-ux/Homework1337.git
cd Homework1337

####Create and activate virtual environment

apt-get update
apt-get install -y python3-venv python3-pip
python3 -m venv .venv
source .venv/bin/activate

####Install dependencies

pip install --upgrade pip
pip install snakemake

####Run workflow

snakemake --cores 1

####Check result
�од
cat result.txt

####Expected output:

Hello from Rivia!

# Homework1337 (Khaustov Maxim)
