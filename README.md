# Modelagem para AI: Gaseificação de Biomassa

Este projeto tem como objetivo construir e comparar três modelos de Machine Learning (ML) — Redes Neurais Artificiais (RNA), Random Forest e SVM — para prever a composição do gás de síntese gerado no processo de gaseificação de biomassa. O trabalho se baseia na dissertação:

Pimentel , Fernanda . Desenvolvimento de Modelos Preditivos Para a  Gaseificação de Biomassa Usando Redes  Neurais Artificiais. 26 May 2022, p. 134.

## Estrutura do Projeto

- **Trabalho_Modelagem.ipynb**: Notebook principal com todo o fluxo de análise, modelagem e comparação dos modelos.
- **BD.xlsx**: Base de dados utilizada para treinamento, teste e validação dos modelos (armazenada no Google Drive).


## Etapas do Projeto(Realizada na Dissertação)

1. **Construção e Tratamento do Banco de Dados**
   - Revisão bibliográfica e extração de variáveis relevantes.
   - Limpeza, filtragem e padronização dos dados.
   - Exclusão de outliers e registros inconsistentes.
   - Divisão dos dados em conjuntos de treino, teste e validação.

2. **Análise Exploratória de Dados**
   - Estatísticas descritivas.
   - Visualização de distribuições e boxplots.
   - Análise de correlação (Spearman) entre variáveis de entrada e saída.
   - Análise de componentes principais (PCA).

3. **Modelagem(Em andamento)**
   - **Rede Neural Artificial (RNA)**: Implementação, avaliação e comparação com o modelo usado na dissertação.
   - **Random Forest**: Implementação e avaliação do modelo.
   - **SVM**: Implementação e avaliação do modelo.

4. **Comparação dos Modelos(Em andamento)**
   - Avaliação de desempenho dos quatro modelos.
   - Discussão dos resultados.

## Como Executar

1. Clone o repositório e abra o notebook [Trabalho_Modelagem.ipynb](Trabalho_Modelagem.ipynb) no Google Colab ou VSCode.
2. Certifique-se de ter acesso ao arquivo `BD.xlsx` no Google Drive.
3. Execute as células do notebook sequencialmente.

## Requisitos

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- prince
- scikit-learn

