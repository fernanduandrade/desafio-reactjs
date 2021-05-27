# SEARCH DEV
Aplicação web para pesquisar e visualizar perfis de desenvolvedores cadastrados no [github](https://github.com)

## :heart: Como rodar na sua máquina:

É necessário ter instalado o `NodeJs 14.17.0 LTS` para rodar a aplicação e baixar os pacotes necessários com o gerenciador de pacotes `npm`, você pode acessar o site oficial para baixar e instalar clicando [aqui](https://nodejs.org/pt-br/).

Após ter instalado o **NodeJs** digite os seguintes comandos para rodar em ambiente de desenvolvimento:

<li>
Primeiramente baixar as dependências, você deve estar dentro do diretório onde contém o arquivo package.json.

```sh
npm install
```
</li>

<li>
Após ter instalado as devidas dependências execute o seguinte comando para iniciar a aplicação.

```sh
npm run start
```
</li>

## :computer: Como rodar em ambiente de produção

<li>
Para ter a sua aplicação em react no ambiente de produção você deve executar o seguinte comando abaixo. 

```sh
npm run build
```

Isso irá gerar uma pasta com nome build da sua aplicação, dentro dela contém o seu index.html e uma pasta chamada static que contém todo seu javascript e css. Após isso você deverá subir essa pasta para um servidor de sua preferência.
</li>

## O que foi utilizado:

Para a aplicação eu escolhi os seguintes pacotes.

<ul>
    <li>Moment.js - Para calcular a data</li>
    <li>Styled-components - Para escrever o css</li>
    <li>FontAwesome - Para os ícones</li>
    <li>Axios - Para as requisições HTTP</li>
    <li>Framer Motion - Para animação de carregamento de tela</li>
</ul>
