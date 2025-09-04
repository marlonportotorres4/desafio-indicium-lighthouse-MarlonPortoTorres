# Desafio de Ciência de Dados - Consultoria e Previsão para a PProductions

## 1. Objetivo do Projeto

Este projeto foi desenvolvido como solução para o desafio de Ciência de Dados da Indicium. O objetivo é atuar como um consultor para o estúdio de Hollywood "PProductions", realizando uma análise detalhada sobre um dataset de filmes do IMDb para extrair insights e construir um modelo preditivo.

O modelo de Machine Learning desenvolvido ao final do projeto é capaz de prever a nota IMDB de um filme com base em suas características, como gênero, diretor, elenco, duração e faturamento.

---

## 2. Como Executar o Projeto

Existem duas maneiras de executar este projeto:

### 🚀 Execução Rápida (Google Colab)

A maneira mais simples de executar este projeto é diretamente no seu navegador através do Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/marlonportotorres4/desafio-indicium-lighthouse-MarlonPortoTorres/blob/main/LH_CD_MARLONPORTOTORRES.ipynb)

**Instruções:**
1. Clique no botão "Open In Colab" acima.
2. **Importante:** Após abrir o notebook, você precisará fazer o upload do dataset `desafio_indicium_imdb.csv` para o ambiente do Colab. Para isso, clique no ícone de pasta na barra lateral esquerda e depois no botão "Fazer upload para o armazenamento da sessão".
3. Com o dataset carregado, você pode executar todas as células do notebook.

---

## 3. Estrutura do Repositório

* **`LH_CD_MARLONPORTOTORRES.ipynb`**: O Jupyter Notebook com todo o desenvolvimento do projeto.
* **`modelo_previsao_imdb.pkl`**: O arquivo do modelo final treinado, pronto para uso.
* **`desafio_indicium_imdb.csv`**: Dataset contendo tudo necessário para o funcionamento do código.
* **`README.md`**: Esta documentação.

## 4. Resumo da Solução

A análise exploratória revelou que o sucesso de um filme é multifatorial, com destaque para a importância do gênero Drama, o poder de diretores e estrelas consagradas, e a fraca correlação entre o sucesso de bilheteria e a aclamação da crítica/público.

Para a modelagem, foi desenvolvido um pipeline de pré-processamento robusto e foram comparados dois modelos de regressão. O modelo final, um **RandomForestRegressor**, alcançou um RMSE (Root Mean Squared Error) de aproximadamente **0.1954**, demonstrando alta precisão na previsão das notas IMDB.

## 5. Contato

Este projeto foi desenvolvido por **Marlon Torres**. Agradeço pela oportunidade de participar deste desafio.

Para mais informações, entre em contato através do LinkedIn:

* **LinkedIn:** [https://www.linkedin.com/in/marlon-porto-torres/](https://www.linkedin.com/in/marlon-porto-torres/)
