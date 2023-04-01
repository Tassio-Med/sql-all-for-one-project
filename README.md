# Bem-vindo ao SQL-All For One!

O objetivo deste projeto foi colocar me prática meus conhecimentos em banco de dados. Nele foram aplicados os comandos que estudei em `MySQL` e para o desnevolvimento foi utilizado o banco de dados `Northwind`.


#### As principais habilidades colocadas prática nesse projeto foram:

* **Javascript**;
* **SQL**;
* **MySQL**;

![javascript](https://img.shields.io/badge/javascript-yellow.svg?style=for-the-badge&logo=javascript&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)  ![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)  ![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=) 

<br/>

## Instalação

Para testar o projeto na sua máquina pessoal siga os seguintes passos:

1. Clone o repositório:

```sh
git@github.com:Tassio-Med/sql-all-for-one-project.git
```

2. Instale os pacotes npm:

```sh
npm install
```
<br/>

## 🗒️ Instruções para restaurar o banco de dados `Northwind`
<br/>

1. Faça o download do arquivo de backup [aqui](northwind.sql) clicando em "Raw", depois clicando com botão direito e selecionando "Salvar como" para salvar o arquivo em seu computador.
2. Abra o arquivo com algum editor de texto e selecione todo o conteúdo do arquivo usando `CTRL-A`.
3. Abra o MySQL Workbench.
4. Abra uma nova janela de query e cole dentro dela todo o conteúdo do arquivo `northwind.sql`.
5. Selecione todo o código com o atalho `CTRL-A` e depois clique no ícone de raio para executar a query.

    ![Restaurando o banco Northwind](images/restore_northwind.png)
6. Aguarde alguns segundos (espere em torno de 30 segundos antes de tentar fazer algo).
7. Clique no botão apontado na imagem a seguir para atualizar a listagem de banco de dados.

    ![Tabelas do banco Northwind](images/refresh_databases.png)
7. Verifique se o banco restaurado possui todas as seguintes tabelas:

    ![Tabelas do banco Northwind](images/northwind.png)
8. Clique com botão direito em cada tabela e selecione "Select Rows" e certifique-se que todas as tabelas possuem registros. Caso tenha alguma faltando, faça o passo a seguir. Caso contrário, pode ir para próxima seção.
9. Caso existam tabelas faltando, drope o banco de dados clicando com o botão direito em cima do banco de dados northwind e selecionando "Drop Schema" e refaça os passos novamente, dessa vez aguardando um tempo maior quando executar o script de restauração.

    ![Drop Schema](images/drop_database.png)

<br/>

## EsLint

Neste projeto foi utilizado o [ESLint](https://eslint.org/) para fazer a análise estática do código. Ajudando a garantir a qualidade do código de forma a tê-lo mais legível, de mais fácil manutenção e seguindo as boas práticas de desenvolvimento.
## Autor

- [@tassio medeiros](https://github.com/Tassio-Med)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tassiomed98) 

[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/tassio.med?igshid=ZDdkNTZiNTM=) 





É importante dar destaque que o projeto foi desenvolvido no  módulo de Back-end na [@trybe](https://github.com/betrybe).

<br><hr>
[🔼 Voltar topo](#bem-vindo-ao-sql-all-for-one)