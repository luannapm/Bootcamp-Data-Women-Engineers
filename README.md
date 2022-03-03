# Bootcamp-Data-Women-Engineers
O Desafio irá testar suas habilidades nas seguintes competências:

✓ Habilidades com a linguagen SQL e T-SQL Comandos DDL e DML 

✓ Construção de 1 Pipeline de dados no SQL Server Integration Services (SSIS) 

1ª Parte – Conhecimentos de SQL e T-SQL(DDL e DML)

EXERCÍCIO 1
Criar o banco de dados chamado desafio(localmente) com as tabelas conforme diagrama de dados Figura 1.

EXERCÍCIO 2
Restaurar o arquivo treino.bak(localmente) para criar um banco de dados treino (versão SQL 2017 ou superior).

EXERCÍCIO 3
Liste todos os clientes com seus nomes e com suas respectivas cidades e estados

EXERCÍCIO 4
Liste o código do produto, descrição do produto e a descrição das categorias dos produtos que tenham o valor unitário na faixa de R$ 10,00 a R$ 1500

EXERCÍCIO 5
Liste o código do produto, descrição do produto e descrição da categoria dos produtos, e também apresente uma coluna condicional com o nome de "faixa de preço"
Com os seguintes critérios
• preço< 500 : valor condicional será igual "preço abaixo de 500"
• preço >= 500 e <=1000 valor condicional será igual "preço entre 500 e 1000"
• preço > 1000 : valor condicional será igual "preço acima de 1000".

2ª Parte – Desenvolvimento Pipeline SSIS

Desenvolva um pipeline de integração de dados usando o SSIS e realize a modelagem multidimensional ,desnormalizando os dados gerando e um DW a tabela fato e suas dimensões de acordo com seu entendimento e realize a carga de dados disponibilizados.
Crie seu projeto no SSIS com o nome Desafio_alunaXX
Origem de dados: BaseDadosDesafio.csv
Disponibilizada junto com arquivos do desafio.
Destino dos dados: Seu DW_XX (SQL Server Instalação Local)
