# 🌾 Dashboard de Vendas Agrícolas – Região Sudeste (2024)

Este projeto é um painel interativo criado no Microsoft Excel, com foco na análise de vendas de produtos agrícolas simulados, voltado especialmente para a **Região Sudeste**. Ele contempla transformação de dados com Power Query, análise com fórmulas e visualização com Tabelas Dinâmicas e gráficos.

---

## 📌 Objetivos

- Limpar e transformar dados simulados de vendas agrícolas
- Realizar análises por produto, região, mês e canal de venda
- Construir um dashboard interativo com indicadores visuais

---

## 🛠️ Ferramentas Utilizadas

- Excel com Power Query
- Tabelas Dinâmicas
- Gráficos (Coluna)
- Fórmulas (SOMASES, MÉDIASES, ÍNDICE, CORRESP)
- Segmentações de Dados
- Design customizado com ícones, cores e painéis

---

## 🔢 Estrutura dos Dados

Simulação com 200 linhas contendo:

- `Data`
- `Região`
- `Produto`
- `Canal de Venda`
- `Quantidade`
- `Preço Unitário`
- `Valor Total`

---

## 🔄 Etapas do Projeto

### 1. 📥 Importação e Limpeza com Power Query
- Conversão de tipos
- Criação de coluna `Mês` com `Date.MonthName`
- Filtro de dados (foco: Região Sudeste)

### 2. 📊 Tabelas e Gráficos Dinâmicos
- Análise de valor total vendido por produto e mês
- Filtro por região e produto com Segmentações

### 3. 🔢 Cálculo de Indicadores com Fórmulas
- `Produto mais vendido` com `ÍNDICE` + `CORRESP`
- `Total vendido (R$)` com `SOMASES`
- `Preço médio` com `MÉDIASES`

### 4. 🖼️ Montagem do Dashboard
- Design com painel cinza e caixas de destaque
- Título com ícone
- Integração de segmentações interativas
- Gráfico de colunas com evolução mensal


