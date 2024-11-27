# Análise de BI: Lucro Bruto, Quantidade e Vendas

## 📄 Visão Geral
Este projeto tem como objetivo explorar dados anuais de vendas, quantidade e lucro bruto para fornecer insights detalhados sobre o desempenho de diferentes países, produtos e períodos. Foram desenvolvidos quatro gráficos interativos para auxiliar na tomada de decisões estratégicas.

---

## 📊 Estrutura do Dashboard

### 1. **Treemap**
   - **Objetivo**: Identificar os 10 piores países em desempenho ao comparar o ano atual com o anterior.
   - **Características**:
     - Cada célula representa um país, com tamanho e cor indicando a magnitude da diferença negativa.
     - Foco em destacar áreas críticas para ações corretivas.

### 2. **Gráfico de Cascata**
   - **Objetivo**: Avaliar a variação mensal de um dos três valores (lucro bruto, quantidade ou vendas) para cada país e produto.
   - **Características**:
     - Demonstra a contribuição mensal para o total anual.
     - Ajuda a identificar sazonalidade e tendências em mercados específicos.

### 3. **Gráfico de Colunas Empilhadas com Linha**
   - **Objetivo**: Visualizar a evolução mensal de um dos valores comparando ano atual e anterior.
   - **Características**:
     - Colunas empilhadas exibem os valores mensais.
     - Uma linha adicional mostra mudanças percentuais ou absolutas entre os anos.
     - Ideal para entender o desempenho agregado por mês.

### 4. **Gráfico de Dispersão**
   - **Objetivo**: Segmentar contas por GP% (Gross Profit Margin) e lucro bruto.
   - **Características**:
     - Cada ponto representa uma conta ou segmento.
     - O eixo X indica GP%, e o eixo Y, o lucro bruto.
     - Útil para priorizar contas de alta ou baixa rentabilidade.

---

## 🛠️ Metodologia

### 1. **Coleta de Dados**
   - Os dados foram extraídos de um arquivo Excel e validados para garantir a integridade.

### 2. **Transformação de Dados**
   - Processos de limpeza e preparação foram aplicados.
   - Métricas calculadas:
     
   - Basicas:
       - COGs
       - Gross Profit
       - Quantity
       - Sales
         
   - PYTD:
       - PYTD_GrossProfit
       - PYTD_Quantity
       - PYTD_Sales
         
   - YTD:
       - YTD_GrossProfit
       - YTD_Quantity
       - YTD_Sales
         
   - SWITCH:
       - S_PYTD
       - S_YTD
       - YTD vs PYTD

### 3. **Visualizações**
   - Gráficos criados com:
     - **Power BI** (opcional para deploy interativo).
   - Foco na clareza e relevância das análises.

---

## 🔧 Ferramentas Utilizadas

- Power BI
- Excel
  
---
