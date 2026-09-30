# 💰 FINANCE — Checkpoint 5

## 📌 Engenharia de Software

Projeto desenvolvido para o **Checkpoint 5**, com foco na criação de um **protótipo funcional utilizando dados mockados**, permitindo a simulação dos principais fluxos de uma aplicação de controle financeiro pessoal.

---

## 👥 Integrantes

- Victor Augusto — RM 558338
- Milena Queiroz — RM 55825
- Pedro Henrique — RM 558867
- Gabriel Yeshua — RM 558273
- Nicolas Alvares — RM 557271

---

## 🎯 Objetivo do Projeto

O **FINANCE** é uma aplicação de gerenciamento financeiro pessoal desenvolvida para permitir que o usuário tenha uma visão simples e centralizada de sua vida financeira.

A aplicação possibilita o registro e acompanhamento de receitas e despesas, permitindo visualizar o saldo disponível, histórico de transações, categorias de gastos e análises financeiras.

Nesta etapa do projeto, correspondente ao **Checkpoint 5**, foi desenvolvido um protótipo funcional com dados simulados, permitindo a navegação e execução dos principais fluxos do sistema.

---

## 🚀 Funcionalidades Implementadas

O protótipo atualmente possui as seguintes funcionalidades:

### 🔐 Login

- Tela de autenticação
- Entrada utilizando usuário de teste
- Redirecionamento para o dashboard após autenticação
- Opção de visualização da senha
- Opção "Manter conectado"

### 🏠 Dashboard Financeiro

O dashboard apresenta ao usuário:

- Saldo disponível
- Total de receitas
- Total de despesas
- Total de economias
- Histórico de transações
- Identificação de saldo positivo ou negativo

Os valores são atualizados conforme novas movimentações são cadastradas.

### ➕ Registro de Movimentações

A aplicação permite registrar diferentes operações financeiras por meio do botão central de ações.

Entre as opções disponíveis estão:

- 💰 Inserir saldo
- 💸 Registrar gastos
- 🎯 Criar metas
- 🔔 Criar alertas

As movimentações realizadas são adicionadas automaticamente ao histórico financeiro do usuário.

### 💵 Receitas

O usuário pode registrar novas entradas financeiras.

Exemplos:

- Presente
- Salário
- Freelance
- Outros tipos de receita

Ao cadastrar uma receita:

1. O valor é adicionado ao saldo
2. O total de receitas é atualizado
3. A movimentação aparece no histórico
4. Os dados são refletidos na área de análise

### 💸 Despesas

O usuário também pode cadastrar gastos.

Exemplos:

- Alimentação
- Transporte
- Lazer
- Compras
- Outros

Quando uma despesa é registrada:

1. O valor é descontado do saldo
2. O total de despesas é atualizado
3. A transação aparece no histórico
4. A categoria é utilizada nas análises financeiras

---

## 📊 Análise Financeira

A aplicação possui uma tela específica para análise das movimentações financeiras.

São apresentados:

- Total de entradas
- Total de saídas
- Saldo atual
- Comparação entre receitas e gastos
- Distribuição das despesas por categoria
- Distribuição das receitas por categoria
- Detalhamento financeiro por categoria

As visualizações utilizam gráficos para facilitar a interpretação das informações.

---

## 🔄 Fluxo Principal do Sistema

```text
Usuário acessa a aplicação
        ↓
Realiza o login
        ↓
Acessa o Dashboard
        ↓
Visualiza seu saldo financeiro
        ↓
Seleciona uma nova movimentação
        ↓
Registra uma receita ou despesa
        ↓
Sistema salva a movimentação
        ↓
Saldo é recalculado
        ↓
Dashboard é atualizado
        ↓
Transação aparece no histórico
        ↓
Tela de análise é atualizada
