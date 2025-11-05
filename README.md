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
│   ├── propaganda.csv            # Dados de investimento em propaganda
│   └── Consumo_cerveja_1.csv     # Dados de consumo de cerveja
│
├── notebooks/                     # Jupyter Notebooks com análises
│   ├── 1 - regressao_linear_simples_propaganda.ipynb
│   ├── 3 - Projeto_Regressão_Múltipla.ipynb
│   └── listas/
│       └── lista_1.ipynb          # Análise de regressão múltipla
│
└── README.md                      # Este arquivo
```

---

## 📊 Conteúdo dos Notebooks

### 1. Regressão Linear Simples - Propaganda
**Arquivo:** `notebooks/1 - regressao_linear_simples_propaganda.ipynb`

Análise completa de regressão linear simples para modelar a relação entre investimento em propaganda e vendas.

**Conteúdo:**
- Análise descritiva dos dados
- Análise de correlação
- Modelagem de regressão linear simples
- Diagnóstico de resíduos
- Interpretação dos modelos

**Dataset:** `data/propaganda.csv`

### 2. Projeto de Regressão Múltipla
**Arquivo:** `notebooks/3 - Projeto_Regressão_Múltipla.ipynb`

Análise de regressão múltipla para modelar o consumo de cerveja.

**Conteúdo:**
- Análise exploratória dos dados
- Modelagem de regressão múltipla
- Diagnóstico e validação do modelo

**Dataset:** `data/Consumo_cerveja_1.csv`

### 3. Lista de Exercícios - Regressão Múltipla
**Arquivo:** `notebooks/listas/lista_1.ipynb`

Análise completa de regressão múltipla para predição de vendas.

**Conteúdo:**
1. **Análise Descritiva** - Explorar características básicas das variáveis
2. **Cálculo de Correlação e Covariância** - Quantificar relações entre variáveis
3. **Modelo de Regressão** - Construir e ajustar modelo de regressão múltipla
4. **Análise de Resíduos** - Avaliar suposições do modelo
5. **Análise de Multicolinearidade** - Verificar dependência entre variáveis explicativas
6. **Análise do Modelo** - Interpretar e avaliar resultados

**Dataset:** `data/propaganda.csv`

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
```

### Instalação

```bash
pip install pandas numpy matplotlib seaborn statsmodels scipy
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
   pip install pandas numpy matplotlib seaborn statsmodels scipy jupyter
   ```

3. **Inicie o Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Abra o notebook desejado** na pasta `notebooks/`

5. **Execute as células** em ordem sequencial

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

### Diagnóstico de Modelos
- **Análise de Resíduos**:
  - Normalidade (testes de Lilliefors, Shapiro-Wilk)
  - Homocedasticidade (teste de Breusch-Pagan)
  - Independência
  - Q-Q plots e gráficos de resíduos

- **Multicolinearidade**:
  - VIF (Variance Inflation Factor)
  - Matriz de correlação entre variáveis explicativas

### Validação e Interpretação
- Métricas de qualidade: R², R² ajustado, AIC, BIC, RMSE, MSE
- Testes de significância (F-statistic, t-tests)
- Interpretação de coeficientes
- Intervalos de confiança

---

## 📊 Datasets

### propaganda.csv
Dataset contendo informações sobre investimentos em diferentes canais de propaganda e suas respectivas vendas.

**Variáveis:**
- `TV`: Investimento em propaganda na TV
- `Radio`: Investimento em propaganda no rádio
- `Jornal`: Investimento em propaganda em jornal
- `Vendas`: Vendas resultantes (variável resposta)

### Consumo_cerveja_1.csv
Dataset contendo informações relacionadas ao consumo de cerveja.

**Variáveis:** (especificar conforme necessário)

---

## 🔬 Conceitos Estatísticos Aplicados

- Regressão Linear Simples e Múltipla
- Método dos Mínimos Quadrados (OLS)
- Coeficiente de Determinação (R²)
- Testes de Hipóteses
- Intervalos de Confiança
- Análise de Variância (ANOVA)
- Diagnóstico de Resíduos
- Multicolinearidade
- Normalidade e Homocedasticidade
- Transformações de Variáveis

---

## 📝 Notas Importantes

- Os notebooks devem ser executados em ordem sequencial
- Certifique-se de que os caminhos dos arquivos CSV estão corretos
- Alguns gráficos podem variar dependendo da versão do matplotlib/seaborn
- Os resultados podem apresentar pequenas variações devido a diferentes versões das bibliotecas

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