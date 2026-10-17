# ChartQA: Multimodal Chart Reasoning

Visual and quantitative reasoning over charts using the [ChartQA dataset](https://huggingface.co/datasets/HuggingFaceM4/ChartQA).

## Dependencies

- Python 3.10, virtual environment named `.venv`
- Hugging Face API key (`HF_TOKEN`)


## Run

Start by intialising a python 3.10 virtual env

## Setup Instructions

### Windows (PowerShell)

```
py -3.10 -m venv .venv
.\.venv\Scripts\Activate.ps1
python utils/Bootstrap.py
```

### macOS

```
python3.10 -m venv .venv
source .venv/bin/activate
python utils/Bootstrap.py
```

Key points:

- Use Python 3.10.
- The virtual environment must be named `.venv`.
- Run `Bootstrap.py` only after activating the virtual environment.
- Run these commands from the repository root directory.

## Deploy

_TBD_

## Structure

```text
chartqa/
├── data/          # Dataset loaders
├── readings/
└── requirements.txt
```