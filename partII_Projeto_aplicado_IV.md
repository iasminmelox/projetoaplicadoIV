
# PROJETO APLICADO IV - Ciência de Dados EaD - 2026/01

# SÉRIE TEMPORAL: Dados climáticos, o caso da cidade de Delhi.

# Integrantes do Grupo
###### Iasmin Melo, 10414568. 

# Introdução

A análise de séries temporais é uma abordagem fundamental para o estudo de fenômenos que evoluem ao longo do tempo, sendo amplamente aplicada em áreas como economia, energia e climatologia. No contexto climático, a observação contínua de variáveis como temperatura, umidade, velocidade do vento e pressão atmosférica permite compreender padrões e comportamentos recorrentes da atmosfera.

Com o avanço da coleta e armazenamento de dados meteorológicos, tornou-se possível realizar análises mais detalhadas e precisas sobre a dinâmica climática. Neste projeto, será utilizada uma base de dados da cidade de Delhi, na Índia, contendo registros diários entre os anos de 2013 e 2017, incluindo variáveis como temperatura média, umidade, velocidade do vento e pressão atmosférica.

A motivação deste estudo está relacionada à importância da compreensão de padrões climáticos ao longo do tempo, especialmente em um cenário de mudanças ambientais globais. A análise de séries temporais permite identificar tendências, sazonalidades e possíveis anomalias nos dados, contribuindo para uma melhor interpretação dos fenômenos climáticos.

Sob a perspectiva da climatologia geográfica, conforme discutido por Emerson Galvani, a análise do clima deve considerar a dinâmica temporal dos elementos atmosféricos e sua relação com o espaço geográfico, permitindo compreender padrões e variações ao longo do tempo.

Este projeto se justifica pela relevância da análise de dados climáticos para diferentes áreas do conhecimento, além de demonstrar a aplicabilidade da linguagem SQL na análise de séries temporais. A hipótese central é que os dados apresentam padrões sazonais bem definidos e relações entre as variáveis meteorológicas.

O objetivo geral do trabalho é analisar o comportamento temporal das variáveis climáticas da cidade de Delhi, identificando padrões e tendências ao longo do tempo. Como objetivos específicos, destacam-se: organizar os dados para análise temporal, investigar a evolução da temperatura, identificar padrões sazonais, aplicar técnicas como médias móveis e analisar relações entre as variáveis climáticas.

# Referencial Teórico

A análise de séries temporais consiste no estudo de dados ordenados no tempo, com o objetivo de identificar padrões como tendência, sazonalidade e variações aleatórias. Essa abordagem é amplamente utilizada na análise de fenômenos climáticos, permitindo compreender o comportamento de variáveis ao longo do tempo.

No campo da climatologia, a análise de dados meteorológicos é essencial para compreender a dinâmica da atmosfera. De acordo com Emerson Galvani, a climatologia geográfica busca interpretar os elementos climáticos considerando sua variabilidade temporal e sua interação com o espaço geográfico.

Estudos relacionados utilizam técnicas estatísticas e computacionais para análise de séries temporais climáticas, frequentemente empregando linguagens como Python e R. Essas abordagens permitem modelagens mais complexas e previsões. No entanto, o uso de SQL se destaca como uma alternativa eficiente para análise exploratória, especialmente na manipulação e agregação de grandes volumes de dados.

Funções analíticas, como médias móveis e funções de janela (window functions), são amplamente utilizadas para suavizar dados e identificar tendências. Entre as vantagens do uso de SQL estão sua eficiência, simplicidade e integração com bancos de dados. Como limitação, destaca-se a menor capacidade de modelagem estatística avançada.

Dessa forma, este trabalho utiliza SQL como ferramenta principal para análise exploratória de séries temporais, com foco na identificação de padrões e relações entre variáveis climáticas.

# Pipeline da Solução

O pipeline da solução proposta é composto pelas seguintes etapas:

