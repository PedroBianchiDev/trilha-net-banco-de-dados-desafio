# DIO - Trilha .NET - Banco de Dados
www.dio.me

## Desafio de projeto
Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de banco de dados, da trilha .NET da DIO.

## Contexto
Você é responsável pelo banco de dados de um site de filmes, onde são armazenados dados sobre os filmes e seus atores. Sendo assim, foi solicitado para que você realize uma consulta no banco de dados com o objetivo de trazer alguns dados para análises.

## Proposta
Você precisará realizar 12 consultas ao banco de dados, cada uma retornando um tipo de informação.
O seu banco de dados está modelado da seguinte maneira:

![Diagrama banco de dados](Imagens/diagrama.png)

As tabelas sao descritas conforme a seguir:

**Filmes**

Tabela responsável por armazenar informações dos filmes.

**Atores**

Tabela responsável por armazenar informações dos atores.

**Generos**

Tabela responsável por armazenar os gêneros dos filmes.

**ElencoFilme**

Tabela responsável por representar um relacionamento do tipo muitos para muitos entre filmes e atores, ou seja, um ator pode trabalhar em muitos filmes, e filmes
podem ter muitos atores.

**FilmesGenero**

Tabela responsável por representar um relacionamento do tipo muitos para muitos entre filmes e gêneros, ou seja, um filme pode ter mais de um gênero, e um genêro pode fazer parte de muitos filmes.

## Preparando o banco de dados
Você deverá executar o arquivo **Script Filmes.sql** em seu banco de dados SQL Server, presente na pasta Scripts deste repositório ([ou clique aqui](Script%20Filmes.sql)). Esse script irá criar um banco chamado **Filmes**, contendo as tabelas e os dados necessários para você realizar este desafio.

## Objetivo
Você deverá criar diversas consultas, com o objetivo de retornar os dados a seguir. Abaixo de cada pedido tem o retorno esperado. O seu retorno deve ser igual ao da imagem.

## 1 - Buscar o nome e ano dos filmes

![Exercicio 1](Imagens/1.png)

## 2 - Buscar o nome e ano dos filmes, ordenados por ordem crescente pelo ano

![Exercicio 2](Imagens/2.png)

## 3 - Buscar pelo filme de volta para o futuro, trazendo o nome, ano e a duração

![Exercicio 3](Imagens/3.png)

## 4 - Buscar os filmes lançados em 1997

![Exercicio 4](Imagens/4.png)

## 5 - Buscar os filmes lançados APÓS o ano 2000

![Exercicio 5](Imagens/5.png)

## 6 - Buscar os filmes com a duracao maior que 100 e menor que 150, ordenando pela duracao em ordem crescente

![Exercicio 6](Imagens/6.png)

## 7 - Buscar a quantidade de filmes lançadas no ano, agrupando por ano, ordenando pela duracao em ordem decrescente

![Exercicio 7](Imagens/7.png)

## 8 - Buscar os Atores do gênero masculino, retornando o PrimeiroNome, UltimoNome

![Exercicio 8](Imagens/8.png)

## 9 - Buscar os Atores do gênero feminino, retornando o PrimeiroNome, UltimoNome, e ordenando pelo PrimeiroNome

![Exercicio 9](Imagens/9.png)

## 10 - Buscar o nome do filme e o gênero

![Exercicio 10](Imagens/10.png)

## 11 - Buscar o nome do filme e o gênero do tipo "Mistério"

![Exercicio 11](Imagens/11.png)

## 12 - Buscar o nome do filme e os atores, trazendo o PrimeiroNome, UltimoNome e seu Papel

![Exercicio 12](Imagens/12.png)

--------------------------------------------------------------------------------------------------------

# Respostas

## 1 
![image](https://github.com/user-attachments/assets/ecb1b35c-2580-4443-a83e-a7e5c3a92be6)

## 2
![image](https://github.com/user-attachments/assets/1e672e83-6ab4-40c4-9c58-a2d705db3fcd)

## 3
![image](https://github.com/user-attachments/assets/7ad2ae45-18ee-4060-91c8-bb15cf9e3460)

## 4
![image](https://github.com/user-attachments/assets/3f45a028-1e13-4ac7-a2a0-0a2d1cdc618e)

## 5
![image](https://github.com/user-attachments/assets/4ab8593b-dae1-4473-8004-db822e0f4520)

## 6
![image](https://github.com/user-attachments/assets/f3b91d88-5c68-4954-8c77-fbfa8c465692)

## 7
![image](https://github.com/user-attachments/assets/67667cc4-f5f1-40bc-ae13-9c7b352a0859)

## 8 
![image](https://github.com/user-attachments/assets/eccb6989-d4f7-4486-a5e6-1cc762a949de)

## 9
![image](https://github.com/user-attachments/assets/99cbbeaf-7f1f-401a-b493-e8f2a14b0432)

## 10
![image](https://github.com/user-attachments/assets/93ded4ab-408d-4e05-8681-82fdd866608e)

## 11
![image](https://github.com/user-attachments/assets/ff1498eb-f64b-43de-84c7-6481f6123032)

## 12
![image](https://github.com/user-attachments/assets/717aaad9-208e-419d-9dda-6d4ce6a7aacb)
