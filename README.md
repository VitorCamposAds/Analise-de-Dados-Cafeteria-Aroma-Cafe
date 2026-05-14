# 📊 Análises de Dados — Rede de Cafeterias Aroma Café

**Autor:** Vitor Campos  
**Cargo:** Analista de Dados  
**Ferramentas utilizadas:** Google Sheets · Estatística Descritiva · Regressão Linear · Análise Preditiva e Prescritiva

---

## 🧭 Visão Geral do Projeto

Este repositório reúne uma sequência de análises realizadas sobre o desempenho da **Rede de Cafeterias Aroma Café**, abrangendo o período de **janeiro a junho de 2023**.  

O objetivo foi compreender a **evolução do faturamento**, identificar **padrões de consumo**, **projetar resultados futuros** e **propor recomendações estratégicas** baseadas em evidências.

As análises estão organizadas em quatro etapas principais:

1. **Análise Descritiva** — Interpretação dos principais indicadores financeiros e operacionais.  
2. **Análise Diagnóstica** — Investigação das causas por trás das variações de desempenho.  
3. **Análise Preditiva** — Projeção de faturamento para julho/2023.  
4. **Análise Prescritiva** — Recomendações de ações para otimização de resultados.

---

## 📈 1. Análise Descritiva — Saúde da Rede

🔗 **[Visualizar painel interativo no Google Sheets](https://docs.google.com/spreadsheets/d/14yo_gb0y62u5emR8huUAsNgMzCEwznPpW3KyKsryiUk/edit?usp=sharing)**  
📄 **[Baixar Relatório PDF](https://drive.google.com/file/d/1n8dGHthHGQ4qvqkE9MyPhUBBtv0TDy9z/view?usp=sharing)**

**Principais resultados:**
- 📈 Crescimento de **+104%** no faturamento entre janeiro e junho (R$ 81.677 → R$ 166.485).  
- ☕ Categorias mais vendidas: **Coffee**, **Tea** e **Bakery**, representando mais de **80%** do volume total.  
- 🌎 Receita bem distribuída entre regiões (diferença < 2,5%) → **homogeneidade operacional**.  
- 💡 Oportunidade: elevar o **ticket médio** e **diversificar o portfólio de produtos**.

---

## 🔍 2. Análise Diagnóstica — Fatores de Impacto no Faturamento

🔗 **[Visualizar painel interativo no Google Sheets](https://docs.google.com/spreadsheets/d/14yo_gb0y62u5emR8huUAsNgMzCEwznPpW3KyKsryiUk/edit?usp=sharing)**  
📄 **[Baixar Relatório PDF](https://drive.google.com/file/d/1EYDy7s2865ppyQQmPiePa9bio_WXBJEM/view?usp=sharing)**

**Objetivo:** identificar **quais fatores** mais impactaram o faturamento no período analisado.  
Foram testadas **cinco hipóteses** por meio de regressão linear, avaliando relações entre **preço**, **tamanho**, **volume de transações** e **receita**.

**Conclusões-chave:**
- 🔹 O **número de transações** apresentou a **maior correlação positiva** com o faturamento.  
- 🔹 Outras variáveis (preço e tamanho) mostraram tendência esperada, mas sem significância estatística robusta.  
- ⚠️ **Limitação:** pequeno tamanho amostral (4–9 observações) reduz o poder inferencial.  
  → *Recomenda-se ampliar a base de dados para fortalecer as análises futuras.*

---

## 📊 3. Análise Preditiva — Projeção de Faturamento (Julho/2023)

🔗 **[Acessar planilha preditiva no Google Sheets](https://docs.google.com/spreadsheets/d/14yo_gb0y62u5emR8huUAsNgMzCEwznPpW3KyKsryiUk/edit?usp=sharing)**  
📄 **[Baixar Relatório PDF](https://drive.google.com/file/d/1IrjeblI-g5AtVu7lgmIFXO8Z1j-PYeVt/view?usp=sharing)**

| Indicador | Valor |
|------------|--------|
| 💰 **Faturamento projetado** | R$ **176.321,62** |
| 📈 **Crescimento previsto** | **+6,5%** em relação a junho |
| 📉 **Erro médio do modelo** | 9% |
| 🔗 **Correlação (tempo x faturamento)** | 0,96 — *alta precisão estatística* |

**Insights principais:**
- A tendência de crescimento é **constante e sustentável**, impulsionada por fidelização e eficiência.  
- Julho tende a ser o **pico sazonal de consumo** (inverno).  

---

## 🧩 4. Análise Prescritiva — Ações Recomendadas

🔗 **[Acessar planilha prescritiva no Google Sheets](https://docs.google.com/spreadsheets/d/14yo_gb0y62u5emR8huUAsNgMzCEwznPpW3KyKsryiUk/edit?usp=sharing)**  
📄 **[Relatório PDF — Ações Prescritivas](https://drive.google.com/file/d/14QiHg7QTTCBlHSY3Q4MoK4Qf-NBbaex_/view?usp=sharing)**

Com base nas análises descritiva, diagnóstica e preditiva, foram propostas as seguintes ações:

### 🅰️ Prioridade A — Aumento de Transações
- Promover campanhas do tipo **“Leve 2, Pague 1”**.  
- Otimizar o fluxo de checkout e reduzir abandono de carrinho.  
- Implementar **programas de fidelidade e recompra**.

### 🅱️ Prioridade B — Estratégia de Preços
- Executar **testes A/B** em categorias-chave (Coffee, Tea).  
- Evitar descontos amplos; priorizar **promoções direcionadas** com base em dados de elasticidade.

### 🆎 Prioridade C — Mix e Tamanho de Produtos
- Testar **embalagens maiores e combos** para elevar o ticket médio.  
- Monitorar margens e impacto no volume de transações.

### 🔄 Prioridade D — Monitoramento Contínuo
- Criar **dashboards em tempo real** com KPIs de transações, receita e preço médio.  
- Estabelecer **rotina de experimentação** (testar, medir, aprender).

---

## ⚠️ Limitações e Próximos Passos

- Base de dados ainda pequena — ampliar volume histórico para análises robustas.  
- Incluir variáveis de controle: **promoções, sazonalidade e canais de venda**.  
- Próximo passo: integração com **BI (Power BI / Looker Studio)** e **atualização mensal automatizada**.

---

## ✅ Conclusão

O **volume de transações** é o **principal impulsionador do faturamento** da Aroma Café.  
As estratégias de **fidelização, recompra e otimização da experiência do cliente** devem ser priorizadas.  
A rede apresenta **crescimento sólido e sustentável**, com fundamentos favoráveis à expansão.

---

📅 **Período analisado:** Janeiro – Junho de 2023  
📍 **Negócio:** Rede de Cafeterias Aroma Café  
✍️ **Elaboração:** Vitor Campos — Analista de Dados

---

> 💡 *Este projeto integra o portfólio de Data Analytics e demonstra o uso integrado das análises descritiva, diagnóstica, preditiva e prescritiva aplicadas a um de negócio.*
