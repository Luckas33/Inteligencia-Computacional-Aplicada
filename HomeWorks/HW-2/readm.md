
# Homework 2 --- Inteligência Computacional Aplicada

Este diretório contém os arquivos referentes ao **Homework 2** da disciplina de **Inteligência Computacional Aplicada (ICA)**.

O código foi desenvolvido em **Python** e executado utilizando o **Google Colab**.

---

## 📁 Estrutura do projeto

```text
HW-2/
│
├── Códigos/
│   └── HomeWork_2.ipynb
│
├── Relatório/
│   └── HomeWork-2-...
│
├── README.md
│
└── TI0175_HW2_assignment.pdf
```

### Códigos

A pasta `Códigos` contém o notebook utilizado para desenvolver e executar a resolução do trabalho:

```text
Códigos/HomeWork_2.ipynb
```

O notebook apresenta a implementação dos modelos de regressão utilizados para prever o Índice de Massa Corporal (BMI), a partir de indicadores de saúde relacionados à diabetes.

### Relatório

A pasta `Relatório` contém o relatório final do Homework 2, com a descrição da metodologia adotada, os modelos desenvolvidos e a análise dos resultados obtidos.

### Enunciado

O arquivo `TI0175_HW2_assignment.pdf` contém o enunciado e as instruções fornecidas para o trabalho.

---

## 🔗 Acesso ao projeto

O código está disponível no GitHub:

[Repositório --- Inteligencia-Computacional-Aplicada](https://github.com/Luckas33/Inteligencia-Computacional-Aplicada/tree/main/HomeWorks/HW-2)

O notebook também pode ser executado diretamente pelo Google Colab:

[HomeWork_2.ipynb --- Google Colab](https://colab.research.google.com/drive/1Oimg2ksLmAAYm3qcK1Ca0_ur2V-EfMhz#scrollTo=zI1eiejPxjyO)

---

## 🚀 Como acessar o código

### Opção 1 --- Pelo Google Colab

Acesse diretamente o notebook:

**Google Colab:**

```text
https://colab.research.google.com/drive/1Oimg2ksLmAAYm3qcK1Ca0_ur2V-EfMhz#scrollTo=zI1eiejPxjyO
```

Após abrir o notebook:

1. Clique em **Conectar**, no canto superior direito;
2. Aguarde a conexão com o ambiente de execução;
3. Execute as células na ordem em que aparecem no notebook.

### Opção 2 --- Pelo GitHub

Acesse a pasta `Códigos` no repositório:

```text
HomeWorks/HW-2/Códigos/
```

e abra o arquivo:

```text
HomeWork_2.ipynb
```

O notebook pode ser baixado ou aberto no Google Colab para execução.

---

## ▶️ Como executar o notebook

Após abrir `HomeWork_2.ipynb` no Google Colab:

1. Clique em **Conectar**;
2. Aguarde o ambiente de execução ser iniciado;
3. Execute as células do notebook na ordem apresentada;
4. Aguarde a conclusão de cada etapa;
5. Os resultados, tabelas e gráficos serão exibidos no próprio notebook.

Para executar todas as células de uma vez, utilize:

**Ambiente de execução → Executar tudo**

> Recomenda-se executar as células na ordem em que aparecem, pois algumas variáveis e resultados são utilizados nas etapas seguintes.

---

## 📦 Bibliotecas utilizadas

O notebook utiliza bibliotecas Python para manipulação de dados, análise estatística, desenvolvimento de modelos de regressão e visualização.

Principais bibliotecas:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LinearRegression, Ridge
from sklearn.neural_network import MLPRegressor
from sklearn.metrics import mean_squared_error, r2_score
from sklearn.model_selection import KFold, cross_val_score
```

O Google Colab normalmente já possui essas bibliotecas instaladas.

Caso seja necessário instalar alguma dependência, utilize:

```python
!pip install nome-da-biblioteca
```

---

## 👥 Autores

- Lucas de Oliveira Sobral - Rede neural
- Gustavo Oliveira Seabra - Modelo Penalizado
- Filipe Alcântara da Costa - Tratamento do Dataset, OLS
- Savlio Carvalho Pontes - PCR

---

## 🔗 Links

**GitHub:**

https://github.com/Luckas33/Inteligencia-Computacional-Aplicada/tree/main/HomeWorks/HW-2

**Google Colab:**

[colab.research.google.com/drive/1Oimg2ksLmAAYm3qcK1Ca0_ur2V-EfMhz#scrollTo=zI1eiejPxjyO](https://colab.research.google.com/drive/1Oimg2ksLmAAYm3qcK1Ca0_ur2V-EfMhz#scrollTo=zI1eiejPxjyO)
