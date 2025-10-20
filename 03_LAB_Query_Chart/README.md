<img src="https://raw.githubusercontent.com/Databricks-BR/lab_sql/main/images/header_handson_sql.png">

# Hands-On LAB 05 - Criando uma visualização na QUERY

Treinamento Hands-on na plataforma Databricks com foco nas funcionalidades de Analytics (SQL, Query, Dask, DataViz, SQL end-point).


## Objetivos do Exercício

O objetivo desse laboratório é explorar as funcionalidade de consultas com Gráficos de Visualização e Filtros</br>
</br>

Vamos utilizar o "Editor SQL".

## Exercício 05.01 - Criação da Query

``` sql


SELECT * FROM academy.SEU_NOME.bronze_dolar;


```
Resultado da Query:
<img src="https://raw.githubusercontent.com/Databricks-BR/lab_sql/main/images/lab05_01.png" style="height: 200px;">
</br></br>

## Exercício 05.02 - Criando a Visualização e o Filtro

Na barra de resultados, clique no botão **"+"**, e escolha a opção "Visualization".

<img src="https://raw.githubusercontent.com/Databricks-BR/lab_sql/main/images/lab05_02.png" style="height: 200px;">

</br></br>
No Visualization Type, escolha "LINE":

<img src="https://raw.githubusercontent.com/Databricks-BR/lab_sql/main/images/lab05_03.png" style="height: 200px;">

</br></br>
Na "X Column" (eixo X), escolha a variável  "dolar_dia".

<img src="https://raw.githubusercontent.com/Databricks-BR/lab_sql/main/images/lab05_04.png" style="height: 200px;">

</br></br>
Na "Y Columns" (eixo Y), escolha a variável  "dolar_fechamento".</br>
Escolha também a forma de agregação:  Média (Average).

<img src="https://raw.githubusercontent.com/Databricks-BR/lab_sql/main/images/lab05_05.png" style="height: 200px;">

</br></br>
Clique no título da visualização e renomeie para "grafico_dolar".

<img src="https://raw.githubusercontent.com/Databricks-BR/lab_sql/main/images/lab05_06.png" style="height: 150px;">

O resultado esperado é igual ao gráfico abaixo:

<img src="https://raw.githubusercontent.com/Databricks-BR/lab_sql/main/images/lab05_07.png" style="height: 500px;">

</br></br>

Clique novamente no botão **"+"**, e adicione um FILTRO:

<img src="https://raw.githubusercontent.com/Databricks-BR/lab_sql/main/images/lab05_09.png" style="height: 150px;">

</br></br>

Escolha a coluna "dolar_ano" para utilizar no FILTRO:

<img src="https://raw.githubusercontent.com/Databricks-BR/lab_sql/main/images/lab05_10.png" style="height: 300px;">

</br></br>
Resultado ficará como abaixo:

<img src="https://raw.githubusercontent.com/Databricks-BR/lab_sql/main/images/lab05_11.png" style="height: 250px;">

</br></br>

Salve o resultado da Query, com o nome:   "Query_Historico_dolar_" +  <SEU_NOME>.
</br></br></br>

