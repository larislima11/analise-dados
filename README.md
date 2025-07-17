# Business Intelligence - Exploração e Análise de Dados

Este projeto apresenta atividades de **Business Intelligence** (BI) e **Data Mining** desenvolvidas durante as aulas do Centro Universitário Facens. Ele inclui a implementação de técnicas para análise, exploração de dados e visualização de padrões em conjuntos de dados.

## Objetivos do Projeto

* **Aplicar Técnicas de Data Mining:** Implementar algoritmos-chave de mineração de dados com sucesso.
* **Explorar Padrões e Tendências:** Extrair insights acionáveis dos dados para dar suporte à tomada de decisões.
* **Realizar Análises Práticas:** Conduzir análises aprofundadas utilizando bases de dados autênticas.
* **Criar Visualizações Estratégicas:** Desenvolver dashboards e gráficos impactantes para comunicar descobertas.

### Análise de Comportamento de Clientes em Shopping Centers

* **Objetivo:** Identificar padrões de gastos dos clientes para possibilitar estratégias de marketing personalizadas.
* **Base de Dados:** [Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
* **Técnica Utilizada:** Regras de Associação.

 <img width="584" height="446" alt="image" src="https://github.com/user-attachments/assets/ef1820e2-7f10-4f80-b906-4c06fb894869" />

* **Análise e Modelo:**
    * **Engenharia de Dados:** Criamos variáveis categóricas para faixa etária e grupo de renda, facilitando a segmentação e análise dos clientes.
    * **Regras de Associação:** Utilizamos o algoritmo **Apriori** para transformar os dados e identificar conjuntos de itens frequentes. Posteriormente, geramos regras de associação com base na métrica de *lift*, revelando combinações de categorias que ocorrem juntas com maior probabilidade (ex: "clientes jovens com renda média tendem a comprar X e Y").
* **Visualizações Chave:**
    * **Heatmap de Regras de Associação:** Visualiza as correlações e padrões entre faixas etárias, gêneros e grupos de renda.
    * **Distribuição por Gênero e Renda:** Gráficos de pizza para uma visão rápida da proporção de clientes por gênero e nos diferentes grupos de renda.
    * **Renda por Faixa Etária:** Histograma ou gráfico de barras mostrando a distribuição da renda em cada faixa etária.
* **Insights Gerados:** Esta análise permite exibir quais grupos de clientes têm maior probabilidade de se relacionar em termos de faixa etária e renda, fornecendo **insights estratégicos** para personalizar campanhas de marketing e otimizar a experiência do cliente.

 ### Previsão de Diabetes

* **Objetivo:** Prever a probabilidade de um paciente ter diabetes com base em informações clínicas.
* **Base de Dados:** [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
* **Técnica Utilizada:** Classificação (Árvores de Decisão, Random Forest).

<img width="459" height="403" alt="image" src="https://github.com/user-attachments/assets/7b9e91a3-69a8-4ad1-a53d-94e6e9168af6" />

 * **Análise e Modelo:**
    * **Engenharia de Dados:** Realizamos a separação clara entre variáveis preditoras e a variável alvo (`Outcome`).
    * **Divisão de Dados:** Os dados foram divididos em conjuntos de treino (80%) e teste (20%) para garantir a robustez e a validação do modelo.
    * **Treinamento e Avaliação:** O modelo Random Forest foi treinado e sua performance avaliada por **acurácia** e **matriz de confusão**, oferecendo uma visão detalhada dos verdadeiros positivos, falsos positivos e falsos negativos.
* **Visualizações Chave:**
    * **Distribuição de Diabetes:** Gráfico de pizza mostrando a proporção de pacientes com e sem diabetes.
    * **Níveis de Glicose:** Histograma da distribuição dos níveis de glicose na população.
    * **Idade vs. Glicose:** Gráfico de dispersão explorando a relação entre idade e níveis de glicose.
    * **IMC por Idade:** Gráfico de barras visualizando a distribuição do IMC entre diferentes faixas etárias.
    * **Matriz de Confusão:** Representação visual da performance do modelo, essencial para entender os erros de classificação.
* **Insights Gerados:** A análise da distribuição de glicose e a relação entre idade e glicose fornecem insights importantes sobre o comportamento da doença e como certas variáveis se correlacionam com a probabilidade de diabetes.
  
## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **Bibliotecas**:
  - `pandas`, `numpy` - Manipulação e análise de dados.
  - `matplotlib`, `seaborn` - Visualização de dados.
  - `scikit-learn` - Modelos de aprendizado de máquina.
- **Jupyter Notebook**: Ambiente para desenvolvimento e execução do código.

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone (https://github.com/larislima11/analise-dados.git)

 ## Principais Resultados
Análise de Shopping Centers:

Descoberta de padrões comportamentais, como grupos de clientes com comportamentos de compras semelhantes.
Visualizações gráficas que destacam a segmentação dos clientes.
Previsão de Diabetes:

Modelo de aprendizado de máquina com métricas de desempenho (acurácia, precisão).
Gráficos explicativos para os resultados de classificação.

## Exercícios Realizados
Os seguintes exercícios foram desenvolvidos como parte do projeto:

Reprodução de exemplos práticos, incluindo:
* **Comentários explicativos detalhados** dentro dos blocos de código.
* **Interpretação aprofundada de gráficos e resultados**
* **Organização em um único notebook para facilitar a navegação.**
  
## Contribuições e Feedback

Agradeço qualquer feedback ou sugestão! Sinta-se à vontade para:

* **Reportar problemas (issues)** no repositório do GitHub.
* **Enviar pull requests** para melhorias ou novas funcionalidades.

## Licença
Este projeto é de uso acadêmico e educacional.

## Contato

* **Professor:** Daniel Ohata
* **Aluna:** Larissa Lima (223201)
* **GitHub:** [larislima11](https://github.com/larislima11)
* **LinkedIn:** (https://www.linkedin.com/in/larissalima01/) 



