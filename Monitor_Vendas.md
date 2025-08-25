---
layout: page
title: "Monitoramento de Vendas"
permalink: /cases/Mon_vendas/
nav_exclude: true
---

# Case: Monitoramento de vendas

**Introdução**  
Um Dashboard de monitoramento de vendas é bastante util para que os tomadores de decisão tenham acesso as dados de produção de forma rapida e dinâmica. O monitoramento traz informações de vendas divididas pelos principais atores,
além de projeções e históricos.

**Contexto**</br>
Este dashboard utiliza dados ficticios, mas inspirado em um caso real no qual atuei. O processo começou com a extração de dados em Excel, realizada a partir de um sistema de gestão, com apoio de automação em Python para organizar e estruturar os arquivos recebidos. Fui responsável por todo o desenvolvimento do dashboard, desde a preparação e tratamento dos dados até a criação dos visuais interativos no Power BI. O objetivo central foi transformar dados brutos em informações consolidadas, disponibilizadas em uma única página de fácil interpretação para diferentes níveis de gestão.

O público-alvo do projeto incluía gerentes comerciais, gestores de área e diretoria, que necessitavam de informações rápidas e confiáveis para embasar suas tomadas de decisão estratégicas.

Entre os principais recursos implementados, destaco:

- Análises detalhadas de vendas segmentadas por tipo de contrato, bancos e parceiros.

- Acompanhamento do desempenho por histórico mensal e diário, permitindo a identificação de tendências sazonais.

- Tooltips personalizados, que fornecem informações adicionais ao passar o mouse sobre os dados, enriquecendo a análise sem comprometer a clareza visual.

- Filtros gerais e específicos, possibilitando a exploração de informações por diferentes atores do processo (parceiros, bancos, gerentes, etc.).

- Indicadores de tendências, projeções e alertas, destacando oportunidades de melhoria, pontos de atenção e a performance de novos parceiros ou daqueles que reduziram suas vendas.

O resultado foi um painel intuitivo e visualmente limpo, que agrega valor ao processo de gestão, trazendo maior agilidade, transparência e precisão na análise dos indicadores comerciais.
**Dashboard**  
<iframe title="clone_pgto Cliente" width="900" height="600" src="https://app.powerbi.com/view?r=eyJrIjoiYWY4NmFmNTItZmZjYi00MzBkLTgwNTctNDEwYTkyYWU2MmZmIiwidCI6ImQ4Nzc1YTNhLWU4OWEtNGNjZC1hY2NiLTQ0MDg4ODdjMzRlMCJ9" frameborder="0" allowFullScreen="true"></iframe>

**Modelagem e DAX**  
Utilizando dados ficticios armazenados via excel as tabelas são importadas via Power query, onde utilizo Linguagem M para fazer os tratamentos, mesclagem e otimização dos dados.

**Principais insights**  
- KPIs Gerais: O faturamento atual é de R$ 954 mil (≈75% da projeção de R$ 1,27 milhão), com crescimento de +23% frente ao mês anterior. Isso mostra boa tendência.
- Tipos de Contratos: Novos e Portabilidade concentram quase 90% das vendas, enquanto Refinanciamento e Crédito Pessoal estão em queda. O FGTS cresce quase +900%, mesmo com volume pequeno, e pode ser explorado como tendência.
- Distribuição por Bancos: O C6 Bank domina (≈70% da carteira), o que indica dependência elevada de um único banco. Outros bancos (BRB, BMG) aparecem, mas com participação muito menor.
- Parceiros: MAXPRIME lidera em volume, mas novos parceiros como FIN-TOP (+402%) e PRIMESOLUTIONS (+223%) mostram forte crescimento, sinalizando oportunidades de expansão.
- Histórico Mensal: Oscilações ao longo dos meses (queda em março e maio, recuperação em abril e junho). A variação sugere que os resultados ainda dependem de momentos pontuais, faltando consistência.

**Principais Ações**
- Campanhas sazonais: Criar promoções específicas para novembro e dezembro, aproveitando o potencial de alta no fim do ano.
- Diversificação Bancária: Negociar condições melhores e incentivar vendas por outros bancos, reduzindo a dependência do C6 Bank.
- Expansão Regional: Mapear estados/regiões com menor penetração e direcionar ofertas localizadas para aumentar cobertura.
- Incentivo ao FGTS e novos produtos: Estruturar campanhas para destacar FGTS e reforçar contratos em queda (Refinanciamento e Crédito Pessoal).
- Bundles e Cross-Sell: Criar pacotes de produtos (serviços financeiros + benefícios extras) para aumentar ticket médio.
- Benchmark Interno: Identificar práticas dos parceiros e gerentes mais performáticos e aplicar treinamentos replicando as melhores estratégias.
