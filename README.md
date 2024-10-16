# Previsão de Consumo de Cerveja com Machine Learning

Este projeto utiliza técnicas de **Machine Learning** para prever o consumo de cerveja com base em variáveis meteorológicas e dados sobre dias da semana.

## Estrutura do Projeto

- **data/**: Contém os dados utilizados no projeto.
  - `raw/`: Dados brutos (não processados).
  - `processed/`: Dados limpos e pré-processados.
- **notebooks/**: Jupyter notebooks usados para a exploração de dados e análise inicial.
- **models/**: Modelos treinados em diferentes algoritmos.
- **scripts/**: Scripts Python para processamento e treinamento dos modelos.
- **reports/**: Gráficos e relatórios gerados durante o projeto.
  
## Modelos Usados

Neste projeto, foram implementados e avaliados três modelos de regressão para prever o consumo de cerveja:
1. **Regressão Linear**
2. **Árvore de Decisão**
3. **Random Forest**

### Desempenho dos Modelos

O desempenho dos modelos foi avaliado usando o **Root Mean Squared Error (RMSE)**. A tabela a seguir mostra os resultados:

| Modelo             | RMSE   |
|--------------------|--------|
| Regressão Linear    | 2.39   |
| Árvore de Decisão   | 3.51   |
| Random Forest       | 2.69   |

### Conclusão

A **Regressão Linear** foi o modelo que apresentou o menor erro e, portanto, foi escolhido como o modelo mais adequado para este problema. No entanto, modelos mais avançados podem ser testados e ajustados para obter melhores resultados.
