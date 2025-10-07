# Modelo de classificação - Projeto da Pós Tech FIAP 

Este projeto foi desenvolvido como parte do curso de Pós-Tech da FIAP e tem como objetivo construir um modelo de Machine Learning (ML).<br>

- **Dataset**: A base de dados empregada neste projeto foi obtida a partir da seguinte fonte: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/data

- **Dataset**: O modelo escolhido para ser usado foi o de Regrssão Logistica e pode ter testado no link: https://fivemlet-f3-streamlit.onrender.com/<br>
O código pode ser encontrado pelo link: https://github.com/PatySutto/5mlet_f3_streamlit


## 📁 Estrutura do Projeto

```bash
5mlet_postech/
├── dataset/
│   ├── heart-failure-tratado.csv
│   └── heart-failure.csv
├── src/
│   ├── analise_exploratoria.ipynb
│   └── modelos ML/
│       ├── arvore_decisao.ipynb
│       ├── knn.ipynb
│       ├── regressão_logistica.ipynb
│       ├── support_vector_machine.ipynb
│       └── xgboost.ipynb   
├── modelo_regressao_logistica.joblib
├── README.md
└── requirements.txt

```
- **`dataset/`**: Diretório que contém as bases de dados usadas.
  - **`heart-failure-tratado.csv`**: Base de dados tratada utilizada para o treinamento do modelo.
  - **`heart-failure.csv`**: Base de dados original.
- **`src/`**: Diretório que reúne os modelos de Machine Learning e os scripts referentes à análise exploratória dos dados.
    - **`analise_exploratoria.ipynb`**: Notebook destinado à realização e visualização da análise exploratória dos dados.
    - **`modelos ML/`**: Diretório que contém os modelos de Machine Learning.
        - **`arvore_decisao.ipynb`**: Notebook com o modelo de Árvore de Decisão.
        - **`knn.ipynb`**: Notebook com o modelo de K-Nearest Neighbors (KNN).
        - **`regressão_logistica.ipynb`**: Notebook com o modelo de Regressão Logística.
        - **`support_vector_machine.ipynb`**: Notebook com o modelo de Support Vector Machine (SVM).
        - **`xgboost.ipynb`**: Notebook com o modelo de XGBoost.
- **`modelo_regressao_logistica.pkl`**: Modelo de Regressão Logística já treinado.
- **`README.md`**: Documentação do projeto.
- **`requirements.txt`**: Lista de dependências do projeto.


## 🛠️ Como Executar o Projeto Localmente

### 1. Clone o Repositório

```bash
git clone https://github.com/PatySutto/5mlet_fase_3.git
```

### 2. Crie um Ambiente Virtual

```bash
python -m venv venv
source .\venv\Scripts\activate   # No Linux: venv/bin/activate
```

### 3. Instale as Dependências

```bash
pip install -r requirements.txt
```

### 4. Execute os modelos

```
Escolha o modelo desejado e clique em "Run All".
```