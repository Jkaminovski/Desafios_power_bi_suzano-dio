# Desafio de Modelagem Dimensional

## **Descrição do Desafio**
📝 O objetivo deste desafio é aplicar os conceitos de modelagem dimensional para criar um **diagrama dimensional** no formato de **esquema em estrela (star schema)**, utilizando tabelas relacionadas a vendas.

---

## **Objetivo**

🎯 Criar o **diagrama dimensional** com base nos requisitos fornecidos, centrado na análise de vendas.

---

## **Foco**

### **Vendas – Objeto de Análise**

📊 A análise será baseada nos dados de **vendas**, considerando informações sobre:
- 🛒 Produtos vendidos;
- 🌍 Regiões onde ocorreram as vendas;
- 📆 Calendário (datas das vendas);
- 🧑‍💼 Vendedores envolvidos no processo.

---

## **Tarefas a Realizar**

1. **Tabela Fato:**
   - 🏷️ Criar uma tabela fato que consolide os dados de vendas, incluindo informações como:
     - 📦 Quantidade vendida;
     - 💰 Valor total da venda;
     - 🔑 Chaves para as tabelas dimensão.

2. **Tabelas Dimensão:**
   - 🌍 **Dimensão Região:**
     - Detalha as regiões onde ocorreram as vendas (país, estado, cidade, etc.).
   - 🛒 **Dimensão Produto:**
     - Contém informações sobre os produtos vendidos (nome, categoria, preço, etc.).
   - 📆 **Dimensão Calendário:**
     - Representa as datas relacionadas às vendas, com níveis de granularidade como ano, mês, dia, etc.
   - 🧑‍💼 **Dimensão Vendedor:**
     - Fornece detalhes sobre os vendedores (nome, região, metas, etc.)


![image](https://github.com/user-attachments/assets/baf01613-0218-4a4d-bc9f-af356776c218)

