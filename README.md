# 📊 Sales Dashboard – Xbox Game Pass (Excel)

## 🎯 Objetivo do Projeto

Desenvolver um Dashboard de Vendas interativo no Excel com foco em organização, visualização estratégica e análise de desempenho.

O projeto transforma dados brutos em indicadores visuais claros e dinâmicos, permitindo análise eficiente e suporte à tomada de decisão orientada por dados.

---

## 📁 Estrutura do Repositório

```
📂 sales-dashboard-excel
│
├── base.xlsx
├── dashboard_xbox_finalizado.xlsx
└── README.md
```

---

## 🗂️ Base de Dados

A base contém informações sobre assinaturas do Xbox Game Pass, incluindo:

- Subscriber ID  
- Nome do cliente  
- Plano contratado  
- Tipo de assinatura (Monthly, Annual, Quarterly)  
- Status de renovação automática (Auto Renewal)  
- Valores de assinatura  
- EA Play Season Pass  
- Minecraft Season Pass  
- Valor total da compra  

Os dados foram organizados na aba **Bases**, estruturados como Tabela (Ctrl + T) e utilizados como fonte para construção das Tabelas Dinâmicas.

---

## 📊 Estrutura do Dashboard

O dashboard foi desenvolvido na aba **Dashboard** do mesmo arquivo Excel.

### 🔹 Indicadores (KPIs)

- Total de vendas EA Play Season Pass  
- Total de vendas Minecraft Season Pass  
- Receita total consolidada  
- Receita segmentada por status de renovação automática  

### 🔹 Interatividade

- Segmentação por tipo de assinatura (Slicers)
- Atualização dinâmica dos KPIs
- Gráficos vinculados às Tabelas Dinâmicas
- Experiência de navegação semelhante a ferramentas de BI

### 🔹 Técnicas Utilizadas

- Tabela estruturada (Excel Table)
- Tabelas Dinâmicas
- Segmentação de Dados (Slicers)
- Conexão de relatório entre múltiplas tabelas
- Gráficos dinâmicos
- Modelagem simples baseada em agregações
- Organização visual inspirada em dashboards de Business Intelligence

---

## 🔄 Como Reproduzir

1. Abrir o arquivo `dashboard_xbox_finalizado.xlsx`
2. Acessar a aba **Dashboard**
3. Utilizar os filtros laterais para interagir com os dados
4. Observar a atualização automática dos KPIs e gráficos

Para recriação manual:

1. Transformar a base em Tabela (Ctrl + T)
2. Criar Tabelas Dinâmicas a partir da tabela estruturada
3. Inserir Segmentação de Dados
4. Conectar as segmentações a todas as Tabelas Dinâmicas
5. Construir os KPIs vinculando células das Tabelas Dinâmicas
6. Organizar o layout visual

---

## 📈 Principais Insights Possíveis

- Comparação de desempenho entre produtos
- Análise de impacto da renovação automática
- Distribuição de receita por tipo de assinatura
- Identificação de variações conforme plano contratado

---

## 🚀 Conclusão

Este projeto demonstra a capacidade de transformar dados transacionais em visualizações estratégicas no Excel, aplicando conceitos de organização de dados, agregação e construção de dashboards interativos.

Simula uma experiência próxima a ferramentas de BI como Power BI, evidenciando habilidades práticas em análise de dados e visualização.

---

Projeto desenvolvido como desafio prático de análise de dados.
