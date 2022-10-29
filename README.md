# Esquema de ecommerce

Escopo: Ecommerce

Narrativa: Produto
 - Os produtos são vendidos por uma única plataforma online. Contudo, eles podem ter vendedores distintos (terceiros)
 - Cada produto possui um fornecedor
 - Um ou mais produtos podem compor um pedido

Narrativa: Cliente
 - O cliente pode se cadastrar no site com seu CPF ou CNPJ
 - O endereço do cliente irá determinar o valor do frete
 - Um cliente pode realizar mais de um pedido. Cada pedido possui um período dentro do qual é possível realizar o retorno do(s) produto(s)

Narrativa: Pedido
 - Os pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega
 - O pedido é composto por um ou mais produtos
 - O pedido pode ser cancelado
