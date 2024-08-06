# Настройка Ubuntu 24.04

```bash
sudo apt update

python3 -m venv ./env
source ./env/bin/activate

pip install torch torchvision --index-url https://download.pytorch.org/whl/cu124
pip install jupyter tqdm matplotlib
```
