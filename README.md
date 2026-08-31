# FINANCE
# 💰 Controle Financeiro Pessoal

## 📌 Sobre o projeto

O projeto consiste no desenvolvimento de uma aplicação de **controle financeiro pessoal**, criada com o objetivo de auxiliar usuários no acompanhamento de suas finanças e na identificação de comportamentos que possam comprometer sua saúde financeira.

Atualmente, fatores como **compras online por impulso, apostas esportivas e influência das redes sociais** podem levar as pessoas a realizar gastos sem planejamento, comprometendo sua renda e dificultando o alcance de seus objetivos financeiros.

Diante desse cenário, a aplicação permitirá que o usuário registre suas **entradas e saídas financeiras**, categorize seus gastos, estabeleça limites e acompanhe sua situação financeira por meio de **gráficos e indicadores**.

Além disso, o sistema contará com um mecanismo de **alertas**, que notificará o usuário quando seus gastos atingirem ou ultrapassarem os limites definidos, ajudando-o a tomar decisões financeiras mais conscientes.

---

## 🎯 Objetivo

O objetivo principal da aplicação é **auxiliar o usuário no controle de suas finanças**, proporcionando uma visão clara de seus hábitos de consumo e alertando sobre situações que possam representar riscos financeiros.

A aplicação busca incentivar:

* Maior controle sobre os gastos;
* Planejamento financeiro;
* Identificação de gastos excessivos;
* Redução de compras impulsivas;
* Maior consciência sobre gastos com apostas;
* Acompanhamento da evolução financeira;
* Estabelecimento e acompanhamento de limites de gastos.

---

## 👥 Público-alvo

A aplicação é destinada principalmente a:

* Pessoas que possuem dificuldades em controlar seus gastos;
* Pessoas que desejam organizar sua vida financeira;
* Pessoas que realizam compras sem planejamento;
* Pessoas que desejam controlar gastos com apostas;
* Pessoas que possuem objetivos financeiros e desejam acompanhar sua evolução.

---

## ⚙️ Funcionalidades

### 👤 Usuário

* Cadastro utilizando usuário/e-mail e senha;
* Login utilizando usuário/e-mail e senha.

### 💵 Controle financeiro

* Cadastro de entradas financeiras;
* Cadastro de saídas financeiras;
* Edição de movimentações;
* Exclusão de movimentações;
* Consulta do histórico financeiro;
* Cálculo do saldo.

### 🏷️ Categorização

O usuário poderá classificar seus gastos em diferentes categorias, como:

* Alimentação;
* Transporte;
* Moradia;
* Lazer;
* Compras;
* Apostas;
* Educação;
* Outros.

Também será possível criar categorias personalizadas.

### 🚨 Alertas financeiros

O sistema poderá emitir alertas quando:

* O usuário atingir determinado percentual do limite definido;
* O usuário ultrapassar o limite de uma categoria;
* O usuário realizar um gasto considerado elevado.

Exemplo:

> ⚠️ Você já utilizou 80% do seu limite mensal para compras.

Ou:

> 🚨 Você ultrapassou o limite definido para apostas neste mês.

### 📊 Dashboard e gráficos

A aplicação apresentará informações financeiras de forma visual, permitindo ao usuário acompanhar:

* Total de entradas;
* Total de saídas;
* Saldo;
* Gastos por categoria;
* Evolução dos gastos;
* Comparação entre entradas e saídas;
* Categorias com maior volume de gastos.

---

## 🏗️ Estrutura do sistema

A aplicação terá como principais entidades:

```text
Usuário
   │
   └── Movimentações
          │
          └── Categorias
                 │
                 └── Limites
                        │
                        └── Alertas
```

Os gráficos e informações do dashboard serão gerados a partir dos dados financeiros cadastrados pelo usuário.

---

## 🔒 Segurança e privacidade

Nesta primeira versão, a aplicação **não terá integração com instituições bancárias**.

Não serão armazenados:

* CPF;
* Dados bancários;
* Número de cartão;
* Agência ou conta bancária;
* Informações de Pix;
* Extratos bancários;
* Outros dados bancários.

O sistema utilizará apenas as informações necessárias para o funcionamento da aplicação, principalmente **usuário/e-mail, senha e os dados financeiros inseridos manualmente pelo próprio usuário**.

As senhas deverão ser armazenadas de maneira segura, utilizando técnicas adequadas de proteção.

---

## 🚫 Fora do escopo inicial

A primeira versão do projeto não contemplará:

* Integração com bancos;
* Open Finance;
* Consulta automática de saldo bancário;
* Importação automática de extratos;
* Pagamentos;
* Transferências;
* Integração com Pix;
* Cadastro de cartões;
* Dados bancários.

