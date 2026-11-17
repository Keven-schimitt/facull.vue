# facull.vue
#Gestao-financeira-web
Um site voltado para os empresários que trabalham fazendo gestão financeira.

controle de entrada e saída, analise de credito, conferência bancária automática.

entidades relacionadas:

Cliente Representa a pessoa cujas finanças são administradas.
id: identificador do cliente

nome: nome completo

email: e-mail de contato

telefone: telefone de contato

dataCadastro: data de cadastro

LancamentoFinanceiro Representa uma movimentação financeira de um cliente.
id: identificador do lançamento

clienteId: cliente relacionado

descricao: motivo da movimentação

tipo: receita ou despesa

valor: valor monetário

data: data da movimentação

categoria: categoria financeira

GestorFinanceiro Representa o profissional que administra o sistema.
id: identificador do gestor

nome: nome completo

email: e-mail de acesso

senhaHash: hash da senha armazenada com segurança

telas previstas.

Painel financeiro Exibe o resumo das receitas, despesas, saldo e situação financeira dos clientes.

Listagem de clientes com filtros Permite pesquisar clientes por nome e e-mail e filtrar os registros.

Detalhes financeiros do cliente Mostra os lançamentos, receitas, despesas, saldo e filtros por período.

Área autenticada do gestor Permite entrar no sistema e gerenciar clientes e movimentações financeiras.
