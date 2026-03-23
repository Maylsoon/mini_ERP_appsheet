# 📊 Mini ERP de Vendas e Estoque com AppSheet

## 🚀 Visão Geral

Este projeto consiste na construção de um mini ERP (Enterprise Resource Planning) utilizando Google Sheets como banco de dados e AppSheet como interface de aplicação.

O sistema permite gerenciar produtos, controlar estoque em tempo real, registrar compras e vendas, além de gerar métricas financeiras automaticamente.

---

## 🎯 Objetivo

Criar um sistema funcional que simule um cenário real de negócio, aplicando boas práticas de modelagem de dados, validação de regras de negócio e automação de processos.

---

## 🧱 Estrutura do Sistema

### 📦 Produtos

* Cadastro de produtos com variações (tamanho e estampa)
* Preço e custo integrados com fornecedores

### 🛒 Compras

* Registro de entrada de estoque
* Validação para garantir que o produto existe no catálogo

### 💰 Vendas

* Registro de saída de estoque
* Validação por combinação (Produto + Tamanho + Estampa)
* Bloqueio de vendas com estoque insuficiente

### 📊 Estoque

* Calculado automaticamente:

  Estoque = SUM(Compras) - SUM(Vendas)

* Consulta de estoque disponível

---

## ⚙️ Regras de Negócio Implementadas

* ✔ Validação de produto existente no catálogo
* ✔ Validação por combinação (evita inconsistência de dados)
* ✔ Bloqueio de venda com estoque insuficiente
* ✔ Preço preenchido automaticamente
* ✔ Receita calculada automaticamente
* ✔ Sistema sem duplicidade de produtos
* ✔ Consulta de produtos disponíveis em estoque (> 0)

---

## 📈 Métricas Financeiras

O sistema gera automaticamente:

* Faturamento total
* Quantidade de vendas
* Ticket médio

---

## 🧠 Decisões Técnicas

* Uso do Google Sheets como banco de dados
* Lógica de negócio implementada no AppSheet (não no Sheets)
* Uso de colunas virtuais para cálculos dinâmicos
* Separação entre dados brutos e cálculos (boas práticas de modelagem)

---

## 🧪 Testes Realizados

* Cadastro de produtos válidos e inválidos
* Testes de compra e atualização de estoque
* Testes de venda com validação de estoque
* Testes de consistência dos dados

---

## 🖼️ Prints do Sistema

![menu do app](mini_ERP_appsheet/imagens/tela.appsheet2.png)

---

## 🚀 Próximas Evoluções

* Implementação de lucro automático
* Dashboard com gráficos
* Alertas de estoque baixo
* Filtros por período
* Integração com banco de dados mais robusto

---

## 💼 Aplicação no Mercado

Este projeto simula um sistema real de controle de vendas e estoque, demonstrando:

* Modelagem de dados
* Pensamento analítico
* Construção de regras de negócio
* Automação de processos

---

## 👨‍💻 Autor

Projeto desenvolvido por Maylson Maia como parte da evolução prática em Análise de Dados e construção de sistemas orientados ao negócio.

