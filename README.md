# RAG

This is a simple implementation of RAG Model

## Requirements
- Python 3.8 or later

#### Install Python using MiniConda

1) Download and install MiniConda from [here](https://docs.anaconda.com/free/miniconda/#quick-command-line-install)

2) Create a new environment using the following command:
```bash
$ conda create -n rag python=3.8
```
3) Activate the environment:
```bash
$ conda activate rag
```

## For better command line interface
```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```

## Installation

### Insatll the required packages

```bash
$ pip install -r requirements.txt
```

### Setup the environment variables

```bash
$ cp .env.example .env
```

Set your environment variables in hte `.env` file. Like
`OPENAI_API_KEY` value.

## Run FastAPI Server

```bash
$ uvicorn main:app --reload --host 0.0.0.0 --port 5000
```
