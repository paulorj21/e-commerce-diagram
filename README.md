
# Modelo EER de um E-COMMERCE

### Diagrama EER de um e-commerce fictício criado para fins didáticos.

Projeto conceitual de um Banco de Dados feito para o desafio de projeto **"Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE"** da plataforma DIO.


## Narrativa

#### **Produto**
- Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros)

- Cada tipo de produto pode possuir um ou mais fornecedores

- Um ou mais produtos podem compor um pedido

- Cada tipo de produto podem estar em estoques diferentes

#### **Cliente**
- O cliente pode se cadastrar no site com seu CPF ou CNPJ

- O endereço do cliente irá determinar o valor do frete

- Um cliente pode comprar mais de um pedido. Este tem um tempo de carência para devolução do produto

#### **Pedido**
- Os pedidos são criados por clientes e possuem informações de compra, endereço e status de entrega

- Um produto ou mais compõem o pedido

- O pedido pode ser cancelado

#### **Fornecedor**
- Um fornecedor pode disponibilizar um ou mais produtos

#### **Estoque**
- Um estoque pode ter um ou mais produtos

- Um estoque possui determinada quantidade de um produto
