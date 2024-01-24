# bancodedados
 banco de dados
## SGBD
Sistema gerenciador de banco de dados 

BANCO DE DADOS
SITEMA QUE ARMAZENA DADOS E FERRAMENTAS PARA GERENCIAR O MESMO, REPRESENTADO POR MINIMUNDOS, QUE SEGUE O CONTEXTO EM RELAÇÃO AO MESMO.

LINHA OU TUPLA = REGISTRO

COLUNA OU ENTIDADE

# Trabalhando com mysql
##conctando
mysql -h localhost -u root

## -h ##
computador que vai conectar

## -u ##
o usuario

## show databases; ##
mostrar dados 

## drop databases ## 
apaga linha do banco de dados

## creat table ##
criar tabelas 

## desc ##
nome da tabela

## show table ## 
exibe a tabela

## drop ##
exclui o banco de dados 

conectar no servidor de banco de dados:
`mysql -h localhost -u`

mostrar todos os bancos de dados do servidor:
`show databases;`


# comandos SQL
## DDL
- `create database nome_do_banco`
- `show databases`
- `create table nome_da_tabela`
- `show tables`
- `desc nome_da_tabela`

## DML MANIPULAÇÃO DE DADOS 
- select * from nome_da_tabela 
- insert info nome_da_tabela(campo1)