# Hello Vectors - Word Embedding Explorations

Este projeto explora conceitos fundamentais de **Processamento de Linguagem Natural (NLP)** por meio do uso de **word embeddings**, representando palavras como vetores em um espaço multidimensional.

## Objetivo

Demonstrar como vetores de palavras podem ser utilizados para prever analogias semânticas, medir similaridade entre termos e representar relações linguísticas de forma matemática.

## O que o projeto faz

- Realiza analogias entre palavras (exemplo: *Athens é para Greece assim como Cairo é para Egypt*).
- Utiliza **similaridade cosseno** e **distância euclidiana** para medir proximidade entre palavras.
- Aplica **PCA (Análise de Componentes Principais)** para reduzir a dimensionalidade dos vetores e facilitar a visualização em 2D.
- Avalia a acurácia das predições com base em embeddings pré-treinados.

## Tecnologias utilizadas

- Python
- Numpy
- Pandas
- Matplotlib
- Word2Vec (vetores pré-treinados do Google News)

## Requisitos

Para rodar o projeto, você precisará dos seguintes arquivos:

- `word_embeddings_subset.p`: subconjunto de embeddings Word2Vec.
- `capitals.txt`: pares de cidades e países usados nas comparações.

## Como executar

1. Clone este repositório.
2. Certifique-se de que os arquivos `word_embeddings_subset.p`, `capitals.txt` e `utils.py`  estejam no diretório correto.
3. Abra o notebook em um ambiente como Jupyter Notebook.
4. Execute as células para carregar os dados, realizar os cálculos e visualizar os resultados das comparações e da PCA.

## Estrutura do Projeto

```
├── word_embeddings_subset.p
├── capitals.txt
├── utils.py
├── Word_embbeding.ipynb
└── README.md
```

## Licença

Este projeto é livre para uso educacional e acadêmico.

---

Sinta-se à vontade para sugerir melhorias ou utilizar os exemplos como base para seus próprios estudos em NLP.
