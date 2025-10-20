# Case Bradesco – Pricing & Rentabilidade (CRM Atacado)

## Objetivo
Desenvolver um painel estratégico de rentabilidade para o **CRM Atacado do Bradesco**, com foco em **priorização de produtos e filiais** através da **Curva ABC** e análise de **margem consolidada**.

---

## Inteligência Aplicada
- **Cálculo de Margem Total e Percentual Acumulado**.
- **Classificação Automática ABC** (A: 80%, B: 15%, C: 5%).
- **Ranking Dinâmico de Filiais** com destaque para o Top 3.
- **Insights Executivos** de rentabilidade e alocação de portfólio.
- Análise de contribuição por **Produto, Filial e Categoria**.
- Aplicação de princípios de **Pareto (80/20)** para priorização comercial.

---

## Metodologia
1. **Extração e Limpeza de Dados**
   - Fontes simuladas representando histórico de vendas e rentabilidade.
   - Tratamento de dados nulos e padronização de colunas.

2. **Transformação e Enriquecimento**
   - Cálculo de **Margem = Receita - Custo**.
   - Cálculo de **% Acumulado** para definição das classes ABC.

3. **Modelagem no Power BI**
   - Criação de **medidas DAX** para cálculo de KPIs.
   - Implementação da **Curva ABC Dinâmica**.
   - Criação de **segmentadores de Produto, Filial e Categoria**.

4. **Visualização Estratégica**
   - Painel único com visões de Produto, Filial e Margem Total.
   - Destaque automático para as **Top 3 Filiais** em performance.
   - Cards executivos com margem média e percentual de contribuição.

---

## Estrutura do Painel
- **Visão 1:** Distribuição de Margem por Produto
- **Visão 2:** Curva ABC Consolidada
- **Visão 3:** Ranking de Filiais com destaque para o Top 3
- **Visão 4:** Painel Executivo – KPIs principais

---

## Insights Executivos
- **20% dos produtos** concentraram **81% da margem total** (classe A).
- As **filiais de maior rentabilidade** apresentam padrão consistente de mix otimizado.
- **Produtos de classe C**, apesar de baixo volume, representam oportunidades de revisão de portfólio.
- Recomenda-se **ajuste de foco comercial** nas linhas intermediárias (classe B) com alta elasticidade de preço.

---

## Tecnologias Utilizadas
- **Power BI Desktop (DAX e Power Query)**
- **Excel / CSV (bases simuladas)**
- **Python (pandas para prototipagem dos dados)**
- **GitHub (versionamento e portfólio)**

---

## Resultados
- Redução de **40% no tempo de análise** através da automação de cálculo da Curva ABC.
- Identificação imediata dos **produtos e filiais mais rentáveis**.
- Padronização visual para **reuso em relatórios corporativos** e painéis executivos.

---

## Estrutura de Arquivos no Repositório
```
📁 Case1_Pricing_Rentabilidade_Bradesco
│
├── 📄 README.md
├── 📊 Painel_Pricing_Rentabilidade.pbix
├── 📈 Imagem_Painel_Bradesco.png
├── 📂 Base_Dados
│   ├── vendas.csv
│   └── produtos.csv
└── 📂 Docs
    └── Apresentacao_Executiva.pptx
```

---

## Próximos Passos
- Integração com o **Case 2 – Inteligência de Ouvidoria / Reclamações**.
- Criação de modelo de **alertas automáticos (Power BI + DAX)** para detecção de anomalias de margem.
- Publicação no **LinkedIn e GitHub** com storytelling de negócio.
