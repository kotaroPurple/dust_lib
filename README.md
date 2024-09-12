
# Dust-Lib

1. initialize python environment

```bash
uv init --lib
```

2. make files

```txt
dust_lib/
│
├── src/
│   └── dust_lib/
│       └── tools/
|           ├── __init__.py
│           └── my_funcs.py
│
└── pyproject.toml
```

3. install with uv

```bash
uv add dust_lib git+https://github.com/kotaroPurple/dust_lib.git
```

4. update dust_lib

```bash
uv add --reinstall-package dust_lib git+https://github.com/kotaroPurple/dust_lib.git
```
