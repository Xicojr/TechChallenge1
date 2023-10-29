# Análise sobre a Exportação de Vinhos no Brasil

Análise sobre a Exportação de Vinhos no Brasil
FIAP: Pós Tech - Data Analytics Tech Challenge #01

### Grupo 66 - Autores:

- Flademir de Albuquerque
- Lucas Ordonio
- Franscisco
- Tadeu Tupinambá

### Objetivo
O objetivo é apresentar análise sobre esse desempenho de exportação brasileira, mostrando os fatores que influenciaram as maiores vendas e o que podemos fazer para performar mais.

### Slides com informações detalhadas e explicadas:

### Arquivos:

- `./analises_externas/`
  - Outras fontes de dados que foram análisadas estão dentro desse folder
- `./Dados/`
  - Aqui se encontra os dados utilizados para a análise
- `./First_Tech_Challenge.ipynb`
  - Análise de dados, EDA e geração de gráficos
- `./Ouput_Tabela_Tech_Challenge.ipynb`
  - Geração da tabela requerida pelo trabalho
    - País de origem
    - País de Destino
    - Quantidade de litros de vinho exportados
    - Valor total das exportações em dólares


### Conclusão da Análise (EDA)

![Tabela final gerada](./images/tabela_resultado.png)

### Análise Exploratória dos Dados de Exportação de Vinho
## 1. Principais Destinos de Exportação por Valor
Os países onde é gerado o maior valor a partir das exportações de vinho são:

- Rússia: $25,064,390

- Paraguai: $20,501,133

- Estados Unidos: $8,422,327

- Reino Unido: $4,368,194

- Espanha: $3,808,426

## 2. Menores Destinos de Exportação por Quantidade
Os países que recebem a menor quantidade de vinho (onde a quantidade > 0) são:

- Equador: 2 litros

- Montenegro: 9 litros

- Belize: 9 litros

- Serra Leoa: 18 litros

- Gibraltar: 23 litros


## 3. Razão Valor-por-Quantidade
Países com o maior valor gerado por litro exportado:

- Serra Leoa: $39,83 por litro

- República Eslovaca: $27,46 por litro

- Bulgária: $13,50 por litro

- Barbados: $10,94 por litro

- Letônia: $9,62 por litro

## 4. Distribuição dos Dados
- Quantidade:
  - Média: 535,063 litros

  - Mediana: 1,279 litros

  - Desvio Padrão: 3,653,642 litros

- Valor:
  - Média: $670,069

  - Mediana: $5,092

  - Desvio Padrão: $2,996,849

### Fontes de dados:
Todos as bases de dados são mantidas pelas respectivas fontes.

- https://ourworldindata.org/grapher/wine-consumption-per-person?tab=table&time=2005..2019
- http://vitibrasil.cnpuv.embrapa.br/index.php?opcao=opt_01
- https://bdmep.inmet.gov.br/
