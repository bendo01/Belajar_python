# Tic Tac Toe PRO

A simple Tic Tac Toe game written in Python using Pygame.

## Prerequisites

You need to have `uv` installed. `uv` is an extremely fast Python package and project manager.

### Installing `uv`

You can install `uv` using one of the following methods:

**macOS and Linux:**
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

**Windows:**
```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

For more details on installation, please refer to the [uv documentation](https://docs.astral.sh/uv/getting-started/installation/).

## Running the App

Since this project requires `pygame`, you can use `uv` to automatically fetch the dependency and run the app in an isolated environment with a single command:

```bash
uv run --with pygame "Game Tic_tac_toe.py"
```

Alternatively, if you prefer creating a virtual environment:

```bash
# Create a virtual environment
uv venv

# Activate it (Linux/macOS)
source .venv/bin/activate
# Or on Windows:
# .venv\Scripts\activate

# Install dependencies
uv pip install pygame

# Run the game
python "Game Tic_tac_toe.py"
```
