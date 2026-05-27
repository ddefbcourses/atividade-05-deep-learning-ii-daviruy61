[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Hbn_ajQx)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=24014959&assignment_repo_type=AssignmentRepo)
# Aprendizado de Máquina

## Estrutura do Projeto

```text
.
├── notebooks/
│   └── ml_experiment_template.ipynb
│
├── src/
│   ├── experiment.py
│   ├── metrics.py
│   ├── plots.py
│   └── utils.py
│
├── requirements.txt
├── setup.sh
├── .gitignore
├── LICENSE
└── README.md
```



## Requisitos

As atividades NÃO possuem como único objetivo atingir a maior accuracy possível.

O foco principal está em:

- compreender o comportamento dos modelos;
- analisar impacto de hiperparâmetros;
- interpretar métricas;
- comparar experimentos;
- justificar decisões experimentais;
- desenvolver organização experimental.

A disciplina incentiva uma abordagem baseada em:

- experimentação;
- análise crítica;
- rastreamento de resultados;
- reprodutibilidade.



## Ambiente de Desenvolvimento

#### Clonando o Repositório

```bash
git clone <repository-url>

cd <repository-name>
```



#### Configuração do Ambiente Virtual

O projeto inclui um script auxiliar para preparação do ambiente:

```bash
./setup.sh
```

O script irá:

- criar um ambiente virtual Python;
- instalar as dependências do projeto;
- preparar o ambiente experimental.



#### Ativando o Ambiente Virtual

###### Linux/macOS

```bash
source venv/bin/activate
```

###### Windows

```bash
venv\Scripts\activate
```



## Executando os Notebooks

Inicie o Jupyter Notebook:

```bash
jupyter notebook
```

Depois abra:

```text
notebooks/assignment.ipynb
```



## MLflow

As atividades utilizam MLflow como ferramenta padrão para rastreamento experimental.

Com MLflow, é possível:

- registrar hiperparâmetros;
- armazenar métricas;
- comparar execuções;
- analisar experimentos;
- manter histórico experimental.



## Iniciando o MLflow

Execute:

```bash
mlflow ui
```

Depois abra no navegador:

```text
http://127.0.0.1:5000
```



## Módulos Auxiliares

O diretório `src/` contém utilitários reutilizáveis para as atividades da disciplina.

#### `experiment.py`

Funções auxiliares relacionadas a:

- MLflow;
- logging;
- rastreamento experimental;
- medição de tempo de treinamento.



#### `metrics.py`

Funções relacionadas a:

- accuracy;
- precision;
- recall;
- f1-score;
- confusion matrix;
- classification report.



#### `plots.py`

Funções auxiliares para:

- curvas de treinamento;
- gráficos comparativos;
- matrizes de confusão;
- visualizações experimentais.



#### `utils.py`

Funções gerais para:

- normalização;
- seeds;
- organização;
- helpers auxiliares.



## Licença

Este projeto é destinado exclusivamente ao uso acadêmico na disciplina de Aprendizado de Máquina.
