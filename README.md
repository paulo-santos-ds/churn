# Previsão de Churn

## Descrição do Projeto
Este projeto tem como objetivo desenvolver um modelo capaz de prever se um cliente está prestes a deixar um banco fictício. Para isso, são analisados dados sobre o comportamento passado dos clientes e rescisões de contratos com o banco.



## Ferramentas e Bibliotecas Utilizadas
- **Python**: Linguagem principal utilizada para a análise.
- **Pandas**: Biblioteca para manipulação e análise de dados.
- **Sklearn**: Biblioteca para construção de modelos de machine learning.
- **Matplotlib.pyplot**: Biblioteca para construção de gráficos.
- **Seaborn**: Biblioteca para construção de gráficos.

## Tabela
O conjunto de dados possui os seguintes campos:

- `RowNumber` — Índice das strings de dados
- `CustomerId` — Identificador exclusivo do cliente
- `Surname` — Sobrenome
- `CreditScore` — Pontuação de crédito
- `Geography` — País de residência
- `Gender` — Gênero
- `Age` — Idade
- `Tenure` — Período de maturação para o depósito fixo de um cliente (anos)
- `Balance` — Saldo da conta
- `NumOfProducts` — Número de produtos bancários usados pelo cliente
- `HasCrCard` — Cliente possui cartão de crédito (1 - sim; 0 - não)
- `IsActiveMember` — Cliente ativo (1 - sim; 0 - não)
- `EstimatedSalary` — Salário estimado
- `Exited` — O cliente saiu (1 - sim; 0 - não)

## Metodologia

### 1. Análise Exploratória de Dados
- Importar as bibliotecas necessárias.
- Carregar e visualizar os dados.

### 2. Pré-processamento
- Identificar e tratar valores ausentes ou duplicados.

### 3. Preparação do Conjunto para o Modelo
- Identificação das **features** e **target** do modelo.
- Divisão dos conjuntos em treino, teste e validação.
- Ajustando o equilíbrio de classes.

### 4. Construindo e Testando Modelos
- **Regressão Logística**
  - Treino
  - Teste
  - Validação
- Aplicação do modelo com e sem o equilíbrio de classes.

### 5. Métricas de Avaliação
- F1-score
- AUC-ROC

## Resultados
O modelo apresentou bons resultados nas métricas utilizadas, como o F1-score e o AUC-ROC. Embora o modelo não atinja o valor máximo em ambas as métricas, seu desempenho é aceitável para ser colocado em uso. Além disso, a Curva ROC indica que ele apresenta resultados superiores ao modelo aleatório.

## Aprendizados
- **Análise de dados**: Interpretação e extração de insights valiosos a partir de grandes volumes de dados.
- **Preparação do conjunto para Machine Learning**: Separação do conjunto original em treino e teste, além da seleção das features e target do modelo.
- **Equilíbrio de classes**: Ajuste das features do modelo para reduzir o viés de uma classe.
- **Aplicação de modelos de Machine Learning**: Aplicação, seleção de hiperparâmetros, teste e avaliação do modelo.
- **Documentação de projetos**: Elaboração de documentação clara e detalhada para garantir que o projeto seja compreensível e replicável.
- **Utilização de bibliotecas e ferramentas**: Aplicação prática de diversas bibliotecas e ferramentas do ecossistema Python.
- **Tomada de decisões baseadas em dados**: Uso de insights derivados da análise de dados para orientar decisões estratégicas.

## 🛠️ Instalação

1. Clone este repositório
2. Instale as dependências listadas acima
3. Execute o aplicativo:


