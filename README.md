[Linkedin](https://linkedin.com/in/delonrocha/)
# Análise Preditiva de Compras em Site Imobiliário

## **Resumo do Projeto**

O projeto teve como objetivo construir um modelo de classificação para prever a compra de usuários em um site imobiliário, utilizando um dataset fictício com 200 registros e 6 colunas. Iniciou-se com uma **Análise Exploratória dos Dados**, identificando distribuições, correlações e valores ausentes. No **Pré-Processamento dos Dados**, valores ausentes foram tratados e variáveis categóricas foram codificadas via *One-Hot Encoding*. O dataset foi então dividido em conjuntos de treino (70%) e teste (30%). Foi treinado um **Modelo de Árvore de Decisão**, que obteve uma acurácia de 58%. A avaliação revelou que o modelo é eficaz para prever não compradores, mas tem dificuldades em identificar compradores, evidenciado por uma baixa taxa de recall e F1-Score para a classe positiva. A **Importância das Variáveis** destacou que o tempo no site e a idade são os principais fatores influentes na previsão. Recomenda-se melhorar o modelo ajustando hiperparâmetros, balanceando os dados, explorando outros algoritmos e realizando engenharia de recursos para aumentar sua eficácia.

### **Índice**

1. **Desafio Prático Ciência de Dados VExpenses**
   - Objetivo do Desafio

2. **Introdução**
   - Objetivo do Projeto
   - Estrutura do Dataset

3. **1. Análise Exploratória dos Dados**
   - Métodos Utilizados
   - Distribuição das Variáveis
     - Idade
     - Renda Anual
     - Tempo no Site
     - Gênero
     - Anúncio Clicado
   - Tabelas de Frequência e Estatísticas Descritivas
   - Insights Identificados

   3.1 **Distribuição das Variáveis**
   
   3.2 **Possíveis Relações entre as Variáveis Independentes e a Variável Alvo (Compra)**
   
   3.3 **Identificação de Valores Ausentes ou Inconsistências nos Dados**
     - Pipeline de Identificação
     - Estratégias de Tratamento Sugeridas

4. **2. Pré-Processamento dos Dados**
   - Tratamento de Valores Ausentes
   - Codificação de Variáveis Categóricas
   - Divisão em Conjuntos de Treino e Teste

   4.1 **Tratamento de Valores Ausentes e Pré-Processamento dos Dados**
   
   4.2 **Realização de Codificação para Variáveis Categóricas**
   
   4.3 **Dividir os Dados em Conjuntos de Treino e Teste**

5. **3. Construção e Avaliação do Modelo de Classificação**
   - Construção do Modelo
     - Escolha do Modelo
     - Treinamento do Modelo
   - Avaliação do Modelo Utilizando Métricas Apropriadas
     - Predições no Conjunto de Teste
     - Cálculo da Acurácia
     - Relatório de Classificação
     - Matriz de Confusão
   - Resultados Obtidos

   5.1 **Construção do Modelo de Classificação**
   
   5.2 **Avaliação do Modelo Utilizando Métricas Apropriadas**

6. **4. Interpretação dos Resultados**
   - Importância das Variáveis
   - Conclusão sobre a Efetividade do Modelo
   - Próximos Passos

---
### **Resumo das Técnicas e Tecnologias**

#### **Análise e EDA:**
- Estatística Descritiva  
- Curva de Densidade de Kernel  
- Matriz de Correlação de Pearson  
- Boxplots  

#### **Pré-Processamento:**
- Tratamento de Valores Ausentes (Mediana e Moda)  
- Correção de Inconsistências  
- Normalização (*Standard Scaler*)  
- Codificação de Variáveis Categóricas (*One-Hot Encoding*)  
- Divisão de Dados (*Train-Test Split*)  

#### **Modelagem:**
- Árvore de Decisão (*DecisionTreeClassifier*)  

#### **Avaliação:**
- Acurácia, Precisão, Recall, F1-Score  
- Matriz de Confusão  
- Relatório de Classificação  

#### **Ferramentas e Tecnologias:**
- **Linguagem:** Python  
- **Bibliotecas:** Pandas, NumPy, scikit-learn, Matplotlib, Seaborn  

#### **Abordagens Adicionais:**
- *Feature Importance*  
- Consideração de Técnicas para Balanceamento de Classes  
- Engenharia de Recursos  
