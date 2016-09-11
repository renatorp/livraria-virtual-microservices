# livraria-virtual-microservices

## Aplicação de micro-serviços híbrida

Aplicações ASP .NET Core, Node.JS(Yeoman) e Spring Boot contendo os seguintes micro-serviços:

- Micro-serviço de autenticação baseado em OpenID do Google [Node.JS gerado a partir do Yeoman]
- Micro-serviço de consulta de livros em uma livraria virtual [ASP.NET Core gerado a partir do Yeoman]
- Micro-serviço de gerenciamento de carrinho de compras em uma livraria virtual [ASP.NET Core gerado a partir do Yeoman]
- Micro-serviço de pagamento e despacho de livros em uma livraria virtual [Spring Boot gerado a partir de start.spring.io]

Somente usuários autenticados podem fazer consultas de livros, gestão do
carrinho de compras. e pagamentos na livraria virtual. O serviço de
pagamento requer acesso ao carrinho de compras do usuário para pegar os
livros, calcular preços e montar o pacote de despacho para o cliente. Use
APIs REST para prover comunicação entre os micro-serviços conforme
apropriado.

## Geradores:
- Passport (Autenticação no Node.JS)
https://github.com/ni4ka7a/generator-express-passport-auth
- Spring Boot - https://start.spring.io
- ASP.NET Core - https://github.com/omnisharp/generator-aspnet
