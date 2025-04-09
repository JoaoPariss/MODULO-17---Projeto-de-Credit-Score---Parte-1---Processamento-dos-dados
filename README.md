# MODULO-17---Projeto-de-Credit-Score---Parte-1---Processamento-dos-dados
Este projeto tem como objetivo realizar o pré-processamento e análise exploratória de um conjunto de dados, com foco em tratamento de variáveis categóricas, análise de correlação e preparação dos dados para modelagem.

---

## 🧩 Etapa 1: Verificação e Tratamento Inicial dos Dados

- **A) Verificação dos tipos de dados**
  - Verificados os tipos das variáveis e aplicadas transformações quando necessário, como conversão de tipos e ajustes em dados categóricos.

- **B) Tratamento de dados faltantes**
  - Identificadas colunas com dados ausentes.
  - Realizado tratamento com justificativas baseadas na proporção de valores faltantes e impacto analítico.

- **C) Verificação de erros nas variáveis categóricas**
  - Analisados valores únicos de variáveis categóricas.

---

## 📊 Etapa 2: Análise Exploratória 

- **A) Análise univariada - Variáveis numéricas**
  - Utilização da função `describe()` para obter medidas estatísticas.
  - Visualização de possíveis outliers com histogramas e boxplots.
  - Insights extraídos sobre tendências centrais, dispersão e anomalias.

- **B) Análise univariada - Variáveis categóricas**
  - Geração de gráficos de barras para entender a distribuição das categorias.
  - Extração de insights relevantes sobre o comportamento dos dados.

- **C) Identificação de outliers**
  - Verificação detalhada dos valores extremos nas variáveis numéricas.

- **D) Análise bivariada**
  - Investigação de relações entre variáveis por meio de gráficos e análise visual:
    - Idade x Estado Civil
    - Score de Crédito x Escolaridade
    - Salário x Idade
    - Salário x Score de Crédito
    - Score de Crédito x Tipo de Propriedade da Casa

---

## 🔍 Etapa 3: Tratamento Final e Preparação para Modelagem

- **A) Análise de correlação**
  - Criação de matriz de correlação 
  - Identificação de possíveis relações entre variáveis numéricas.

- **B) Interpretação das correlações**
  - Avaliação das correlações encontradas e justificativas para possíveis relações lógicas entre as variáveis.

- **C) Codificação de variáveis categóricas**
  - Aplicação de técnicas de codificação:
    - `One-Hot Encoding` para variáveis nominais.
    - `Label Encoding` e `Ordinal Encoding` para variáveis com ordem lógica (ex: Education e Credit Score).
  - Remoção das colunas categóricas originais após codificação.

- **D) Nova análise de correlação com variáveis codificadas**
  - Verificação do impacto das variáveis categóricas transformadas nas correlações gerais do dataset.

- **E) Separação da base em treino e teste**
  - Divisão dos dados em conjuntos de treino e teste com `train_test_split`.
  - Verificação das dimensões com `shape`.

- **F) Verificação de balanceamento da variável target (Score de Crédito)**
  - Visualização da distribuição das classes.
  - Análise do grau de desbalanceamento da variável-alvo.

- **G) Balanceamento da base de treino**
  - Aplicação de técnicas de balanceamento (ex: over/undersampling) **somente** na base de treino, preservando a integridade da base de teste.

---

## 🛠 Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## ✅ Status do Projeto

✔️ Concluído – dados tratados, analisados e prontos para aplicação de modelos de machine learning.
