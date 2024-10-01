# nokku

## Prepare python environment

```
python3 -m venv .venv

source .venv/bin/activate

python3 -m pip install scapy
```

## Run packet.py

```bash
sudo .venv/bin/python3 packet.py
```

### Alternative way?:

```bash
sudo setcap cap_net_raw+eip $(which python3)
```

## Run service

```bash
# Run in place or build
./nokku
```

## Send package
