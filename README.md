# Sprint 14 - Projeto 14/17 BootCamp TripleTen de Ciências de Dados

<div align="center">
  <img src="https://github.com/Angelaidt/Sprint-14-Film-Junky-Union/blob/main/imagem_sprint_14.png" width="60%">
</div>

# Introdução
A Film Junky Union, uma nova comunidade para entusiastas de filmes clássicos, está desenvolvendo um sistema para filtrar e categorizar resenhas de filmes. 

# Objetivo do Projeto 🎯

O objetivo principal é treinar um modelo de Processamento de Linguagem Natural (NLP) capaz de detectar resenhas negativas com alta precisão, otimizando a experiência dos usuários na plataforma.

⚙️ Requisitos e Metas:
Dataset: Utilização da base de dados do IMDB com rotulagem de polaridade.

Tarefa: Classificação binária de sentimentos (Positivo vs. Negativo).

Métrica de Sucesso: O modelo deve atingir um valor de F1-Score mínimo de 0,85.

Impacto: Automatizar a filtragem de críticas para auxiliar a curadoria da Film Junky Union.

# Estrutura do Repositório
Veja os dados utilizados : 

![Dados Sprint 14 - arquivo  CSV](https://github.com/Angelaidt/Sprint-14-Film-Junky-Union/blob/main/imdb_reviews.zip)


# 🛠️ Tecnologias e Ferramentas

Para alcançar os objetivos deste projeto, foram utilizadas as seguintes bibliotecas e ferramentas da linguagem Python:

Manipulação e Análise de Dados
Pandas & NumPy: Essenciais para a estruturação, limpeza e manipulação do dataset do IMDB.

Matplotlib & Seaborn: Utilizados para a análise exploratória (EDA) e visualização do equilíbrio das classes.

Processamento de Linguagem Natural (NLP)
NLTK / Spacy: Aplicados para a normalização do texto (tokenização, remoção de stopwords e lematização).

Scikit-learn (TfidfVectorizer / CountVectorizer): Para a vetorização do texto, transformando palavras em representações numéricas baseadas em frequência e importância.

Modelagem de Machine Learning
Scikit-learn: Implementação de modelos clássicos como Regressão Logística.

XGBoost: Algoritmo de Gradient Boosting para otimização de performance.

Abordagem com Deep Learning (Transfer Learning)
Hugging Face (Transformers): Utilização da biblioteca para carregar o modelo pré-treinado BERT (Bidirectional Encoder Representations from Transformers), focando em maximizar o F1-Score.

PyTorch : Framework de deep learning utilizado para treinar o modelo BERT sobre os dados do IMDB.

Métricas de Avaliação: Foco total na métrica F1-Score, além de Matriz de Confusão e Curva ROC-AUC.

Ambiente de Desenvolvimento
Jupyter Notebook / VS Code: Para o desenvolvimento iterativo e documentação dos experimentos.
