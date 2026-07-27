# Análise de Performance de Campanhas de Marketing

Projeto de Análise Exploratória de Dados (EDA) desenvolvido em **Microsoft Excel**, utilizando uma base com **200.005 campanhas de marketing** realizadas ao longo de 2021.

O objetivo foi investigar se variáveis como canal de divulgação, tipo de campanha, segmento de cliente, investimento, engajamento e tempo eram capazes de explicar diferenças de desempenho entre campanhas.

---

## TL;DR

- Base com **200.005 campanhas** de marketing.
- Foram analisados canais, tipos de campanha, segmentos de clientes, investimento, engajamento e comportamento temporal.
- Nenhuma variável apresentou relação consistente com o **ROI** ou a **taxa de conversão**.
- O projeto demonstra a aplicação de técnicas de EDA, teste de hipóteses, construção de dashboard e comunicação de resultados baseada em evidências.
- Os resultados são compatíveis com uma base de dados sintética.

---

## Tecnologias Utilizadas

- Microsoft Excel
- Git
- GitHub

---

## Base de Dados

- **200.005 campanhas**
- **5 empresas**
- **6 canais de marketing**
  - Google Ads
  - YouTube
  - Instagram
  - Website
  - Facebook
  - Email
- **5 segmentos de clientes**
  - Fashionistas
  - Foodies
  - Health & Wellness
  - Outdoor Adventurers
  - Tech Enthusiasts
- **Período:** Janeiro a Dezembro de 2021

---

## Objetivos da Análise

Responder às seguintes perguntas:

- Existe algum canal mais eficiente?
- Algum tipo de campanha apresenta desempenho superior?
- O ROI varia ao longo do tempo?
- Existe relação entre investimento e retorno?
- O engajamento influencia a conversão?
- Existem padrões consistentes entre campanhas de alto e baixo desempenho?

---

## Contexto da Análise

A hipótese inicial era verificar se variáveis como canal, tipo de campanha, segmento de cliente, investimento ou tempo seriam capazes de explicar diferenças de desempenho entre campanhas.

Para isso, foram aplicadas diferentes abordagens analíticas, buscando validar ou rejeitar cada hipótese com base nos dados.

---

## Análises Realizadas

### Análise univariada

Foram comparados ROI e taxa de conversão entre canais e tipos de campanha. As diferenças observadas foram pequenas e sem relevância prática.

### Análise bivariada

Foi analisado o cruzamento entre canal e segmento de cliente por meio de uma matriz (heatmap). Nenhuma combinação apresentou desempenho significativamente superior.

### Eficiência dos canais

Foram calculados indicadores como **CTR** e **CPC**, que apresentaram comportamento semelhante entre todos os canais.

### Análise de Outliers

Utilizando percentis para identificar campanhas de alto e baixo desempenho, observou-se uma distribuição uniforme entre os canais.

### Análise Temporal

O ROI permaneceu praticamente estável durante todo o ano de 2021, sem evidências de sazonalidade.

### Correlação entre Variáveis

Também foi analisada a relação entre:

- Custo de aquisição × ROI
- Engajamento × Conversão

Em ambos os casos, as correlações encontradas foram praticamente nulas.

---

## Dashboard

![Dashboard](imagens/marketing-analytics-dashboard.png)

O dashboard consolida visualmente os principais indicadores e resultados da análise exploratória.

---

## Principais Resultados

- Não foram identificadas diferenças relevantes de ROI entre canais.
- Não foram identificadas diferenças relevantes entre tipos de campanha.
- Não houve correlação entre custo de aquisição e ROI (**r = 0,0046**).
- O cruzamento Canal × Segmento não revelou combinações de destaque.
- CPC e CTR médios foram semelhantes entre todos os canais.
- Campanhas de alto e baixo desempenho distribuíram-se de forma uniforme entre os canais.
- Não houve sazonalidade do ROI ao longo de 2021.
- Não houve correlação entre engajamento e conversão (**r = -0,00065**).

---

## Interpretação dos Resultados

As variáveis disponíveis na base não apresentaram poder explicativo consistente para o desempenho das campanhas.

Esse resultado pode indicar dois cenários:

1. O desempenho de campanhas reais depende de fatores não presentes na base, como qualidade do criativo, contexto de mercado, concorrência ou estratégia de segmentação.

2. A base possui características compatíveis com dados sintéticos, situação comum em datasets públicos utilizados para fins educacionais.

A ausência de relações significativas não representa uma falha da análise. Pelo contrário, demonstra a importância de validar hipóteses antes de transformá-las em recomendações de negócio.

---

## Competências Demonstradas

- Limpeza e preparação de dados
- Análise Exploratória de Dados (EDA)
- Formulação e teste de hipóteses
- Construção de métricas derivadas (CTR, CPC e Faixa de ROI)
- Correlação entre variáveis
- Análise temporal
- Identificação de outliers por percentis
- Construção de Tabelas Dinâmicas
- Desenvolvimento de Dashboard
- Comunicação de resultados baseada em evidências

---

## Ferramentas e Técnicas

- Microsoft Excel
- Tabelas Dinâmicas
- Dashboard
- Formatação Condicional
- Texto para Colunas
- Colunas calculadas
- Funções:
  - `CORREL`
  - `MÉDIASE`
  - `PERCENTIL.INC`
  - `SE`

---

## Limitações

- A base apresenta características compatíveis com dados sintéticos.
- Não foi possível estabelecer relações de causa e efeito.
- Os resultados limitam-se às variáveis presentes no dataset.
- Não foram aplicados testes estatísticos inferenciais (ANOVA, teste t ou regressão).

---

## 📂 Estrutura do Projeto

```
  analise-campanhas-marketing
├── dados/
├── dashboard/
├── imagens/
├── relatorio/
├── README.md
```

---

## Relatório Completo

A documentação detalhada da análise encontra-se em:

**relatorio/relatorio_analise_marketing.md**

---

## Fonte dos Dados

**Marketing Campaign Dataset – Kaggle**

https://www.kaggle.com/datasets/guelmaniloubna/marketing-campaign-dataset

---

## Considerações Finais

Este projeto demonstra a aplicação de técnicas de Análise Exploratória de Dados utilizando Microsoft Excel para investigar hipóteses de negócio.

Embora não tenham sido identificadas relações significativas entre as variáveis analisadas, o trabalho evidencia a importância de testar hipóteses, interpretar resultados com rigor metodológico e comunicar conclusões de forma clara, objetiva e baseada em evidências.
