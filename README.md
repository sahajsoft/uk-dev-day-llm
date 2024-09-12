# LLM DEV DAY
Resources and Notebooks related to talk: [Building with LLMs](https://www.meetup.com/devday-uk/events/303113488/)

## Prerequisites
Make sure you have the following installed
* [python 3.11](https://www.python.org/downloads/)
* [poetry](https://pypi.org/project/poetry/)
* [ollama](https://github.com/ollama/ollama)
* [notebook](https://pypi.org/project/notebook/)

## Getting started 

To get staretd, run the following commands

```

 poetry install
 ollama serve &
 ollama pull mistral &
 ollama pull nomic-embed-text &
 poetry run jupyter notebook &

```
