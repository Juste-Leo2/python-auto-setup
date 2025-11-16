# PYTHON-AUTO-SETUP 🚀

Zero-setup Python environments on Windows, powered by `uv`.

This project automates the creation of a self-contained Python environment. **No prior Python installation is required.** The scripts use `uv` to bootstrap a specific Python version and manage all dependencies locally.

## 🚀 Quick Start

1.  **`setup_env_win.bat`**
    Run this first to create the environment. It will download Python and install packages from `requirements.txt`.

2.  **`run_win.bat`**
    Run this to execute `main.py` in the created environment.

## How It Works

-   **`setup_env_win.bat`**: Downloads `uv`, uses it to create a `.venv` with a managed Python interpreter, and installs dependencies.
-   **`run_win.bat`**: Activates the local `.venv` and runs the main script.

## 🙏 Acknowledgements

A huge thanks to the [Astral team](https://github.com/astral-sh/uv) for their incredible work on `uv`.

## 📄 License

Licensed under the Apache 2.0 License.