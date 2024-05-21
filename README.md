# Utilização de aprendizado supervisionado para desenvolvimento de Máquinas Preditivas com KNN(K-Nearest Neighbors) e Redes Neurais para Previsão de Pagamento de Dívidas de Clientes

### Materiais e Tecnologias

- `Python`
- `Colab`
- `Sklearn`
- `Pandas`

  
[Base de Dados](https://raw.githubusercontent.com/andre-marcos-perez/ebac-course-utils/develop/dataset/credito.csv) 


### Etapas

1. Carregamento dos dados e Análise Exploratória
2. Pré-Processamento dos Dados
3. Máquina Preditiva (KNN)
4. Avaliação Métricas (KNN)
5. Máquina Preditiva (Rede Neural)
6. Avaliação Métricas (Rede Neural)
7. Avaliação melhor modelo

 ### Objetivo  
Prever se um cliente irá pagar uma divida com base em dados pessoais e dados relacionados ao relacionamento do cliente com uma insituição financeira, precisamos classificar os clientes em duas categorias.

*   1 = Inadimplentes
*   2 = Adimplentes

  ![image](https://github.com/filipevilelaluz/aprendizado_supervisionado/assets/74246172/3ecd1e6f-c0b2-4d8e-b34e-82fdf3e6af20)


Cada cliente é representado no conjunto de dados por 15 atributos ou caracteristicas do cliente.

**Atributos** (variáveis de entrada)


Aqui está a lista das colunas enumeradas com uma breve descrição de cada uma:

1. **id**: Identificador único do cliente.
2. **idade**: Idade do cliente.
3. **sexo**: Sexo do cliente (M para masculino, F para feminino).
4. **dependentes**: Número de dependentes do cliente.
5. **escolaridade**: Nível de escolaridade do cliente.
6. **estado_civil**: Estado civil do cliente.
7. **salario_anual**: Faixa de salário anual do cliente.
8. **tipo_cartao**: Tipo de cartão de crédito do cliente.
9. **meses_de_relacionamento**: Número de meses que o cliente tem relacionamento com a instituição financeira.
10. **qtd_produtos**: Quantidade de produtos financeiros adquiridos pelo cliente.
11. **iteracoes_12m**: Número de interações do cliente com a instituição nos últimos 12 meses.
12. **meses_inativo_12m**: Número de meses em que o cliente esteve inativo nos últimos 12 meses.
13. **limite_credito**: Limite de crédito do cliente.
14. **valor_transacoes_12m**: Valor total das transações do cliente nos últimos 12 meses.
15. **qtd_transacoes_12m**: Quantidade total de transações do cliente nos últimos 12 meses.

**Atributo** (variável alvo)

1. **default**: Indicador se o cliente está inadimplente (0 para não inadimplente, 1 para inadimplente).


# Codigo em Python do desenvolvimento do  projeto


| Etapa         | Atividade |
|  :----:   | ----------- |
| ETAPA 1        |[Desenvolvimento do Projeto](Análise_Pagamentos.ipynb) |
