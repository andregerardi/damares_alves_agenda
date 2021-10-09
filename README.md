# O que motivou a construção desses script?

Esses script raspa a agenda de integrantes do MMFDH. O ministério não possuiu uma opção para baixar os dados em formato CSV. Esse trabalho surgiu da necessidade em obter os dados no site, o que reflete a falta de transparência com a divulgação de informações da burocracia estatal. Afim de contribuir com outros pesquisadores, disponibilizei o script para auxiliar outras pessoas enfrentam tal dificuladade.

## Objetivo

Os dados serão utilizados numa pesquisa em andamento, que cruza as agendas de ministros declaradamente conservadores do governo Bolsonaro.

## Scripts

O modelo apresenta uma lista de todas as [agendas disponíveis]('https://www.gov.br/mdh/pt-br/acesso-a-informacao/agenda-de-autoridades/) no site do Ministério da Família. Há um csv com essa lista e um dataframe, que pode ser usado de duas maneiras:

1) para buscar a agenda de pessoas espedíficas, que no exemplo buscamo da ministra Damares, ou para; 

2) realizar a obtenção da agenda de todos os integrantes do ministério. Em outubro de 2021, no momento que elaborei esse modelo, a agenda da ministra somava pouco mais de 1000 linhas, mas quando consideramos todas as agendas de integrantes do ministério, o N foi > 45.000 linhas.