Coleta dos dados: utilização de base de dados climáticos contendo registros diários.

#### Pré-processamento: tratamento de valores nulos e padronização de datas.

#### Transformação: organização dos dados em estrutura temporal e criação de variáveis auxiliares.

#### Análise exploratória: cálculo de métricas como médias, máximos e mínimos.

#### Aplicação de técnicas de série temporal: uso de médias móveis e análises de tendência.

#### Visualização: construção de gráficos para interpretação dos dados.

#### Interpretação: análise dos resultados e identificação de padrões climáticos.


O pipeline da solução proposta foi estruturado com o objetivo de transformar dados climáticos brutos em informações analíticas relevantes, permitindo a identificação de padrões temporais nas variáveis meteorológicas.

Inicialmente, os dados são coletados a partir de uma base histórica contendo registros diários das variáveis climáticas da cidade de Delhi. Esses dados são organizados em formato tabular, possibilitando sua manipulação por meio de consultas SQL.

Na etapa de pré-processamento, os dados passam por um processo de limpeza e padronização, incluindo a conversão do campo de data para um formato adequado, tratamento de valores nulos e verificação de inconsistências. Essa etapa é fundamental para garantir a qualidade da análise.

Em seguida, ocorre a transformação dos dados, onde são criadas variáveis auxiliares, como mês e ano, extraídas a partir da data. Além disso, os dados são organizados cronologicamente e agregados em diferentes níveis (diário e mensal), permitindo análises em múltiplas escalas temporais.

Na fase de análise exploratória, são aplicadas consultas SQL para cálculo de métricas descritivas, como médias, máximos e mínimos das variáveis climáticas. Essa etapa permite uma compreensão inicial do comportamento dos dados.

Posteriormente, são aplicadas técnicas de séries temporais, como médias móveis e análise de tendência, utilizando funções analíticas do SQL. Essas técnicas possibilitam a identificação de padrões ao longo do tempo, como variações sazonais e tendências de crescimento ou redução.

Por fim, os resultados são visualizados por meio de gráficos, facilitando a interpretação dos padrões identificados. A etapa final consiste na análise e interpretação dos resultados, permitindo extrair insights sobre o comportamento climático da região estudada.

Dessa forma, o pipeline proposto integra todas as etapas necessárias, desde a coleta até a análise final, garantindo uma abordagem estruturada e eficiente para o estudo de séries temporais.

# Cronograma

| Etapa | Atividade | Período |
|------|----------|--------|
| 1 | Definição do tema e escolha da base de dados | 01/03 – 05/03 |
| 2 | Revisão teórica sobre séries temporais e climatologia | 05/03 – 10/03 |
| 3 | Coleta e compreensão da base de dados | 10/03 – 12/03 |
| 4 | Limpeza e tratamento dos dados | 12/03 – 15/03 |
| 5 | Transformação dos dados para análise temporal | 15/03 – 18/03 |
| 6 | Desenvolvimento das consultas SQL | 18/03 – 22/03 |
| 7 | Análise exploratória dos dados | 22/03 – 26/03 |
| 8 | Aplicação de técnicas de séries temporais (média móvel, tendência) | 26/03 – 29/03 |
| 9 | Construção de gráficos e visualizações | 29/03 – 31/03 |
| 10 | Interpretação dos resultados | 31/03 – 02/04 |
| 11 | Redação do trabalho | 02/04 – 05/04 |
| 12 | Revisão final e ajustes | 05/04 – 07/04 |
| 13 | Preparação para entrega | 07/04 – 08/04 |
| 14 | Entrega do projeto | 08/04 |

# Referências

WEATHER UNDERGROUND. Weather Data API. Disponível em: https://www.wunderground.com/
. Acesso em: 29 mar. 2026.

GALVANI, Emerson; LIMA, Nádia Gilma Beserra de. Climatologia aplicada: resgate aos estudos de caso. Curitiba: CRV, 2012.
