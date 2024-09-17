# LLM DEV DAY
Resources and Notebooks related to talk: [Building with LLMs](https://www.meetup.com/devday-uk/events/303113488/)

## Prerequisites
Make sure you have the following installed
* [python 3.11](https://www.python.org/downloads/)
* [poetry](https://pypi.org/project/poetry/)
* [ollama](https://github.com/ollama/ollama)

## Getting started 

To get staretd, run the following commands

```

 poetry install
 ollama serve &
 ollama pull mistral &
 ollama pull llama3.1:8b &
 ollama pull nomic-embed-text &
 docker run -d -p 8080:8080 -p 50051:50051 cr.weaviate.io/semitechnologies/weaviate &
 poetry run jupyter notebook &

```
