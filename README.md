# Modelagem_DIO
Desafio: projeto conceitual banco de dados

Descrição do mini mundo:

Produtos:
  -Temos que vários produtos podem ser disponibilizados por vários fonecedores.
  -Um ou mais produtos podem compor um pedido
  -Os produtos podem ter vários vendedores distintos(terceiros)
  -Uma loja possui vários produtos, um produto pode estar em estoque ou não
Pedidos:
  -Os pedidos são criados por clientes e possuem informações relacionadas eles.
  -Um ou mais produtos compoem um pedido
  -O pedido por ser cancelado
Cliente:
  -Cliente pode se cadastrar no site com seu CPF ou CPNJ (PF ou PJ), isso pode ser definido no campo (éPF), se for PF, PF =1, se não, PF=0. E armazenamos seu documento em documento.
  -Endereço do cliente determina o valor do frete
