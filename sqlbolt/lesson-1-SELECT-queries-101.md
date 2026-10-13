# SQL Lesson 1: SELECT queries 101

- Query: Consultas são declarações que descrevem quais dados estamos procurando, onde encontrá-lo no banco de dados, e opcionalmente como transformá-lo antes de ser retornado.
- Tabela: Em SQL, pode ser pensada como uma entidade, e cada linha como uma instância. Isso significa que as colunas representam propriedades comuns a todas as instâncias.
- Consulta básica:

```
SELECT coluna, outra_coluna
FROM tabela;
```
- Resultado: conjunto de linhas e colunas, uma cópia da tabela, somente com as colunas solicitadas

- ```SELECT *```: retorna todas as colunas da tabela


# Exercício

- Contexto: Usaremos um banco de dados com dados sobre alguns filmes clássicos da Pixar. Este primeiro exercício envolverá apenas a tabela Filmes. 
- **Table**: movies
- **Columns**: id; title; director; year; length_minutes

<details>
<summary><b>Encontre o title de cada filme</b></summary>
SELECT title FROM movies;
</details>

<details>
<summary><b>Encontre o director de cada filme</b></summary>
SELECT director FROM movies;
</details>

<details>
<summary><b>Encontre o title e director de cada filme</b></summary>
SELECT title, director FROM movies;
</details>

<details>
<summary><b>Encontre o title e year de cada filme
</b></summary>
SELECT title, year FROM movies;
</details>

<details>
<summary><b>Encontre todas as informações sobre cada filme</b></summary>
SELECT * FROM movies;
</details>