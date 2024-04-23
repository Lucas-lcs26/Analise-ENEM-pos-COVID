# Análise das Notas do ENEM para Entender o Impacto da Pandemia no Ensino Médio brasileiro

Este notebook apresenta uma análise das notas do Exame Nacional do Ensino Médio (ENEM) com o objetivo de investigar o impacto da pandemia do COVID-19 na educação brasileira. Utilizando [dados](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/sinopses-estatisticas/enem) disponibilizados pelo [INEP - Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira](https://www.gov.br/inep/pt-br/acesso-a-informacao/institucional/sobre), foi explorada as tendências nas médias das notas por região, as dinâmicas das notas por disciplina e as variações no número de inscritos ao longo dos anos 2011 a 2022.

# **Principais Etapas do Projeto:**

## **1. Contextualização:**
Apresenta um breve contexto de análise e as perguntas a serem respondidas.

## **2. Coleta de Dados:**
Utilizando dados do ENEM disponibilizados pelo INEP, foram segregadas as informações sobre notas por região, notas por disciplina e número de inscritos. Para isso, foram utilizadas as bibliotecas `pandas` e `zipfile` para extrair e moldar os dados.


## **3. Análise e Visualização:**


1. **Análise das Notas por Região:** Foram investigadas as médias das notas do ENEM por região do Brasil ao longo dos anos, buscando entender padrões e variações regionais. Bibliotecas utilizadas: `pandas`, `matplotlib` e `scipy.stats`.


2. **Dinâmica das Notas por Disciplina:** Foram analisadas as médias das notas por disciplina para identificar possíveis mudanças na performance dos alunos em diferentes áreas de conhecimento. Bibliotecas utilizadas: `pandas`,  `matplotlib` e `scipy.stats`.


3. **Tendências no Número de Inscritos:** Foram exploradas as tendências no número de inscritos no ENEM ao longo dos anos, a fim de quantificar o impacto da pandemia na participação dos alunos. Bibliotecas utilizadas: `pandas` e `matplotlib`.


4. **Visualização Geoespacial:** Para melhor entendimento do panorama apresentado, foram construídas visualizações geoespaciais para mapear as médias das notas e o número de inscritos por estado, oferecendo insights adicionais sobre as disparidades regionais. Bibliotecas utilizadas: `geopandas` e `folium`.

## **4. Conclusão:**
 Apresenta a conclusão da análise.

## **5. Referências:**
Apresenta as referências utilizadas.
