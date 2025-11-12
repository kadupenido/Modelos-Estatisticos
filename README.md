# Modelos Estatísticos

## 📚 Disciplina
**Modelos Estatísticos**  
Curso de Pós-Graduação em **Inteligência Artificial e Aprendizado de Máquina**  
Pontifícia Universidade Católica de Minas Gerais (PUC Minas)

---

## 📋 Sobre o Projeto

Este repositório contém análises estatísticas e modelos de regressão desenvolvidos como parte da disciplina de Modelos Estatísticos. O projeto abrange desde regressão linear simples até modelos de regressão múltipla, com foco em análise exploratória de dados, diagnóstico de modelos e validação de pressupostos estatísticos.

## 🎯 Objetivos

- Aplicar conceitos teóricos de modelos estatísticos em problemas práticos
- Desenvolver habilidades em análise exploratória de dados
- Implementar e avaliar modelos de regressão linear simples e múltipla
- Realizar diagnósticos estatísticos completos dos modelos
- Interpretar resultados e extrair insights relevantes

---

## 📁 Estrutura do Projeto

```
Modelos Estatisticos/
│
├── data/                          # Conjuntos de dados
│   ├── propaganda (2).csv        # Dados de investimento em propaganda
│   ├── preco_carro.csv           # Dados de preços de automóveis
│   └── rigidez.csv               # Dados de rigidez
│
├── notebooks/                     # Jupyter Notebooks com análises
│   ├── aulas/                    # Notebooks das aulas por semana
│   │   ├── semana_1/            # Semana 1: Medidas resumo, correlação e regressão linear simples
│   │   │   ├── 1 - medidas_resumo.ipynb
│   │   │   ├── 2 - Medidas_correlacao.ipynb
│   │   │   ├── 3 - correlacao_regressao_linear.ipynb
│   │   │   └── 4 - regressao_linear_simples_propaganda.ipynb
│   │   ├── semana_2/            # Semana 2: Regressão linear simples e múltipla
│   │   │   ├── 1 - regressao_linear_simples_propaganda.ipynb
│   │   │   ├── 2 - Regressao_linear_simples_mtcars.ipynb
│   │   │   └── 3 - Projeto_Regressão_Múltipla.ipynb
│   │   └── semana_3/            # Semana 3: Transformações de variáveis
│   │       ├── 2 - Transformação de variáveis com Pyhton.ipynb
│   │       └── 5 -Transformação de Box- Cox.ipynb
│   └── listas/                   # Listas de exercícios
│       ├── lista 1.1.ipynb      # Regressão múltipla - Propaganda
│       └── lista 1.2.ipynb      # Regressão múltipla - Preço de Carros
│
└── README.md                      # Este arquivo
```

---

## 📊 Conteúdo dos Notebooks

### 📚 Aulas por Semana

#### Semana 1: Fundamentos e Análise Exploratória
- **1 - medidas_resumo.ipynb**: Medidas de tendência central e dispersão
- **2 - Medidas_correlacao.ipynb**: Cálculo e interpretação de correlação
- **3 - correlacao_regressao_linear.ipynb**: Introdução à regressão linear
- **4 - regressao_linear_simples_propaganda.ipynb**: Aplicação de regressão linear simples

#### Semana 2: Regressão Linear Simples e Múltipla
- **1 - regressao_linear_simples_propaganda.ipynb**: Regressão linear simples com dados de propaganda
- **2 - Regressao_linear_simples_mtcars.ipynb**: Regressão linear simples com dataset mtcars
- **3 - Projeto_Regressão_Múltipla.ipynb**: Projeto completo de regressão múltipla

#### Semana 3: Transformações de Variáveis
- **2 - Transformação de variáveis com Pyhton.ipynb**: Técnicas de transformação de variáveis (Label Encoding, StandardScaler, MinMaxScaler)
- **5 -Transformação de Box- Cox.ipynb**: Transformação de Box-Cox para normalização de dados

---

### 📝 Listas de Exercícios

### 1. Lista 1.1 - Regressão Múltipla: Predição de Vendas
**Arquivo:** `notebooks/listas/lista 1.1.ipynb`

Análise completa de regressão múltipla para predizer vendas a partir de investimentos em diferentes canais de propaganda.

**Conteúdo:**
1. **Análise Descritiva** - Explorar características básicas das variáveis
2. **Cálculo de Correlação e Covariância** - Quantificar relações entre variáveis
3. **Modelo de Regressão** - Construir e ajustar modelo de regressão múltipla
4. **Análise de Resíduos** - Avaliar suposições do modelo (normalidade, homocedasticidade, independência)
5. **Análise de Multicolinearidade** - Verificar dependência entre variáveis explicativas (VIF)
6. **Análise do Modelo** - Interpretar e avaliar resultados (R², RMSE, MAE)

