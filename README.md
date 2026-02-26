💰 Sistema Bancário - API de Transações e Gestão

Este projeto foi desenvolvido como um desafio técnico para simular a lógica de um banco digital. Embora o foco inicial tenha sido o desenvolvimento Back-end, a estrutura de dados aqui implementada é a base para análises de comportamento financeiro e saúde de carteira.


🚀 Contexto de Negócio

O sistema gerencia contas bancárias, permitindo operações de depósito, saque e transferências entre contas. Como Representante de Negócios na Ambev, entendo que sistemas transacionais como este são a fonte primária para KPIs de volume de vendas e positivação de clientes.

🛠️ Tecnologias e Conceitos de Dados

Node.js & Express: Construção da lógica de negócio e rotas.

Manipulação de JSON/Arrays: Estruturação de dados para persistência (equivalente a tabelas de fatos e dimensões).

Lógica de Saldo: Implementação de cálculos matemáticos para atualização em tempo real (essencial para Data Validation).

Data & Hora: Registro de date em cada transação, permitindo análises de séries temporais (Time Series).

📊 Visão de Analista: Transformando Código em Insights

Se eu fosse analisar os dados gerados por esta API hoje, eu buscaria responder:
Ticket Médio de Transferência: Identificar o valor médio movimentado entre usuários.
Análise de Retenção: Quais usuários realizaram depósitos mas não fizeram saques (acumuladores)?
Pico de Operações: Em quais horários ou datas o volume de transações é maior?

📁 Como executar
Clone o repositório: git clone https://github.com
Instale as dependências: npm install
Inicie o servidor: npm run dev
