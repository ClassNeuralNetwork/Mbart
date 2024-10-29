# MBART-50

## Repositório dedicado à exploração prática do modelo MBART-50.

Este repositório contém exemplos que exercitam o modelo MBART-50 (Multilingual BART) desenvolvido pela Facebook AI Research, que realiza tradução automática e outras tarefas de NLP multilinguística. Todos os exemplos foram implementados utilizando a biblioteca [Hugging Face Transformers](https://huggingface.co/).

## Modelos Utilizados

Os modelos aplicados nos exemplos incluem diferentes variantes para atender tarefas específicas:

- **m2m (many-to-many)**: Permite tradução direta entre vários pares de idiomas, oferecendo flexibilidade para tradução multilateral.
- **m2o (many-to-one)**: Direciona diversas entradas em diferentes idiomas para um único idioma de destino, útil para tarefas de resumo ou centralização de informações.
- **o2m (one-to-many)**: Facilita a tradução de um idioma para vários idiomas de saída, ideal para disseminação de informações em múltiplos idiomas.

## Pré-requisitos

- Python 3.8+
- Transformers da Hugging Face
- PyTorch ou TensorFlow (dependendo do backend preferido)

Para utilizar a biblioteca Hugging Face, instale o transformers:

```bash
pip install transformers
```
## Equipe

- [Alan Almeida](https://github.com/AlanTddy) 
- [Dalton Campos](https://github.com/daltonfcampos) 
- [Iverton Emiquison](https://github.com/IVERTON-EMIQUISON) 