# Install instructions

## Python dependencies

```bash
pip install -U pip install -U distro requests packaging docopt-ng ruamel.yaml jinja2 toml tomli-w
```

## Fedora dependencies

```bash
# Tested Fedora 39 41
dnf install -y python3-distro python3-docopt python3-ruamel-yaml python3-jinja2 python3-jinja2-cli python3-toml python3-tomli-w

# Fedora 42
# dotdrop 1.15
dnf install -y python3-distro python3-docopt-ng python3-ruamel-yaml python3-jinja2 python3-jinja2-cli python3-toml python3-tomli-w
```

## Use

```bash
git submodule update --init --recursive
./dotdrop/dotdrop.sh install
```
