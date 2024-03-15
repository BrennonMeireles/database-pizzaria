# Banco de Dados de uma Pizzaria

Este projeto foi desenvolvido como parte de uma atividade prática na aula de banco de dados do curso no SENAI. O objetivo era projetar um banco de dados para uma pizzaria, capaz de armazenar informações sobre clientes, pedidos de pizza, detalhes das pizzas oferecidas e bebidas disponíveis.

## Requisitos do Banco de Dados

### Clientes
- Cada cliente deve ter um registro no banco de dados contendo seu nome, endereço, número de telefone e um identificador único.

### Pedidos
- O sistema deve ser capaz de registrar os pedidos feitos pelos clientes, incluindo detalhes como a data e hora do pedido, a lista de pizzas pedidas e a quantidade de cada pizza, as bebidas pedidas e sua quantidade, e o valor total do pedido.

### Pizzas
- O sistema deve armazenar informações sobre as pizzas oferecidas pela pizzaria, incluindo o nome da pizza, a massa utilizada, a borda, os sabores disponíveis e os preços.

### Bebidas
- O sistema deve manter um registro das bebidas disponíveis para os clientes, incluindo a descrição e o preço de cada bebida.

### FornadasPizza
- O sistema deve armazenar informações sobre as pizzas oferecidas pela pizzaria, horario da fornada, pedido da qual a fornada faz parte, quantidade produzida, status por exemplo, concluída, em andamento.

### Outras Entidades Relevantes
- Além das entidades principais, outras entidades e relacionamentos foram identificados como relevantes para o funcionamento da pizzaria, como fornadas de pizzas e ingredientes utilizados nas pizzas.

## Estrutura do Banco de Dados

O banco de dados foi projetado com as seguintes tabelas principais:

1. **Clientes**: Armazena informações sobre os clientes, como nome, endereço, telefone e ID único.
2. **Pedidos**: Registra os pedidos feitos pelos clientes, com detalhes como data e hora do pedido, lista de pizzas e bebidas, e o valor total.
3. **Pizzas**: Contém informações sobre as pizzas oferecidas, incluindo nome, tipo de massa, borda, sabores disponíveis e preço.
4. **Bebidas**: Mantém registros das bebidas disponíveis, com descrição e preço.
5. **Outras entidades**: Tabelas adicionais foram criadas para relacionamentos muitos-para-muitos, como `IngredientesPorPizza`, para armazenar os ingredientes utilizados em cada pizza.

## Tecnologias Utilizadas

O banco de dados foi projetado utilizando SQL, e pode ser implementado em diversos sistemas de gerenciamento de banco de dados relacionais, como MySQL, PostgreSQL, SQL Server, entre outros.

## Como Utilizar

Para implementar o banco de dados, basta executar os scripts SQL fornecidos neste repositório no sistema de gerenciamento de banco de dados de sua escolha. Certifique-se de seguir as instruções de criação das tabelas e relacionamentos.

## Diagrama Entidade-Relacionamento (Modelo Lógico)
A seguir está o diagrama ER que representa a estrutura do banco de dados da pizzaria:

![image](https://github.com/BrennonMeireles/database-pizzaria/assets/141636246/5fc73a04-b02f-459e-8614-b3a38757c711)

## Exemplos de Uso
Os dados armazenados no banco de dados da pizzaria podem ser utilizados para diversos fins, como:

Gerar relatórios de vendas e análise de desempenho.
Facilitar o gerenciamento de estoque de ingredientes e bebidas.
Oferecer uma experiência personalizada aos clientes, baseada em seus históricos de pedidos.
Considerações de Desempenho e Escalabilidade
Para garantir um bom desempenho e escalabilidade do sistema, é importante considerar:

Indexação adequada das tabelas para otimizar consultas.
Utilização de técnicas de cache para reduzir o tempo de resposta.
Monitoramento constante do desempenho do banco de dados e ajustes conforme necessário.
Este projeto proporcionou uma oportunidade valiosa para aplicar conceitos de modelagem de banco de dados na prática, e desenvolver uma solução que atenda às necessidades de uma pizzaria fictícia.

Para quaisquer dúvidas ou sugestões, sinta-se à vontade para entrar em contato.

