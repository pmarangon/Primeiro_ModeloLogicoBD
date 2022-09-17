#Criação Banco:
#Create Database Ecommerce;
Tabela Produto
Use Database Ecommerce
Create Table Produto(
  pk auto_increment  IDProduto Int,
  categoria VARCHAR(45),
  Descricao  VARCHAR(45),
)
Tabela Fornecedor:
Create table Fornecedor (
  pk auto_increment  IDFornecedor Int,
  Razao Social VARCHAR(45),
  CNPJ  VARCHAR(45)
  )
  Tabela pedido:
  (
  pk auto_increment  IDPedido Int,
  Status pedido Enum()
  Descricao  VARCHAR(45)
   CONSTRAINT fk_IDCliente int(ID_Cliente)
 );
 Tabela Cliente:
 create table Cliente(
  pk auto_increment  IDCliente Int,
  Nome VARCHAR(45),
 Nome do meio  VARCHAR(3),
 Sobrenome VARCHAR(20),
 CPF VARCHAR(11)
 Data de Nascimento DATE'                                                                                   )
 Tabela Produto:
 Create table Produto(
  pk auto_increment  IdProduto Int,
  Categoria VARCHAR(45)
  Descricao VARCHAR(45)
 )

Tabela Estoque:
Create Table Estoque(
  pk auto_increment IdEstoque Int,
  Local VARCHAR(45)
)
 Tabela Terceiro Vendedor:
 Create Table Terceiro Vendedor(
  pk auto_increment IdTerceiroVendedor Int,
   Razao Social VARCHAR(45)
  Local VARCHAR(45)

 )