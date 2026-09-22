# Mecanica-Maria-Rayssa-Lellis
DESCRITIVO: Sistema que permita o cadastro e gerenciamento de clientes, veículos e agendamentos, com autenticação de usuários e controle seguro de dados.
RESPONSÁVEIS: Rayssa Marques, Isabella Léllis e Maria Clara Silva

##Front 
 Lista das ações necessárias no front ( telas e comportamento )
- Tela para login com tempo de expiração
- Tela de busca de clientes
- Tela com listagem de agendamentos

##Backend
Lista dos controllers:
- MecanicosController
- VeiculosController
- ClientesController
- AgendamentosController

 Lista das Entidades e seus relacionamentos
- Mecanico -> Agendamento
- Cliente -> Agendamento, Veiculo

  Lista das Rotas
- POST: cadastrar cliente e veiculo, fazer agendamento
- GET: para buscar os clientes ou veículos na lista
- DELETE: para excluir agendamento cancelados
- PUT: para atualizar agendamento ou informações
