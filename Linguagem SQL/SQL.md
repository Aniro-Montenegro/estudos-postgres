# **Linguagem SQL**

SQL => Structure Query Language (Linguagem Estruturada de Consulta)
>Nome dado à linguagem responsável pela interação com os dados armazenados
>na maioria dos bancos de dados relacionais.

## **Recursos Utilizados**
1. **Consultas**: Possibilidade de capturar do banco de dados informações armazenadas.
2. **Atualizações**: Torna possível a atualização das informações armazenadas no banco 
de dados de sistemas conectados ao banco.
3. **Filtros e ordenações**: Os dados retornados de uma consulta podem voltar ordenados e formatados.

## **Criar banco de dados**
>Criar banco de dados *banco_estudo*
>Rodar o Script para criação de tabelas e inserção de dados Banco_dados.sql

## **Instrução select**
>O comando select é utilizado na realização de consultas ao banco de dados, retornando
> sempre os dados solicitados em formato de tabelas

````sql
SELECT *campo*  FROM *tabela*
````
````sql
SELECT NOME FROM TB_FUNCIONARIOS;
````
>Resultado:
<div>
<img src="/Imagens/primeiro-select.png" style="width:800px;height:600px;">
</div>

> Podemos solicitar mais de um campo para ser exibido na consulta
````sql
SELECT NOME, CARGO FROM TB_FUNCIONARIOS;
````
>Resultado:
<div>
<img src="/Imagens/select-dois-campos.png" style="width:800px;height:600px;">
</div>

> Retornando todos os campos 
````sql
SELECT * FROM TB_FUNCIONARIOS;
````
>Resultado:
<div>
<img src="/Imagens/select-from.png" style="width:800px;height:600px;">
</div>