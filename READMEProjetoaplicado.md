
# PROJETO APLICADO IV - Ciência de Dados EaD - 2026/01

# SÉRIE TEMPORAL: Dados climáticos, o caso da cidade de Delhi.

# Integrantes do Grupo
###### Iasmin Melo, 10414568. 


 
# 1 INTRODUÇÃO



## 1.1 Contexto do trabalho

A análise de séries temporais é amplamente utilizada para compreender fenômenos que se desenvolvem ao longo do tempo, sendo aplicada em diversas áreas como economia, energia e meteorologia. No contexto climático, o estudo de variáveis como temperatura, umidade, velocidade do vento e pressão atmosférica permite identificar padrões e comportamentos recorrentes que auxiliam na compreensão das condições ambientais.
Com o avanço da coleta de dados meteorológicos, tornou-se possível armazenar grandes volumes de informações históricas, possibilitando análises mais detalhadas e precisas. 
Neste projeto, será utilizada uma base de dados climáticos da cidade de Delhi, na Índia, contendo registros diários entre os anos de 2013 e 2017.

O problema central deste trabalho consiste em compreender como as variáveis climáticas evoluem ao longo do tempo e identificar padrões como tendências, sazonalidades e possíveis anomalias presentes nos dados.
Sob a perspectiva da climatologia geográfica, a análise dos elementos climáticos deve considerar não apenas os valores isolados das variáveis, mas também sua dinâmica temporal e espacial. 
Conforme discutido por Emerson Galvani, professor doutor do departamento de climatologia de geografia da USP, o estudo do clima envolve a compreensão dos processos atmosféricos em interação com o espaço geográfico, permitindo identificar padrões e variações que refletem tanto fatores naturais quanto influências antrópicas.
Dessa forma, a utilização de séries temporais neste trabalho permite não apenas a análise quantitativa dos dados climáticos, mas também uma interpretação mais ampla de sua variabilidade ao longo do tempo.

## 1.2 Motivações e Justificativa

A relevância deste estudo está diretamente relacionada à importância da análise de dados climáticos para a compreensão de padrões ambientais e suas variações ao longo do tempo. Em um cenário global marcado por mudanças climáticas, entender o comportamento de variáveis meteorológicas torna-se essencial para diversas áreas, como planejamento urbano, agricultura e gestão de recursos naturais.
Além disso, a aplicação de técnicas de séries temporais permite extrair informações valiosas a partir de dados históricos, identificando tendências e padrões que não são perceptíveis em análises estáticas. O uso da linguagem SQL como ferramenta principal reforça a aplicabilidade prática do projeto, demonstrando sua capacidade de realizar análises complexas de forma eficiente.
Outro ponto relevante é o potencial de aplicação dos resultados obtidos, que podem contribuir para previsões climáticas, identificação de padrões sazonais e suporte à tomada de decisão em diferentes contextos.

## 1.3 Objetivo geral e objetivos específicos da pesquisa

• Analisar o comportamento temporal das variáveis climáticas da cidade de Delhi, utilizando técnicas de séries temporais para identificar padrões, tendências e relações entre os dados.

###### Objetivos Específicos:
• Organizar e preparar os dados para análise temporal.

• Analisar a evolução da temperatura ao longo do tempo.

• Identificar padrões sazonais nas variáveis meteorológicas.

• Aplicar técnicas como médias móveis para suavização da série.

• Investigar possíveis relações entre temperatura, umidade, vento e pressão.

• Detectar anomalias ou variações atípicas nos dados.

# 2. DESCRIÇÃO DA BASE E REFERENCIAL TEÓRICOS 

## 2.1 Descrição da Base de Dados

O conjunto de dados utilizado neste projeto contém informações meteorológicas da cidade de Delhi, Índia, coletadas entre 1º de janeiro de 2013 e 24 de abril de 2017. Os dados foram obtidos por meio da API Weather Underground, sendo amplamente utilizados para estudos de análise climática e séries temporais.

A base de dados é estruturada em formato tabular, contendo registros diários com as seguintes variáveis:

•	date: data da observação 

•	meantemp: temperatura média do dia 

•	humidity: nível de umidade 

•	wind_speed: velocidade do vento 

•	meanpressure: pressão atmosférica média 

Os dados apresentam organização cronológica e consistência temporal, sendo adequados para análises de séries temporais. A granularidade diária permite a identificação de padrões sazonais e tendências ao longo dos 
anos.

## 2.2 Referencial Teóricos

WEATHER UNDERGROUND. Weather Data API. Disponível em: https://www.wunderground.com/. Acesso em: 29 mar. 2026.
GALVANI, Emerson (org.). Climatologia aplicada: resgate aos estudos de caso. Curitiba: CRV, 2012.

