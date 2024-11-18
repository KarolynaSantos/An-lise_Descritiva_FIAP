# Análise Descritiva - Perfil de Clientes de E-Commerce

Este projeto realiza uma análise descritiva de um conjunto de dados sobre os clientes de um e-commerce, fornecendo insights sobre o comportamento e as características dos clientes.

## Objetivo

O objetivo desta análise é explorar e entender as principais características dos clientes de um e-commerce, por meio de estatísticas descritivas, visualizações e insights sobre os dados.

## Bibliotecas Utilizadas

Durante a análise, foram utilizadas as seguintes bibliotecas:

- **pandas**: Para manipulação de dados.
- **matplotlib** e **seaborn**: Para visualizações gráficas.
- **sklearn.preprocessing.LabelEncoder**: Para codificação de variáveis categóricas.
- **sweetviz**: Para gerar relatórios de exploração de dados e análise visual automatizada.
- **numpy**: Para operações numéricas e matrizes.
- **warnings**: Para controlar mensagens de advertência durante a execução.

### Instalação das Bibliotecas

Caso ainda não tenha as bibliotecas necessárias, você pode instalá-las usando o seguinte comando:

```bash
pip install -r requirements.txt
```


## Análise Descritiva
### A análise descritiva inclui:

* Estatísticas básicas dos dados, como médias, medianas, desvio padrão, etc.
* Análise de distribuições de variáveis quantitativas.
* Visualizações gráficas para identificar padrões e outliers.
* Exploração de variáveis categóricas usando codificação com LabelEncoder.

Além disso, foi utilizado o sweetviz para gerar um relatório interativo sobre os dados:

``` 
import sweetviz as sv

# Gerando relatório Sweetviz
relatorio = sv.analyze(df)
relatorio.show_html('relatorio.html')

```

O relatório gerado pelo Sweetviz oferece uma visão geral detalhada das características dos dados, incluindo distribuições de variáveis, correlações e possíveis inconsistências.

## Resultados
Através da análise, conseguimos:

* Identificar padrões de compra e comportamento dos clientes.
* Explorar variáveis importantes para a segmentação de clientes.
* Detectar possíveis outliers ou erros nos dados.

## Conclusão
Esta análise descritiva forneceu uma visão geral valiosa sobre o perfil dos clientes de um e-commerce. Com os insights obtidos, podemos criar estratégias de marketing mais direcionadas, melhorar a experiência do cliente e tomar decisões informadas sobre a segmentação de público.