**Dataset:** `data/propaganda (2).csv`

**Variáveis:**
- `TV`: Investimento em propaganda na TV
- `Radio`: Investimento em propaganda no rádio
- `Jornal`: Investimento em propaganda em jornal
- `Vendas`: Vendas resultantes (variável resposta)

---

### 2. Lista 1.2 - Regressão Múltipla: Previsão de Preço de Automóveis
**Arquivo:** `notebooks/listas/lista 1.2.ipynb`

Análise comparativa de três modelos de regressão múltipla para prever o preço de automóveis usando diferentes conjuntos de variáveis preditoras.

**Modelos Implementados:**
- **Modelo 1**: Regressão com todas as variáveis disponíveis
- **Modelo 2**: Regressão com as 3 variáveis mais correlacionadas com o preço
- **Modelo 3**: Regressão com as 5 variáveis mais correlacionadas com o preço

**Conteúdo para cada modelo:**
1. **Análise Descritiva** - Estatísticas descritivas e visualizações
2. **Cálculo de Correlação e Covariância** - Matrizes de correlação e covariância
3. **Modelo de Regressão** - Ajuste do modelo OLS com `statsmodels`
4. **Análise de Resíduos** - Diagnóstico completo (gráficos, Q-Q plots, Durbin-Watson)
5. **Análise de Multicolinearidade** - Cálculo de VIF para cada variável
6. **Análise de Outliers** - Identificação usando resíduos padronizados, distância de Cook e leverage
7. **Comparação de Modelos** - Métricas comparativas (R², R² ajustado, RMSE, MAE, AIC, BIC)

**Dataset:** `data/preco_carro.csv`

**Variáveis:**
- `on road old`: Preço antigo na estrada
- `on road now`: Preço atual na estrada
- `years`: Idade do veículo (anos)
- `km`: Quilometragem
- `rating`: Avaliação do veículo
- `condition`: Condição do veículo
- `economy`: Economia de combustível
- `top speed`: Velocidade máxima
- `hp`: Potência (cavalos)
- `torque`: Torque
- `current price`: Preço atual (variável resposta)

---

## 📦 Dependências

### Bibliotecas Python Principais

```python
# Manipulação de dados
pandas
numpy

# Visualização
matplotlib
seaborn

# Modelos estatísticos
statsmodels
scipy

# Métricas de avaliação
scikit-learn
```

### Instalação

```bash
pip install pandas numpy matplotlib seaborn statsmodels scipy scikit-learn
```

Ou utilizando um ambiente virtual:

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
venv\Scripts\activate     # Windows

pip install -r requirements.txt
```

---

## 🚀 Como Executar

### Pré-requisitos
- Python 3.7 ou superior
- Jupyter Notebook ou JupyterLab

### Passos

1. **Clone o repositório** (ou navegue até o diretório do projeto)

2. **Instale as dependências**
   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels scipy scikit-learn jupyter
   ```

3. **Inicie o Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
   Ou use JupyterLab:
   ```bash
   jupyter lab
   ```

4. **Abra o notebook desejado**:
   - Para aulas: `notebooks/aulas/semana_X/`
   - Para listas: `notebooks/listas/`

5. **Execute as células** em ordem sequencial (importante para manter as variáveis no ambiente)

---

## 📈 Metodologia

### Análise Exploratória de Dados (EDA)
- Estatísticas descritivas
- Visualizações (histogramas, boxplots, scatter plots)
- Identificação de outliers
- Verificação de valores ausentes

### Modelagem
- **Regressão Linear Simples**: Modelo com uma variável explicativa
- **Regressão Múltipla**: Modelo com múltiplas variáveis explicativas
- Seleção de variáveis
- Ajuste de modelos usando `statsmodels`
- **Transformações de Variáveis**: 
  - Transformação de Box-Cox
  - Normalização e padronização
  - Encoding de variáveis categóricas

### Diagnóstico de Modelos
- **Análise de Resíduos**:
  - Normalidade (Q-Q plots, histogramas)
  - Homocedasticidade (gráficos de resíduos vs valores ajustados)
  - Independência (estatística de Durbin-Watson)
  - Resíduos padronizados

- **Multicolinearidade**:
  - VIF (Variance Inflation Factor)
  - Matriz de correlação entre variáveis explicativas
  - Interpretação de valores de VIF

- **Análise de Outliers**:
  - Resíduos padronizados
  - Distância de Cook
  - Leverage (hat values)
  - Resíduos studentizados

### Validação e Interpretação
- Métricas de qualidade: R², R² ajustado, AIC, BIC, RMSE, MSE
- Testes de significância (F-statistic, t-tests)
- Interpretação de coeficientes
- Intervalos de confiança

