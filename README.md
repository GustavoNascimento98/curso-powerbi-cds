[![pt-br](https://img.shields.io/badge/language-pt--br-green.svg)](https://github.com/GustavoNascimento98/curso-powerbi-cds/blob/main/README.md)
[![en](https://img.shields.io/badge/language-en-red.svg)](https://github.com/GustavoNascimento98/curso-powerbi-cds/blob/main/README-en.md)

![](img/powerbi-cover.jpg)


# Projeto Power BI

Esse projeto contém um dashboard desenvolvido durante o curso **Introdução ao Power BI** ministrado pela [Comunidade DS](https://www.comunidadeds.com/). Nele trabalhamos com o conjunto de dados da [Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

Acesse o relatório [aqui](https://app.powerbi.com/view?r=eyJrIjoiNDFhOTNmZTctMDVhYy00ZDYyLWI1ZTMtYTE0YzIyMmFhNmNmIiwidCI6ImRhNmQ0OWRhLTU1N2MtNDQxNy04YWVmLTg4ZTA1MDcxOTE0MyJ9)

[![](img/dash.gif)](https://app.powerbi.com/view?r=eyJrIjoiNDFhOTNmZTctMDVhYy00ZDYyLWI1ZTMtYTE0YzIyMmFhNmNmIiwidCI6ImRhNmQ0OWRhLTU1N2MtNDQxNy04YWVmLTg4ZTA1MDcxOTE0MyJ9)

</br>
Interaja, filtre, explore e tire suas próprias conclusões! 

## Visão Geral
A Olist é uma empresa brasileira que opera uma plataforma de comércio eletrônico que conecta pequenas e médias empresas a grandes marketplaces. Eles ajudam essas empresas a expandir sua presença online e aumentar suas vendas, fornecendo uma solução integrada que simplifica o processo de vendas em múltiplos canais. A Olist também oferece serviços de logística e suporte para ajudar os vendedores a gerenciar seus negócios de forma eficiente.

No desenvolvimento do relatório foi usando um [conjunto de dados](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) que contém informações de 100 mil pedidos de 2016 a 2018 feitos em múltiplos marketplaces no Brasil. Suas características permitem visualizar um pedido em várias dimensões: desde o status do pedido, preço, desempenho de pagamento e frete até a localização do cliente, atributos do produto e, finalmente, avaliações escritas pelos clientes. O relacionamento entre as entidades de dados pode ser verificado abaixo:

![](img/data-schema.png)

Devido ao alto volume de dados e a dificuldade de extração de insights, a equipe de negócios encomendou um dashboard interativo para auxiliar a tomada de decisões.

## Problema de Negócio
Com o crescimento acelerado e a complexidade do ambiente de negócios, a Olist reconheceu a necessidade de desenvolver um dashboard para facilitar a tomada de decisões estratégicas. O time de negócios enfrentava desafios significativos na obtenção de insights acionáveis devido à falta de uma visão abrangente e centralizada de todas as operações.

Diante desses desafios, o desenvolvimento de um dashboard se tornou uma prioridade estratégica para a Olist. Um dashboard centralizado e intuitivo proporcionaria ao time de negócios uma visão panorâmica das operações, permitindo uma tomada de decisão mais informada e ágil. Ao fornecer insights acionáveis sobre o funcionamento do negócio, o comportamento do usuário e o desempenho das métricas-chave, o dashboard capacitaria a Olist a impulsionar o crescimento de maneira eficaz e sustentável.


## Solução
Com esses tópicos em mente foi desenvolvido um relatório com 6 visões e que pode ser acessado pelo [link](https://app.powerbi.com/view?r=eyJrIjoiNDFhOTNmZTctMDVhYy00ZDYyLWI1ZTMtYTE0YzIyMmFhNmNmIiwidCI6ImRhNmQ0OWRhLTU1N2MtNDQxNy04YWVmLTg4ZTA1MDcxOTE0MyJ9):

1. **Visão Produto:** Insights sobre as características dos produtos sendo vendidos.

2. **Visão Pagamentos:** Insights sobre os tipos de pagamento.

3. **Visão Pedido:** Acompanhamento da evolução dos pedidos feitos e comparação com a meta estabelecida.

4. **Visão Avaliações:** Análise sobre quais fatores influenciam a avaliação dos clientes. 

5. **Visão Vendedores:** Características dos vendedores da base como localização, valor vendido, etc.

6. **Visão Vendas:** Evolução do faturamento, análise de cohort e análise de pareto.


## Próximos Passos
Possíveis aprimoramentos para o relatório do Power BI incluem:

1. **Adição de Novos Indicadores**: Identificar e adicionar novos indicadores-chave de desempenho (KPIs) que possam fornecer insights adicionais sobre o negócio.

2. **Análises Preditivas**: Desenvolver capacidades de análise preditiva para prever o desempenho futuro do negócio e antecipar possíveis desafios ou oportunidades.
