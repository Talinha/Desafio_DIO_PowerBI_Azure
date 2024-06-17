Status: Finalizado 🏆


![PowerBI](https://img.shields.io/badge/Power%20BI--yellow?style=for-the-badge&logo=Power%20BI&logoColor=BLUE)
![Azure](https://img.shields.io/badge/Azure-blue?style=for-the-badge&logo=microsoft%20azure&logoColor=blue&labelColor=FFFFFF&link=https%3A%2F%2Fimages.app.goo.gl%2FK7PN1jYJd57x4q7A8)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)


# Objetivo do Projeto:


1.	Criar  uma instância na Azure para MySQL
2.	Criar um Banco de dados com scripts SQL
3.	Integração do Power BI com MySQL no Azure 
4.	Verificar problemas na base a fim de realizar o tratamento dos dados


## 1. Criação da instancia na Azure:


![image](https://github.com/Talinha/Desafio_DIO_PowerBI_Azure/assets/121242992/fdb01042-c32c-480d-9978-3db2db5c6da9)


## 2. Criação de um banco de dados MySQL:


Criação das tabelas: 


[SQL/script_bd_company.sql](https://github.com/Talinha/Desafio_DIO_PowerBI_Azure/blob/main/SQL/script_bd_company.sql)


População das tabelas:  


[SQL/insercao_de_dados_e_queries_sql.sql](https://github.com/Talinha/Desafio_DIO_PowerBI_Azure/blob/main/SQL/insercao_de_dados_e_queries_sql.sql)


## 3.	Integração do Power BI com MySQL no Azure:


![image](https://github.com/Talinha/Desafio_DIO_PowerBI_Azure/assets/121242992/75640c89-e042-4304-90b6-cc4718d72ae5)


![image](https://github.com/Talinha/Desafio_DIO_PowerBI_Azure/assets/121242992/9b9aa4ca-720a-4f3b-9f94-a6e065d4b66f)


## 4. Alterações realizadas nas tabelas no Power Query:


### Departament

1. Exclusão de colunas desnecessárias**: Remoção das colunas que não são relevantes para a análise.
2. Alteração do tipo de dados**: Modificação dos tipos de dados para garantir consistência e precisão.
3. Inclusão de coluna com nomes dos gerentes**: Adição de uma nova coluna que contém os nomes dos gerentes.

### Dependent

1. Exclusão de colunas desnecessárias**: Remoção das colunas que não são relevantes para a análise.
2. Alteração do tipo de dados**: Modificação dos tipos de dados para garantir consistência e precisão.

### Departament_Locations

1. Exclusão de colunas desnecessárias**: Remoção das colunas que não são relevantes para a análise.
2. Alteração do tipo de dados**: Modificação dos tipos de dados para garantir consistência e precisão.
3. Mescla com a tabela Departament**: Mesclagem da tabela `Departament_Locations` com a tabela `Departament` para trazer as colunas `Departament_Name`.
4. Mescla de colunas Departament_Locations com Departament_Name**: Integração das colunas `Departament_Locations` com `Departament_Name` para consolidar as informações.

### Employee

1. Exclusão de colunas desnecessárias**: Remoção das colunas que não são relevantes para a análise.
2. Alteração do tipo de dados**: Modificação dos tipos de dados para garantir consistência e precisão.
3. Substituição de valores null**: Substituição de valores null por números de gerência.
4. Mescla com a tabela Departament**: Mesclagem da tabela `Employee` com a tabela `Departament` para trazer as colunas `Manager` e `Departament_Name`.
5. Mescla de colunas Fname e Lname**: Integração das colunas `Fname` e `Lname` para criar uma coluna completa de nomes dos funcionários.

### Project

1. Exclusão de colunas desnecessárias**: Remoção das colunas que não são relevantes para a análise.
2. Alteração do tipo de dados**: Modificação dos tipos de dados para garantir consistência e precisão.

### Works_on

1. Exclusão de colunas desnecessárias**: Remoção das colunas que não são relevantes para a análise.
2. Alteração do tipo de dados**: Modificação dos tipos de dados para garantir consistência e precisão.

Essas transformações foram realizadas para garantir que os dados estejam limpos, consistentes e preparados para análises mais aprofundadas.










