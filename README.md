# 📊 Projeto Power BI – Análise de Vendas

Este projeto demonstra a criação de um dashboard interativo no **Power BI**, utilizando dados fictícios de vendas e clientes, publicados no GitHub.  
O objetivo é apresentar uma solução completa de conexão, modelagem, navegação e análise por diferentes visões.

---

## 📁 Dados utilizados

Os arquivos foram gerados via Copilot e publicados no repositório:

- **Vendas**  
  [dados_vendas.xlsx](https://github.com/FilipeGodoy/Power-Bi/raw/refs/heads/main/dados_vendas.xlsx)

- **Clientes**  
  [dados_clientes.xlsx](https://github.com/FilipeGodoy/Power-Bi/raw/refs/heads/main/dados_clientes.xlsx)

As tabelas incluem:

### Tabela de Vendas
- Nome do Produto  
- Vendedor  
- Quantidade vendida  
- Receita  
- Ano e Mês (últimos 12 meses)  
- Cliente (ID)

### Tabela de Clientes
- ID  
- Nome  
- Endereço  
- Telefone  
- E-mail  

---

## 🔗 Modelagem dos dados

As duas tabelas foram conectadas através do **ID do Cliente**.

<img width="1035" height="407" alt="image" src="https://github.com/user-attachments/assets/c4b779f6-4d18-4eb4-a0be-d6dcbb128a8b" />


---

## 🧭 Navegação e parâmetros

Foram criados parâmetros para permitir que o usuário navegue entre diferentes análises:

- Quantidade vendida ou Receita  
- Visão por Cliente  
- Visão por Produto  
- Visão por Vendedor  
- Visão por Ano.Mês  

Os filtros afetam toda a página dinamicamente.

<img width="773" height="34" alt="image" src="https://github.com/user-attachments/assets/913ec59f-b1bc-4504-a2b1-78505fcaba33" />


---

## 🧮 Transformações realizadas (DAX)

Foi criada uma coluna separando **Cidade** e **Estado** a partir do endereço, permitindo filtros geográficos.

<img width="672" height="131" alt="image" src="https://github.com/user-attachments/assets/d02d7c87-a725-4cab-b941-99182d77b9ef" />

---

## 🎛️ Filtros aplicados

Incluídos filtros para:

- Cidade  
- Estado  
- Produto  
- Cliente  
- Vendedor  

---

## 📈 Ordenação dos gráficos

- Quando filtrado por **Ano.Mês**, o gráfico é ordenado por evolução temporal.  
- Para demais categorias, a ordenação é por maior valor (Top N).

---

## 🚀 Como abrir o projeto

1. Baixe este repositório
2. Abra o Power BI Desktop
3. Conecte-se aos arquivos Excel (links acima)
4. Atualize as consultas
5. Explore o dashboard

---

## 🚀 Anexei também um BI chamado "PowerBI_Estágio de PerformanceV2.pbix" que ajudei um amigo a conseguir um Estágio no Red Bull Bragantino.

## 📬 Contato

Autor: **Filipe Godoy**  
19 995303113
Este é meu primeiro repositório no GitHub 🚀  
