# mini-rag

Minimal Retrieval-Augmented Generation (RAG) example for question answering.

## Prerequisites

- Python 3.8 or later

## Install Python using Miniconda

1. Download and install Miniconda from: https://docs.anaconda.com/free/miniconda/#quick-command-line-install
2. Create a new environment:
```bash
conda create -n mini-rag python=3.8
```
3. Activate the environment:
```bash
conda activate mini-rag
```

4. Optionally customize your shell prompt for readability (bash/zsh):
```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```

# Installation

### Install the required packages

```bash
$ pip install -r requirements.txt
```

### Install the environment variables
```bash
cp .env.example .env
```

Set your environment variables in the `.env` file. Like `OPENAI_API_KEY` value.
 
## Dependencies

- If the project includes a `requirements.txt`, install dependencies with:
```bash
pip install -r requirements.txt
```
- Otherwise, install the main libraries you need (example):
```bash
pip install transformers sentence-transformers faiss-cpu
```

## Quickstart

- Add a short usage example here describing how to run the app. Example placeholder:
```bash
python -m mini_rag  # replace with the actual run command
```

## Data

- Place your documents under a `data/` directory or configure the path in the project's config. Include preprocessing or indexing steps here.

## Development & Testing

- Run tests (if present):
```bash
pytest
```

## Contributing

- Contributions are welcome. Open a PR and include a short description of your change.

## License

- See the `LICENSE` file for license details.

---

If you'd like, I can add a concrete quickstart command and a small example Q&A output — tell me the actual run command or the entry point for this project and I'll fill it in.