---

## 📊 Datasets

### propaganda (2).csv
Dataset contendo informações sobre investimentos em diferentes canais de propaganda e suas respectivas vendas.

**Variáveis:**
- `TV`: Investimento em propaganda na TV
- `Radio`: Investimento em propaganda no rádio
- `Jornal`: Investimento em propaganda em jornal
- `Vendas`: Vendas resultantes (variável resposta)

**Uso:** Análise de regressão múltipla para predição de vendas (Lista 1.1)

---

### preco_carro.csv
Dataset contendo informações detalhadas sobre automóveis e seus preços.

**Variáveis:**
- `v.id`: Identificador único do veículo
- `on road old`: Preço antigo na estrada
- `on road now`: Preço atual na estrada
- `years`: Idade do veículo em anos
- `km`: Quilometragem do veículo
- `rating`: Avaliação do veículo
- `condition`: Condição do veículo
- `economy`: Economia de combustível
- `top speed`: Velocidade máxima
- `hp`: Potência em cavalos
- `torque`: Torque do motor
- `current price`: Preço atual do veículo (variável resposta)

**Uso:** Análise comparativa de três modelos de regressão múltipla (Lista 1.2)

---

### rigidez.csv
Dataset contendo informações sobre rigidez (detalhes específicos podem variar conforme o contexto da análise).

**Uso:** Utilizado em análises de transformação de variáveis e modelagem estatística.

---

## 🔬 Conceitos Estatísticos Aplicados

- **Regressão Linear Múltipla**
  - Método dos Mínimos Quadrados (OLS)
  - Seleção de variáveis
  - Comparação de modelos

- **Métricas de Avaliação**
  - Coeficiente de Determinação (R²)
  - R² Ajustado
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)
  - AIC (Akaike Information Criterion)
  - BIC (Bayesian Information Criterion)

- **Diagnóstico de Modelos**
  - Análise de Resíduos
  - Normalidade dos resíduos (Q-Q plots)
  - Homocedasticidade
  - Independência (Durbin-Watson)
  - Multicolinearidade (VIF)
  - Análise de Outliers

- **Transformações de Variáveis**
  - Transformação de Box-Cox
  - Normalização (StandardScaler, MinMaxScaler)
  - Encoding de variáveis categóricas
  - Transformações logarítmicas e exponenciais

- **Conceitos Avançados**
  - Distância de Cook
  - Leverage (hat values)
  - Resíduos studentizados
  - Matriz de correlação e covariância

---

## 📝 Notas Importantes

- **Ordem de Execução**: Os notebooks devem ser executados em ordem sequencial, pois as células dependem de variáveis definidas anteriormente
- **Caminhos dos Arquivos**: 
  - Notebooks em `notebooks/listas/` usam caminhos relativos (`../../data/`)
  - Notebooks em `notebooks/aulas/` podem usar caminhos relativos ou absolutos dependendo da estrutura
  - Certifique-se de ajustar os caminhos conforme necessário
- **Versões das Bibliotecas**: Alguns gráficos podem variar dependendo da versão do matplotlib/seaborn
- **Resultados**: Os resultados podem apresentar pequenas variações devido a diferentes versões das bibliotecas, mas as conclusões devem ser consistentes
- **Performance**: Para datasets grandes, algumas análises (como VIF) podem demorar alguns segundos
- **Estrutura de Aprendizado**: Recomenda-se seguir a ordem das semanas (semana_1 → semana_2 → semana_3) para melhor compreensão dos conceitos

---

## 🤝 Contribuições

Este é um projeto acadêmico desenvolvido como parte do curso de Pós-Graduação em Inteligência Artificial e Aprendizado de Máquina da PUC Minas.

---

## 📄 Licença

Este projeto é destinado exclusivamente para fins educacionais e acadêmicos.

---

## 👨‍🎓 Autor

Desenvolvido como parte do curso de **Pós-Graduação em Inteligência Artificial e Aprendizado de Máquina** da **PUC Minas**.

---

## 📚 Referências

- Montgomery, D. C., Peck, E. A., & Vining, G. G. (2021). *Introduction to Linear Regression Analysis*. Wiley.
- James, G., Witten, D., Hastie, T., & Tibshirani, R. (2021). *An Introduction to Statistical Learning*. Springer.
- Hastie, T., Tibshirani, R., & Friedman, J. (2009). *The Elements of Statistical Learning*. Springer.

---

## 🔗 Links Úteis

- [Documentação do Statsmodels](https://www.statsmodels.org/stable/index.html)
- [Documentação do Pandas](https://pandas.pydata.org/docs/)
- [Documentação do Matplotlib](https://matplotlib.org/)
- [Documentação do Seaborn](https://seaborn.pydata.org/)

---