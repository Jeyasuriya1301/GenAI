# GenAI

A learning workspace for Generative AI, managed with [uv](https://docs.astral.sh/uv/) for fast Python environment and package management.

## Installation

### 1. Install uv

Use `irm` to download the install script and execute it with `iex`:

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

> Changing the execution policy with `-ExecutionPolicy ByPass` allows running a script downloaded from the internet.

### 2. Install Python 3.13.5

```powershell
uv python install 3.13.5
```

### 3. Create the project directory

```powershell
mkdir GENAI
cd GENAI
```

### 4. Create a virtual environment

```powershell
uv venv genai
```

### 5. Activate the environment

```powershell
genai\Scripts\activate.bat
```

To deactivate the environment:

```powershell
genai\Scripts\deactivate.bat
```

## Managing packages

To install a new package, add it to `requirements.txt`, then install all dependencies with:

```powershell
uv pip install -r requirements.txt
```