Essas funcionalidades poderão ser consideradas em versões futuras.

---

## 📋 Requisitos principais

### Requisitos funcionais

* Cadastro de usuário;
* Login;
* Cadastro de entradas;
* Cadastro de saídas;
* Edição e exclusão de movimentações;
* Categorização de gastos;
* Definição de limites;
* Geração de alertas;
* Consulta de saldo;
* Histórico financeiro;
* Dashboard;
* Geração de gráficos.

### Requisitos não funcionais

* Segurança das senhas;
* Privacidade dos dados;
* Proteção das informações financeiras;
* Boa usabilidade;
* Bom desempenho;
* Responsividade;
* Integridade dos dados;
* Manutenibilidade;
* Compatibilidade com navegadores.

---

## 🧑‍💻 Equipe

| Integrante  | Responsabilidade principal            |
| ----------- | ------------------------------------- |
| **Victor**  | Estrutura do projeto e banco de dados |
| **Nicolas** | Entradas e saídas financeiras         |
| **Pedro**   | Categorias e limites de gastos        |
| **Milena**  | Sistema de alertas                    |
| **Gabriel** | Dashboard e gráficos                  |

---

## 🗂️ Gerenciamento do projeto

O desenvolvimento do projeto será acompanhado através do **Trello**, utilizando um fluxo de tarefas baseado em:

```text
Backlog → To Do → Doing → Done
```

As tarefas serão distribuídas entre os integrantes da equipe e acompanhadas durante o desenvolvimento.

---

## 🚀 Desenvolvimento

O projeto será desenvolvido de forma incremental, começando pelas funcionalidades essenciais da aplicação e posteriormente adicionando recursos complementares.

### Etapas previstas

1. Levantamento dos requisitos;
2. Modelagem do sistema;
3. Criação do banco de dados;
4. Desenvolvimento do cadastro e login;
5. Desenvolvimento do controle de entradas e saídas;
6. Implementação das categorias;
7. Implementação dos limites;
8. Desenvolvimento do sistema de alertas;
9. Desenvolvimento do dashboard;
10. Implementação dos gráficos;
11. Testes;
12. Correção de erros;
13. Documentação;
14. Apresentação final.

---

## 📈 Exemplo de funcionamento

Um usuário recebe:

**R$ 3.000,00**

E registra no sistema:

| Tipo    | Categoria   |    Valor |
| ------- | ----------- | -------: |
| Entrada | Salário     | R$ 3.000 |
| Saída   | Alimentação |   R$ 500 |
| Saída   | Transporte  |   R$ 300 |
| Saída   | Lazer       |   R$ 200 |
| Saída   | Compras     |   R$ 400 |
| Saída   | Apostas     |   R$ 100 |

O sistema utilizará essas informações para:

**1.** Calcular o saldo;

**2.** Categorizar os gastos;

**3.** Gerar gráficos;

**4.** Comparar os gastos com os limites definidos;

**5.** Emitir alertas quando necessário.

---

## 🎓 Finalidade acadêmica

Este projeto está sendo desenvolvido como parte de um trabalho acadêmico, com o objetivo de aplicar conhecimentos de **engenharia de software, levantamento de requisitos, modelagem UML, desenvolvimento de sistemas, banco de dados e gerenciamento de projetos**.

---

## 📄 Status do projeto

🚧 **Em desenvolvimento**

Novas funcionalidades e melhorias serão adicionadas durante as etapas de desenvolvimento do projeto.

## 🔗 Documentação e Protótipos

### 📌 Miro

(https://miro.com/welcomeonboard/a0ZmWWl4Vnh5VXdnRzdCZGE4ZFR6VW5YUXJUc09GMzhIekNIMXZIV0xtZ1pPV0Y3bm5EcVpNT0kyNS9IVWRZMU9ZUGtYVEsrQ3Ftazh0U1VOdSt2ZHF5SlBPbHRuZVhITzZzNkFVei9IWGNCMHdBbXZJYTI5YS9NUkpxa0E4MzFzVXVvMm53MW9OWFg5bkJoVXZxdFhRPT0hdjE=?share_link_id=665379564321)

### 🎨 Trello

https://trello.com/invite/b/6a9086903b5ed2758e7dd3c7/ATTI7490dcf74956897d56e9d8db5615273c441ECEC7/financecp456

### 🎨 Figma 

https://www.figma.com/make/oojsaNIjxd3kS7AqxcWlAM/Tela-de-login?t=zv23XFMV0XnhToWD-1


---

