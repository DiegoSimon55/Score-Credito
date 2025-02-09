# **📌 Análise e Balanceamento de Score de Crédito**

## **📖 Objetivo do Projeto**
Este projeto tem como objetivo **analisar os fatores que influenciam o Score de Crédito** e entender como variáveis demográficas e financeiras impactam esse indicador. Além disso, aborda o problema de **desbalanceamento dos dados** e aplica técnicas para melhorar a representatividade das classes, garantindo um conjunto de dados mais adequado para futuras modelagens preditivas.

---

## **🛠 Ferramentas e Tecnologias Utilizadas**
- **Linguagem:** Python
- **Ambiente:** Jupyter Notebook
- **Bibliotecas:**
  - **Pandas**: Manipulação e análise de dados.
  - **Seaborn & Matplotlib**: Visualização de dados.
  - **Scikit-Learn**: Modelagem, processamento e balanceamento de dados.

---

## **📊 Etapas do Projeto**

### **1️⃣ Exploração e Limpeza dos Dados**
- Verificação dos **tipos de dados** e tratamento de valores nulos.
- Identificação e tratamento de **outliers**.
- Conversão de variáveis categóricas usando **Label Encoding**.

### **2️⃣ Análises Estatísticas e Gráficas**
- **Análise Univariada**: Distribuição das variáveis categóricas e numéricas.
- **Análise Bivariada**: Correlação entre variáveis como **Escolaridade x Renda** e **Idade x Score de Crédito**.
- **Matriz de Correlação** para identificar **relações fortes entre variáveis**.

### **3️⃣ Tratamento do Desbalanceamento**
- Identificação do **desbalanceamento do Score de Crédito**.
- Aplicação de **Oversampling (Scikit-Learn)** para balancear a base de treino.
- Visualização do impacto do balanceamento com **gráficos de distribuição**.

---

## **📈 Conclusão**
- Foi identificada uma **forte correlação entre Idade e Renda**, sugerindo que quanto maior a idade, maior a tendência de uma pessoa ter um rendimento maior.
- A **posse de imóvel tem relação com estado civil e renda**, indicando que pessoas casadas e com maior renda têm maior probabilidade de serem proprietárias.
- O **desbalanceamento inicial do Score de Crédito foi reduzido**, tornando a distribuição das classes mais homogênea. No entanto, algumas classes ainda estão menos representadas e podem impactar modelos preditivos.

---

## **📁 Estrutura do Projeto**
```
📂 credit-score-analysis
│── 📄 README.md  # Descrição do projeto
│── 📄 credit_score_analysis.ipynb  # Notebook com a análise
│── 📄 requirements.txt  # Dependências do projeto
│── 📂 data  # Base de dados utilizada
│── 📂 images  # Gráficos gerados na análise
```

---

## **📌 Como Executar o Projeto**
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/credit-score-analysis.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Abra o Jupyter Notebook e execute o arquivo `credit_score_analysis.ipynb`.
