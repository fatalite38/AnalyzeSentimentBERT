# Análise de Sentimento com BERT

Este projeto foi desenvolvido como parte do Trabalho de Conclusão de Curso (TCC) e consiste em uma análise de sentimento utilizando o modelo BERT para classificação de sequências. O objetivo é treinar e avaliar um modelo de linguagem pré-treinado do BERT na base de dados do IMDb, que contém críticas de filmes rotuladas como positivas ou negativas.

## Conteúdo

1. [Descrição do Projeto](#descrição-do-projeto)
2. [Requisitos](#requisitos)
3. [Instalação](#instalação)
4. [Uso](#uso)
5. [Estrutura do Projeto](#estrutura-do-projeto)
6. [Limitações](#limitações)
7. [Trabalho de Conclusão de Curso (TCC)](#trabalho-de-conclusão-de-curso-tcc)
8. [Contribuições](#contribuições)

## Descrição do Projeto

O notebook `AnalyzeSentiment.ipynb` contém todo o código necessário para carregar, pré-processar, treinar e avaliar o modelo BERT na base de dados do IMDb. Ele utiliza a biblioteca `transformers` para trabalhar com o modelo BERT e o TensorFlow para treinamento e avaliação.

## Requisitos

- Python 3
- TensorFlow
- Transformers
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Instalação

1. Clone este repositório:
  git clone https://github.com/fatalite38/AnalyzeSentimentBERT.git

2. Instale as dependências:
   pip install
   

## Uso

Para usar o código, siga os seguintes passos:

1. Abra o arquivo `AnalyzeSentiment.ipynb` em um notebook Jupyter.
2. Execute as células do notebook para instalar as bibliotecas necessárias e carregar os dados do IMDB.
3. Treine o modelo BERT em duas épocas usando um otimizador AdamW com um scheduler de aprendizado linear com aquecimento.
4. Avalie o modelo no conjunto de teste e calcule as métricas de desempenho, como precisão, recall e F1-score.
5. Visualize a matriz de confusão e a curva ROC para avaliar a qualidade do modelo.


## Estrutura do Projeto

- `AnalyzeSentiment.ipynb`: Notebook Jupyter contendo o código completo para análise de sentimento com BERT.
- `README.md`: Este arquivo de documentação.
  

## Trabalho de Conclusão de Curso (TCC)

O desenvolvimento deste projeto faz parte do Trabalho de Conclusão de Curso (TCC) em [Nome do Curso] da [Nome da Instituição de Ensino].

Para visualizar o PDF do TCC no Visual Studio Code, siga estas instruções:

1. Certifique-se de ter a extensão "PDF (Preview)" instalada no Visual Studio Code. Você pode encontrá-la no Marketplace de extensões do VS Code.

2. Após instalar a extensão, reinicie o Visual Studio Code.

3. No explorador de arquivos do VS Code, clique com o botão direito no arquivo `Tcc.pdf`.

4. Selecione "Open Preview" (Abrir Pré-visualização) no menu de contexto.

Isso abrirá o PDF do TCC diretamente no Visual Studio Code, permitindo que você visualize e navegue pelo conteúdo sem sair do ambiente de desenvolvimento.
## Limitações

O código está limitado a classificar os comentários do IMDB como positivos ou negativos. Além disso, o código não está treinando o modelo em várias épocas, o que pode ser uma limitação. Por fim, o código não está salvando o modelo treinado, o que pode ser uma limitação se quisermos usar o modelo em outras aplicações.


## Contribuições

Se você encontrar algum erro ou problema no código, ou se tiver alguma sugestão de melhoria, por favor, abra um issue ou envie um pull request. Obrigado!

