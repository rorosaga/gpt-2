# gpt-2

## Environment Setup

Before starting, be sure to create a virtual environment. I recommend using 'uv' to create and manage your virtual environment.

1. To install uv, follow the instructions [here](hthttps://docs.astral.sh/uv/getting-started/installation/).

2. Then, you can create the virtual environment:

```bash
uv venv .venv --python 3.11
```

3. Activate the virtual environment:
```bash
source .venv/bin/activate
```

4. Install the dependencies:
```bash
uv sync
```