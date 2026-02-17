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

*(inserir imagem da modelagem caso deseje)*

---

## 🧭 Navegação e parâmetros

Foram criados parâmetros para permitir que o usuário navegue entre diferentes análises:

- Quantidade vendida ou Receita  
- Visão por Cliente  
- Visão por Produto  
- Visão por Vendedor  
- Visão por Ano.Mês  

Os filtros afetam toda a página dinamicamente.

*(inserir imagens dos botões / navegação)*

---

## 🧮 Transformações realizadas (DAX)

Foi criada uma coluna separando **Cidade** e **Estado** a partir do endereço, permitindo filtros geográficos.

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

## 📬 Contato

Autor: **Filipe Godoy**  
Este é meu primeiro repositório no GitHub 🚀  
