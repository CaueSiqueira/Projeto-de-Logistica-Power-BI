# Projeto-de-Logistica-Power-BI
Dashboard logístico e financeiro desenvolvido em Power BI para monitoramento de KPI’s como OTIF, INFULL, ONTIME, pedidos, ocorrências, receita, custos e margem. O projeto utiliza modelagem de dados, Power Query e DAX para apoiar análises operacionais e estratégicas dos Centros de Distribuição.

Dashboard Logístico e Financeiro | Power BI
Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de solucionar um problema de negócio relacionado ao acompanhamento operacional e financeiro da logística de uma empresa.

A organização enfrentava dificuldades para monitorar o desempenho logístico dos Centros de Distribuição (CDs), pois não possuía uma visão consolidada e acessível dos dados operacionais, dificultando a tomada de decisão.

Diante disso, foi solicitado o desenvolvimento de um dashboard interativo no Power BI, permitindo uma análise completa dos principais indicadores logísticos e financeiros da operação.

Problema de Negócio

A empresa precisava:

Acompanhar a performance logística de forma consolidada entre todos os CDs;
Possuir análises individuais por Centro de Distribuição;
Monitorar os principais KPI’s logísticos;
Visualizar pedidos entregues no prazo e atrasados;
Analisar ocorrências logísticas;
Verificar a distribuição de pedidos por tipo de veículo;
Avaliar o desempenho mensal dos indicadores;
Acompanhar custos, receita, margem e ticket médio;
Visualizar dados geográficos por cidade.

O objetivo principal era criar um painel intuitivo, segmentável por ano e centro de distribuição, auxiliando tanto o controle operacional quanto a tomada de decisão estratégica.

Ferramentas Utilizadas
Power BI
DAX
Power Query
Modelagem de Dados
Excel / CSV

Indicadores Desenvolvidos
KPI’s Logísticos
OTIF
INFULL
ONTIME
Quantidade de Pedidos
Pedidos no Prazo
Pedidos Atrasados
KPI’s Financeiros
Receita Bruta
Custos Logísticos
Margem
% Margem
Ticket Médio
Estrutura do Dashboard
Página KPI’s Logísticos
Visão Geral

O dashboard apresenta uma visão consolidada da operação logística com filtros por:

Centro de Distribuição
Ano
<img width="458" height="209" alt="image" src="https://github.com/user-attachments/assets/2813bf00-9112-43a5-b989-6c234286f014" />

KPI’s OTIF, INFULL e ONTIME

Os principais indicadores logísticos foram desenvolvidos para acompanhar a eficiência operacional das entregas.

OTIF

Indicador responsável por medir entregas realizadas:

No prazo;
Sem falhas;
Com quantidade correta.
INFULL

Responsável por medir entregas realizadas de forma completa.

ONTIME

Indicador utilizado para acompanhar entregas realizadas dentro do prazo.

<img src="images/kpis-otif.png" width="100%">
Pedidos no Prazo x Atrasados

Visual criado para comparar o volume de pedidos entregues no prazo e pedidos atrasados, auxiliando na identificação de gargalos operacionais.

<img src="images/pedidos-prazo-atrasados.png" width="100%">
Ocorrências Logísticas

O dashboard também apresenta as principais ocorrências registradas durante a operação logística.

Principais ocorrências:

Mercadoria Errada
Pedido Faltando
Cliente Ausente
Desistência do Cliente
Recusa do Cliente

Esse acompanhamento auxilia na identificação das principais causas de falhas operacionais.

<img src="images/ocorrencias.png" width="100%">
Distribuição por Tipo de Veículo

Visual utilizado para analisar a distribuição operacional por modal de transporte.

Tipos de veículos analisados:

Fiorino
Truck
Carreta 2 Eixos
Rodotrem
Bitrem
<img src="images/veiculos.png" width="100%">
Evolução Mensal do OTIF

Gráfico temporal desenvolvido para acompanhar a evolução mensal do indicador OTIF ao longo do ano.

Com esse visual é possível:

Identificar sazonalidades;
Comparar períodos;
Detectar quedas operacionais.
<img src="images/otif-mensal.png" width="100%">
OTIF por Cidade

Mapa geográfico criado para visualizar o desempenho logístico por cidade e região.

Esse visual auxilia na identificação de:

Regiões críticas;
Centros com menor performance;
Distribuição operacional das entregas.
<img src="images/mapa-otif.png" width="100%">
Página Financeira
Visão Financeira

A segunda página do dashboard apresenta os principais indicadores financeiros da operação logística.

<img src="images/financeiro-geral.png" width="100%">
Receita, Custos e Margem

Os cards financeiros apresentam:

Receita Bruta;
Custos Logísticos;
Margem Total;
% Margem;
Ticket Médio.

Esses indicadores auxiliam na análise da rentabilidade operacional.

<img src="images/cards-financeiros.png" width="100%">
Receita Bruta por Veículo

Visual utilizado para analisar quais veículos possuem maior representatividade financeira na operação.

<img src="images/receita-veiculo.png" width="100%">
Receita por Ocorrência

Análise financeira relacionada às ocorrências logísticas registradas.

Esse visual permite avaliar impactos financeiros causados por falhas operacionais.

<img src="images/receita-ocorrencia.png" width="100%">
Receita Bruta e Margem por Mês

Gráfico temporal utilizado para acompanhar:

Evolução da receita;
Evolução da margem;
Tendências financeiras da operação.
<img src="images/receita-margem-mensal.png" width="100%">
Receita Bruta por Cidade

Mapa geográfico responsável por apresentar a distribuição financeira das operações por região.

<img src="images/mapa-financeiro.png" width="100%">
Tooltips Personalizados

Foram desenvolvidos tooltips personalizados para enriquecer a experiência analítica do usuário.

Os tooltips apresentam:

Quantidade de pedidos;
Distribuição por ocorrência;
Distribuição por veículo;
KPI OTIF regional.
<img src="images/tooltips.png" width="100%">
Medidas DAX Desenvolvidas

O projeto conta com diversas medidas DAX utilizadas para construção dos indicadores.

Principais medidas
% INFULL
% On time
% OTIF
Custo Total
Margem
Margem %
Qtde Atrasado
Qtde No Prazo
Qtde Pedidos
Qtde Pedidos Cancelados
Qtde Pedidos Sem Ocorrência
Receita Bruta
Receita Bruta com Ocorrência
Ticket Médio
Modelagem de Dados

O projeto foi estruturado utilizando modelo dimensional com tabelas fato e dimensão.

Estrutura utilizada
Tabela Fato
fPedidos
Dimensões
dCalendario
dCD
dStatus
dTransporte
<img src="images/modelagem.png" width="100%">
Principais Insights
Identificação de CDs com menor OTIF;
Análise das principais causas de atraso;
Comparação entre veículos mais eficientes;
Monitoramento financeiro da operação;
Avaliação do impacto financeiro das ocorrências;
Identificação de sazonalidade nos KPI’s.
Resultado

O dashboard permitiu centralizar informações operacionais e financeiras em um único ambiente analítico, facilitando:

Acompanhamento dos indicadores;
Identificação de gargalos operacionais;
Monitoramento estratégico da logística;
Apoio à tomada de decisão.
Autor
Cauê Siqueira

Estudante de Análise e Desenvolvimento de Sistemas com foco em:

Power BI
SQL
Python
Análise de Dados
Visualização de Dados

LinkedIn: coloque seu link
Portfólio: coloque seu link
