# 📊 Análise de Performance de Campanhas de Marketing

Projeto de análise exploratória de dados desenvolvido em Microsoft Excel, utilizando uma base com **200.005 campanhas de marketing** realizadas ao longo de 2021.

## 🎯 Objetivo

Investigar se variáveis como canal de divulgação, tipo de campanha, investimento, engajamento e duração influenciam o desempenho das campanhas, medido por indicadores como **ROI** e **taxa de conversão**.

---

## 📊 Dashboard

![Dashboard](analise-campanhas-marketing/imagens/marketing-analytics-dashboard.png) 

---

## 🔍 Principais resultados

- Não foram identificadas diferenças relevantes de ROI entre os canais de divulgação ou tipos de campanha.
- Não foi observada correlação entre custo de aquisição e ROI (**r = 0,0046**).
- Não foi observada correlação entre engajamento e taxa de conversão (**r = -0,00065**).
- O ROI manteve comportamento estável ao longo de 2021, sem indícios de sazonalidade.
- Campanhas com desempenho extremo (outliers) estão distribuídas entre diferentes canais, sem concentração específica.

---

## 🛠️ Ferramentas e técnicas utilizadas

- Microsoft Excel
- Tabelas Dinâmicas
- Dashboard Interativo
- Formatação Condicional
- Validação de Dados
- Segmentação e agregação de informações
- Funções do Excel:
  - CORREL
  - MÉDIASE
  - PERCENTIL.INC
  - SE
- Criação de métricas derivadas (CTR, CPC e classificação por percentis)

---

## 📂 Estrutura do projeto

```
├── dados/
├── dashboard/
├── imagens/
├── relatorio/
├── README.md
```

---

## 📄 Relatório

A análise completa, incluindo metodologia, interpretação dos resultados e conclusões, está disponível em:

**relatorio/relatorio_analise_marketing.md**

---

## ⚠️ Limitações

A base utilizada apresenta características compatíveis com dados sintéticos. Dessa forma, os resultados obtidos têm finalidade educacional e não devem ser interpretados como evidência de cenários reais de negócio.

---

## 📌 Base de dados

**Marketing Campaign Dataset – Kaggle**

https://www.kaggle.com/datasets/guelmaniloubna/marketing-campaign-dataset

---

## 👩‍💻 Sobre o projeto

Este projeto foi desenvolvido com o objetivo de praticar técnicas de análise exploratória de dados, organização de informações, construção de dashboards e comunicação de resultados utilizando Microsoft Excel, compondo meu portfólio na área de Análise de Dados.
