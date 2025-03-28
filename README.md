FIAP Checkpoint 1
Descrição
Este projeto é uma API Spring Boot para gerenciar pedidos de clientes, desenvolvida como parte do Checkpoint 1 da disciplina de Arquitetura SOA e Web Services.
Estrutura do Projeto
Apply
Entidades
Pedido
id: Long, chave primária, gerada automaticamente.
clienteNome: String, não pode ser nulo ou vazio.
dataPedido: LocalDate, preenchida automaticamente com a data atual.
valorTotal: double, não pode ser negativo.
Endpoints
GET /pedidos: Retorna a lista de pedidos cadastrados.
GET /pedidos/{id}: Retorna um pedido pelo ID.
POST /pedidos: Cria um novo pedido.
PUT /pedidos/{id}: Atualiza um pedido existente.
DELETE /pedidos/{id}: Remove um pedido pelo ID.
Configuração do Banco de Dados
Utiliza o H2 Database como banco de dados em memória. O console do H2 está habilitado para visualização dos dados.
Testes
Utilize o Postman ou outra ferramenta similar para testar os endpoints. Testes obrigatórios incluem:
Criar um novo pedido.
Buscar todos os pedidos.
Buscar um pedido pelo ID.
Atualizar um pedido.
Deletar um pedido.
Como Executar
Clone o repositório.
Navegue até o diretório do projeto.
Execute o projeto com o Maven ou sua IDE preferida.
Contribuição
Sinta-se à vontade para contribuir com melhorias ou correções.
