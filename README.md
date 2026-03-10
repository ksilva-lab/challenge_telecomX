# Análise de Evasão de Clientes (Customer Churn)

## Visão Geral do Projeto

A evasão de clientes, conhecida como **Churn**, é um dos principais desafios enfrentados por empresas que trabalham com serviços recorrentes, como telecomunicações, streaming e serviços financeiros. O churn ocorre quando um cliente decide cancelar ou interromper o uso de um serviço.

Este projeto realiza uma **Análise Exploratória de Dados (EDA)** em um dataset de clientes de uma empresa de telecomunicações, com o objetivo de identificar **padrões e fatores associados ao cancelamento de clientes**.

A análise busca gerar **insights baseados em dados** que possam auxiliar empresas a melhorar suas estratégias de **retenção de clientes**.

---

## Objetivos

Os principais objetivos deste projeto são:

* Compreender os **fatores mais relacionados ao cancelamento de clientes**
* Analisar **padrões de comportamento dos clientes**
* Identificar **perfis de clientes com maior risco de churn**
* Gerar **insights estratégicos para redução da evasão**

---

## Dataset

O dataset utilizado contém informações sobre **7032 clientes** de uma empresa de telecomunicações, incluindo:

* Informações demográficas
* Tempo de relacionamento com a empresa
* Serviços contratados
* Informações de faturamento
* Método de pagamento
* Status de cancelamento

Principais variáveis analisadas:

* `genero`
* `tempo_cliente_meses`
* `tipo_internet`
* `tipo_contrato`
* `metodo_pagamento`
* `gasto_mensal`
* `suporte_tecnico`
* `servicos_streaming`
* `churn`

---

## Ferramentas e Tecnologias

Este projeto foi desenvolvido utilizando as seguintes ferramentas:

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## Análise Exploratória de Dados

Diversas visualizações foram criadas para entender melhor o comportamento dos clientes e identificar padrões relacionados ao churn.

### Distribuição de Cancelamento de Clientes

Análise da proporção de clientes que cancelaram o serviço em comparação com aqueles que permaneceram.

### Cancelamento por Gênero

Comparação da taxa de churn entre clientes do sexo masculino e feminino.

### Cancelamento por Tipo de Contrato

Clientes com **contratos mensais (month-to-month)** apresentam taxas de cancelamento significativamente maiores quando comparados a contratos anuais ou de longo prazo.

### Cancelamento por Método de Pagamento

Clientes que utilizam **Electronic Check** apresentam maior tendência ao cancelamento em comparação com outros métodos de pagamento.

### Cancelamento por Tipo de Internet

Clientes que utilizam **fibra óptica** apresentam maior taxa de churn, possivelmente devido a expectativas maiores ou valores mais elevados.

### Tempo de Cliente vs Cancelamento

Clientes com **menor tempo de relacionamento com a empresa apresentam maior probabilidade de cancelamento**, indicando que os primeiros meses são críticos para retenção.

### Gasto Mensal vs Cancelamento

Clientes com **gastos mensais mais elevados apresentam maior tendência ao churn**, o que pode indicar sensibilidade ao preço ou insatisfação com o custo-benefício do serviço.

---

## 🔍 Principais Insights

A análise revelou alguns padrões importantes:

* Aproximadamente **36% dos clientes cancelaram o serviço**
* Clientes com **menor tempo de permanência apresentam maior churn**
* **Contratos mensais** possuem as maiores taxas de cancelamento
* O método de pagamento **Electronic Check** está associado a maior churn
* Clientes com **gastos mensais elevados** tendem a cancelar mais
* Clientes **sem suporte técnico** apresentam maior probabilidade de churn

Esses padrões ajudam a identificar **perfis de clientes com maior risco de evasão**.

---

## Conclusões
A análise exploratória realizada neste projeto permitiu identificar fatores importantes associados ao cancelamento de clientes em uma empresa de telecomunicações. A partir da exploração dos dados e das visualizações geradas, foi possível compreender melhor o comportamento dos clientes e detectar padrões relevantes relacionados ao churn.

Os resultados mostram que variáveis como tipo de contrato, tempo de relacionamento com a empresa, método de pagamento e gasto mensal possuem forte relação com a evasão de clientes. Em especial, clientes com contratos mensais, menor tempo de permanência e gastos mensais mais elevados apresentam maior probabilidade de cancelamento.

Além disso, a análise sugere que a oferta de serviços adicionais e suporte técnico pode contribuir para aumentar o engajamento dos clientes e reduzir a taxa de churn.

Esses insights demonstram como a análise de dados pode apoiar a tomada de decisões estratégicas, permitindo que empresas desenvolvam ações preventivas para retenção de clientes, como incentivos a contratos de longo prazo, melhorias no atendimento ao cliente e ajustes nas estratégias de precificação.

Como próximos passos, o projeto pode evoluir para a construção de modelos preditivos de churn, permitindo identificar clientes com maior risco de cancelamento e possibilitando a implementação de estratégias de retenção de forma mais proativa.

---

## Autor

Kaique Silva

https://www.linkedin.com/in/kaique-silva-134457157/

https://github.com/ksilva-lab/Laranjas-e-Toranjas/edit/main
