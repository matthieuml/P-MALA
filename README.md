## P-MALA

### Installation

Before installing Python packages, it is required to install the `lapacke` package on the system itself for [proxTV](https://github.com/albarji/proxTV).

For Debian-based distribution:
```bash
sudo apt-get install liblapacke-dev
```

For Arch-based distribution:
```
sudo pacman -Sy lapacke
```

Then, you can install the required dependencies using `requirement.txt` with pip:
```bash
pip install -r requirement.txt
```

You can also install the required dependencies using `pyproject.toml` with [Pixi](https://pixi.sh/latest/) or [Poetry](https://python-poetry.org/).