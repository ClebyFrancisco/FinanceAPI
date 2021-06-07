## FinAPI - Financeira

### Requisitos

- [x] Deve ser possível criar uma conta.
- [x] Deve ser possível buscar o extrato bancário do cliente.
- [x] Deve ser possível realizar um depósito.
- [x] Deve ser possível realizar um saque.
- [x] Deve ser possível buscar o extrato bancário do cliente por data.
- [] Deve ser possível atualizar dados da conta do cliente.
- [] Deve ser possível obter dados da conta do cliente.
- [] Deve ser possível deletar uma conta.

## Regras de Negócio

- [x] Não Deve ser possível cadastrar uma conta com um cpf já existente.
- [x] Não Deve ser possível fazer depósito em uma conta não existente.
- [x] Não Deve ser possível buscar extratos em uma conta não existente.
- [x] Não Deve ser possível fazer saque em conta não existente.
- [] Não Deve ser possível excluir uma conta não existente.
- [x] Não Deve ser possível fazer saque quando o saldo for insuficiente.