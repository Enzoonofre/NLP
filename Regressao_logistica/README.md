# Análise de Sentimentos em Tweets com Regressão Logística

Este projeto tem como objetivo construir um modelo simples de aprendizado de máquina para realizar **análise de sentimentos** em tweets, utilizando técnicas de **Processamento de Linguagem Natural (NLP)**.

## 🔍 Sobre o Projeto

O notebook contém uma explicação passo a passo de como aplicar um pipeline básico de NLP para classificar sentimentos (positivos ou negativos) em textos curtos como tweets. Ao longo do projeto, são abordadas e explicadas funções fundamentais para pré-processamento de texto, extração de características e construção de modelos de classificação usando regressão logística.

A análise de sentimentos é amplamente utilizada no mercado para entender a opinião de usuários sobre produtos, serviços, campanhas políticas, eventos e marcas. É uma ferramenta poderosa para tomada de decisão baseada em dados.

A ideia deste projeto foi inspirada no curso da Coursera **Natural Language Processing Specialization**, especificamente no módulo **Processamento de linguagem natural com classificação e espaços vetoriais**, que faz parte da especialização em Deep Learning.

## 📌 Etapas do Projeto

O projeto está organizado nas seguintes partes:

1. **Importação e exploração do dataset**  
   - Carregamento de tweets rotulados (positivos e negativos) com NLTK.

2. **Pré-processamento dos textos**  
   - Limpeza dos tweets, remoção de ruídos, tokenização, stopwords e stemming.

3. **Análise de frequência**  
   - Construção de um dicionário com as palavras mais frequentes e seus rótulos associados.

4. **Regressão logística**  
   - Implementação do modelo de aprendizado supervisionado para prever sentimentos.

5. **Treinamento do modelo**  
   - Aplicação do gradiente descendente para ajustar os pesos do modelo.

6. **Testando o modelo**  
   - Verificação de previsões com base em novos exemplos.

7. **Verificação de desempenho**  
   - Cálculo da acurácia em um conjunto de teste separado.

8. **Teste seu próprio tweet**  
   - O usuário pode testar frases customizadas e verificar a predição do modelo.

## 🛠️ Tecnologias Utilizadas

- Python
- NLTK (Natural Language Toolkit)
- NumPy
- Regressão Logística (implementada do zero)

## 📈 Aplicações no Mercado

A análise de sentimentos é muito usada em:

- Monitoramento de redes sociais
- Pesquisa de opinião pública
- Análise de feedback de clientes
- Automação de SAC e atendimento
- Marketing direcionado

Compreender como o público se sente em relação a uma marca ou produto pode ser essencial para o sucesso de estratégias comerciais e institucionais.

## ✅ Como usar

Este projeto está em formato de notebook Jupyter/Colab. Basta seguir a sequência das células para acompanhar a explicação e execução do modelo. Todas as funções utilizadas são explicadas no próprio notebook.

---
