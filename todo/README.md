## Tasker (apelidado por mim)
### Aplicação para criar lembretes(tasks) 

# Backend: 

## Desafio criado utilizando node.js com typescript e banco de dados postgres
 - A aplicação é um to-do onde é possível criar tasks e deletar, além de categoriza-las

## Conceitos e tecnologias utilizadas:
- Node.js
- Typescript
- Express
- Mysql
- TypeORM
- Jest (testes)
- Tsyringe (injeção de dependencias)
- date-fns (manipulação de datas)
- Eslint - prettier - editorconfig (linting e padronização de código)
- TDD
- DDD

## Divisão dos módulos do projeto:
- Entities
- Controllers
- Rotas
- Repoitories
- Database
- Services

## Como utilizar o backend:
- baixe o repositório, abra o terminal na pasta e aplique um yarn para baixar as dependencias em sua máquina,

- Em seguida, abra o arquivo ormconfig.json e substitua as credenciais pelas credenciais do seu banco de dados mysql ou sua imagem do docker, embora o banco esteja com o nome crud, voce pode substituir e criar com o nome que desejar

- após criar o banco em sua máquina e deixar as credenciais prontas, utilize o comando yarn typeorm migration:run em seu terminal para criar as tabelas no banco de dados.

- agora para iniciar a aplicação é só utilizar o comando yarn dev:server para a aplicação rodar na porta 3333

## Testes:
- Para iniciar o jest e testar os services da aplicação(onde fica a lógica da aplicaçã), basta no terminal aplicar um yarn test e irá mostrar o resultado dos testes. Foram feitos testes unitários apenas.
- Para ter acesso ao coverage dos testes é necesário,primeiramente, realizar o passo anterior, para criar o coverage e então acessar a pasta coverage na pasta raiz do projeto, acessar a pasta Lcov-report e então abrir o index.html para ter dados sobre o coverage

# FrontEnd:
## Conceitos e tecnologias utilizadas:
- React Js
- Typescript
- Styled-components
- axios
- date-fns (manipulação de datas)
- Eslint - prettier - editorconfig (linting e padronização de código)
- @unform
- react-springs
- react-icons

## Divisão dos módulos do projeto:
- Routes
- Components
- Routes
- Pages
- Service
- utils
- style
- hooks

## Como utilizar o FrontEnd:
- baixe o repositório, abra o terminal na pasta e aplique um yarn para baixar as dependencias em sua máquina,

- agora para iniciar a aplicação é só utilizar o comando yarn start para a aplicação rodar na porta 3000

- Garanta que o backend e o banco de dados esteja rodando em sua máquina
