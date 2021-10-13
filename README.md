# QATest

1.

Cenário 01: Enviar uma mensagem para o cliente que participa do clube de cliente quando um produto consumido entrar em promoção
Dado que enviarei uma mensagem para o cliente 
E irá notifica-lo
Quando os produtos mais consumidos pelo cliente entrarão em promoção 
Então o sistema deve mostrar os produtos mais consumidos pelo cliente com o valor já alterado.

Cenário 02: Verificar se o cliente não comprou o produto nos últimos 5 dias
Dado que o sistema irá verificar quais os produtos comprados pelo cliente 
E irá fazer uma busca atraves de um filtro com uma data personalizada de 5 dias 
E irá filtrar por ordem decrescente
Quando ele listar os produtos mais antigos
Então irá exibir em ordem decrescente os produtos que não foram adquiridos nos últimos dias

Cenário 03: Verificar se a mensagem foi salva no sistema
Dado que foi enviado ao cliente uma mensagem
E nela continha as informações sobre o produto 
E a promoção
Quando sistema enviar a mensagem
Então ele irá guarda-lá no banco de dados

Cenário 04: Verificar se o preço está vindo com o desconto.
Dado que o sistema irá verificar os produtos 
E os preços cadadastrados com os descontos pré-cadastrados no cadastro do produto
Quando houver promoção 
Então o sistema irá trazer aquele produto com os descontos que já foram pré-cadastrados

Cenário 05: Verificar se o escopo da mensagem está trazendo os produtos mais consumidos pelo cliente.
Dado que no envio da mensagem para o cliente 
E no escopo
Quando a api for listar os produtos
Então deve verificar quais foram os mais comprados pelo cliente


Cenário 06: Verificar se o escopo da mensagem não está vindo em branco.
Dado que o sistema irá enviar a mensagem para o cliente 
E será exibido as informações sobre as promoções
Quando o cliente abrir o escopo da mensagem
Então deve conter todas informações de forma correta, como seu nome, produto e preço/promoção. 

Cenário 07: Verificar se o sistema irá trazer indicações.
Dado que o sistema irá enviar a mensagem para o cliente 
E irá exibir os produtos em promoção 
Quando os produtos forem listados
Então deve trazer pelo menos um parecido para o cliente com a promoção aplicada.


4.

Definição de Pronto:
1. A funcionalidade/correção foi implementada
2. A funcionalidade/correção foi testada no ambiente de QA
3. A funcionalidade/correção está disponível em PROD


1.  funcionalidade após ter sido implementada pela equipe de desenvolvimento, deve passar para o 
time de qualidade verificar o que foi adicionado de novo no sistema e qual impacto irá causar dentro do mesmo,
o que pode gerar ou não bugs para ser encaminhado novamente ao time de desenvolvimento.


2. A partir disso, quando as correções forem aplicadas, será realizado um teste confirmação através dos relatos dos 
erros com um passo-a-passo com evidencias para o melhor entedimento do time de desenvolvimento.

3.  Quando todas as correções forem aplicadas da devida forma(após ter passsado ou não por bugs e melhorias) estará pronta
para ser enviada a produção.


