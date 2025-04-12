# Projeto Python IA: Inteligência Artificial e Previsões

## 💼 Case: Score de Crédito dos Clientes

Você foi contratado por um banco para definir o score de crédito dos clientes. O objetivo é analisar os dados dos clientes e criar um modelo de Machine Learning capaz de prever automaticamente o score de crédito com base em suas informações. Os scores possíveis são:

- **0**: Ruim  
- **1**: Ok  
- **2**: Bom

---

## 📁 Estrutura do Projeto

- **Leitura dos dados** (`clientes.csv`)
- **Pré-processamento**
  - Codificação de variáveis categóricas (`profissao`, `mix_credito`, `comportamento_pagamento`)
- **Separacão dos dados**
  - Features (X) e target (y)
  - Divisão em treino e teste (70% treino / 30% teste)
- **Modelagem**
  - Random Forest Classifier
  - KNN Classifier
- **Avaliação dos Modelos**
  - Comparação por acurácia
  - Melhor modelo escolhido: Árvore de Decisão (Random Forest)
- **Previsão para novos clientes** (`novos_clientes.csv`)

---

## 🧠 Tecnologias Utilizadas

- Python
- Pandas
- Scikit-Learn
- Jupyter Notebook

---

## 📊 Resultados

- O modelo Random Forest apresentou melhor acurácia e foi utilizado para prever o score dos novos clientes.
- A previsão foi armazenada em uma nova coluna chamada `score_credito` no DataFrame de novos clientes.

---

## 🚀 Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/nome-do-repositorio.git
   ```

2. Instale os pacotes necessários:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute o notebook `inicial.ipynb` no Jupyter Notebook.

---

## 📂 Dados

Os dados utilizados estão disponíveis em:
- `clientes.csv`: Base de dados original com os clientes do banco.
- `novos_clientes.csv`: Novos clientes a serem analisados pelo modelo.

---

## 📬 Contato

Caso tenha dúvidas ou sugestões, entre em contato:

- Nome: Léo Matias Araújo
- Email: leo21matias@hotmail.com

---

## 📌 Observações

Este projeto é apenas uma simulação educacional e não deve ser usado em ambientes de produção sem as devidas validações.

