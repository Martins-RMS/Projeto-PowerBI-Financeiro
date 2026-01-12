# 📊 Projeto Power BI: Análise Financeira e Fluxo de Caixa

## 🔹 Contexto
Projeto guiado em Power BI com foco em **análise financeira e fluxo de caixa** de uma empresa fictícia, cobrindo todas as etapas da análise de dados: **ETL, modelagem, DAX e visualização**.

O objetivo: criar um dashboard que permita **insights claros e tomada de decisão baseada em dados**, aplicando boas práticas de BI e storytelling.

### Requisitos atendidos:
- **Área de atuação:** Financeira  
- **Início das atividades:** 2017  
- **Fonte de dados:** Excel (OneDrive)  
- **Análise da movimentação financeira**, incluindo receitas, custos, despesas, lucro e detalhes como:  
  - Receita por mês vs. mês do ano anterior  
  - Receita por tipo de conta  
  - Pagamentos por tipo de conta  
  - Pagamentos por tipo e mês  
  - Receita por cliente  
  - Fluxo de caixa por mês em gráfico de cascata e detalhada em tabela (tela dedicada)  

---

## 🛠️ ETL (Extração, Transformação e Carga)
- Importação de **múltiplas planilhas simultaneamente**  
- **Padronização de cabeçalhos** para facilitar união de dados  
- **Criação de funções no Power Query** para tabelas com cabeçalhos diferentes  
- **Construção de tabela calendário** via `List.Dates` para análise temporal e hierarquia de datas  

---

## 🧱 Modelagem de Dados
- **Modelo estrela** (fato e dimensões)  
- **Tabelas fato:** recebimentos e pagamentos  
- **Tabelas dimensão:** contas e calendário  
- Relacionamentos definidos de forma **lógica e eficiente**  

---

## 📊 Métricas Financeiras (DAX)
- Receita  
- Custo  
- Despesa  
- Lucro  
- Margem de lucro (%)  

---

## 📈 Visualizações e UX
- KPIs financeiros (receita, despesa, custo e lucro)  
- Evolução da receita ao longo do tempo – **gráfico de colunas**  
- Receita por tipo de conta – **gráfico de pizza**  
- Pagamento por tipo de conta – **gráfico de pizza**  
- Pagamento por mês e tipo de conta – **gráfico de colunas empilhadas**  
- Receita por clientes – **gráfico de barras**  
- Fluxo de caixa por mês – **gráfico cascata (waterfall)**  
- Matriz consolidando todas as medidas, com **formatação condicional**  
- Botões de navegação e imagens de fundo para **padrão visual consistente**  

> **Dica:** você pode colocar imagens do dashboard aqui usando:  
> `![Nome da imagem](Imagens/nome_da_imagem.png)`

---

## 💡 Principais Insights
- Meses com **prejuízo** e impacto no fluxo de caixa  
- Clientes mais relevantes para a receita  
- Impacto dos **tipos de pagamento** na receita da empresa  
- Experiência prática em **todo o fluxo de dados**, do ETL à visualização final  

---

## ✅ Tecnologias Utilizadas
- Power BI Desktop  
- Power Query  
- DAX  
- Modelagem de dados estrela  

---

## 📚 Créditos
Projeto guiado pelo canal: **Nogueira Junior – Hands-on**
