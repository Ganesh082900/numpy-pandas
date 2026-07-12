```markdown
# NumPy & Pandas

A Python project for learning and experimenting with **NumPy** and **Pandas**.

## Project Structure

```

numpy-pandas/
│
├── .venv/                 # Virtual environment (not tracked by Git)
├── .gitignore
├── requirements.txt
├── main.py
├── README.md
└── ...

````

## Prerequisites

- Python 3.14 or later
- Git (optional)

## Getting Started

### 1. Clone the repository

```bash
git clone <repository-url>
cd numpy-pandas
````

### 2. Create a virtual environment

#### Windows (PowerShell)

```powershell
python -m venv .venv
```

### 3. Activate the virtual environment

#### Windows (PowerShell)

```powershell
.\.venv\Scripts\Activate.ps1
```

#### Windows (Command Prompt)

```cmd
.venv\Scripts\activate.bat
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

## Running the Project

```bash
python main.py
```

## Installing New Packages

To install a package:

```bash
pip install <package-name>
```

Update `requirements.txt` after installing new packages:

```bash
pip freeze > requirements.txt
```

## Deactivating the Virtual Environment

```bash
deactivate
```

## Common Commands

Check Python version:

```bash
python --version
```

Check installed packages:

```bash
pip list
```

Upgrade pip:

```bash
python -m pip install --upgrade pip
```

## Notes

* The `.venv/` directory is excluded from Git using `.gitignore`.
* Always activate the virtual environment before installing packages or running the project.
* Commit `requirements.txt` whenever project dependencies change.

## License

This project is for learning and experimentation.

```
```
