# Projeto Final - Módulo 4 - Pandas

## Projeto final do quarto módulo do curso de Data Science da Let's Code

### Grupo de Trabalho - Os Pythaon

[Erivan Oliveira](https://github.com/Erivan2400)

[Saul Oliveira](https://github.com/saulzera)

[Vinicius Mendes](https://github.com/vmendes93)

# Descrição do Projeto

Você fazem parte do time de Data Science e Analytics da Popolishoshop e receberam uma base de dados contendo as infromações sobre a última Black Friday que ocorreu. O time de negócio solicitou para vocês um relatório, onde especificaram algumas informações e também um estudo para que vocês respondessem utilizando as bases fornecidas.

Para esse desafio, vamos trabalhar com o data set [Black Friday](https://www.kaggle.com/sdolezel/black-friday), que reúne dados sobre transações de compras em uma loja de varejo. Esse dataset está quebrado em diferentes arquivos e é sua função entender como cada um se relaciona com o outro.

Vamos utilizá-lo para praticar a exploração utilizando pandas.

Na tabela a seguir podemos ver os nomes das colunas e as descrições dos campos:

| Coluna                 | Descrição                                                 |
|------------------------|-----------------------------------------------------------|
| User_ID                | ID do usuário                                             |
| Product_ID             | ID do produto                                             |
| Gender                 | Sexo do usuário                                           |
| Age                    | Ano em intervalos                                         |
| Occupation             | Ocupação (mascarada)                                      |
| City_Category          | Categoria da cidade (A, B, C)                             |
| StayInCurrentCityYears | Número de anos de permanência na cidade atual             |
| Marital_Status         | Estado civil                                              |
| ProductCategory1       | Categoria do produto (Mascarada)                          |
| ProductCategory2       | Categoria que o produto pode pertencer também (Mascarada) |
| ProductCategory3       | Categoria que o produto pode pertencer também (Mascarada) |
| Purchase               | Valor da compra                                           | 

Todo o código desenvolvido deve ser pensado para ser reutilizado. A avaliação se dará executando todo o notebook com outra tabela, de mesmas colunas. Sendo assim, pensem na qualidade e reprodução do código.

## _Set up_ da análise

Faça a leitura das três bases fornecidas e junte-as em um único DataFrame.


## Questão 1

Quantas observações e quantas colunas há no dataset completo (todas as bases juntas)? Responda no formato de uma tuple `(n_observacoes, n_colunas)`.

## Questão 2

Há quantas mulheres com idade entre 26 e 35 anos no dataset? Responda como um único escalar.

## Questão 3

Quantos usuários únicos há no dataset? Responda como um único escalar.

## Questão 4

Qual porcentagem dos registros (percentual de linhas) possui ao menos um valor null (`None`, `ǸaN` etc)? Responda como um único escalar entre 0 e 1.

## Questão 5

Quantos valores null existem na variável (coluna) com o maior número de null? Responda como um único escalar.

## Questão 6

Qual o valor mais frequente (sem contar nulls) em `Product_Category_3`? Responda como um único escalar.

## Questão 7

Podemos afirmar que se uma observação é null em `Product_Category_2` ela também o é em `Product_Category_3`? Responda com um bool (`True`, `False`).

## Questão 8

Qual o ID do usuário que mais gastou na Black Friday?

## Questão 9

Qual grupo (homens ou mulheres) mais gastou na Black Friday?

## Questão 10

Faça uma nova tabela com a categoria mais comprada por cada cliente.

Obs: se ele comprou um produto que possuir valores nas três colunas de categorias, então deve-se considerar todas as categorias.

## Questão 11

Normalize a coluna Purchase. A fórmula de normalização é:


<img src="https://render.githubusercontent.com/render/math?math=x = \frac{x - X_{min}}{X_{max}-X_{min}}" >

## Questão 12
O estado civil influencia no valor gasto e na categoria de produto comprada? Mostre!

Se eu quisesse vender mais produtos da categoria 14, deveria investir em propagandas para qual estado civil?

## Questão 13
Quais as variáveis que mais impactaram no valor da compra? Como você chegou a essa conclusão?
