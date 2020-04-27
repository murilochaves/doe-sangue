<h1 align="center">
	<img alt="Imagem de DOE" src="./src/frontend/public/logo.png" width="150px" />
</h1>

<h3 align="center">
	Um sistema minimalista para cadastrar doadores de sangue.
</h3>

<p align="center">
	Projeto <b>D<span style="color: #ff0000">O</span>E Sangue</b> desenvolvido durante a 3ª ed. da MaratonaDev da Rocketseat 🎓
</p>

<p align="center">
	<img alt="GitHub complete" src="https://img.shields.io/badge/MaratonaDev-done-green?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAALVBMVEVHcExxWsF0XMJzXMJxWcFsUsD///9jRrzY0u6Xh9Gsn9n39fyMecy0qd2bjNJWBT0WAAAABHRSTlMA2Do606wF2QAAAGlJREFUGJVdj1cWwCAIBLEsRU3uf9xobDH8+GZwUYi8i6ucJwrxKE+7D0G9Q4vlYqtmCSjndr4CgCgzlyFgfKfKCVO0LrPKjmiqMxGXkJwNnXskqWG+1oSM+BSwD8f29YLNjvx/OQrn+g99oQSoNmt3PgAAAABJRU5ErkJggg==">
	</img>
	<img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
	</img>
</p>

<p align="center">
	<a href="#rocket-instalação">Instalação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
	<a href="#produção">Produção</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
	<a href="#execução">Execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
	<a href="#memo-licença">Licença</a>
</p>

## :rocket: Instalação

1. Faça a instalação do editor de código [VS Code](https://code.visualstudio.com);
2. Utilize o [Google Chrome](https://www.google.com/intl/pt-BR/chrome/) com as ferramentas de inspeção de código web;
3. Instale o [Node.js](https://nodejs.org/en/);
4. Instale o [PostgreSQL](https://www.postgresql.org/);
5. Instale o [Postbird](https://www.electronjs.org/apps/postbird).

## Produção

1. Entre na pasta do projeto com `cd doesangue`;
2. Rode o comando `npm init -y`;
3. Instale todas as dependências;
4. Configure o arquivo `server.js`: <br/>
4.1 Ligue o servidor e permita o acesso à alguma porta (3000) `server.listen`; <br/>
4.2 Configure a apresentação da página, <br/>
4.3 Configure a template engine, <br/>
4.4 Configure o servidor para apresentar os arquivos estáticos, <br/>
4.5 Configure o banco de dados.

### Dependências

* `express` (framework para o node.js);
* `nodemon` (realiza auto-restart da aplicação ao salvar um arquivo modificado);
* `nunjucks` (template engine que permite manipular os conteúdos html de maneira mais fácil, intuitiva e dinâmica);
* `pg` (permite conexão com o banco de dados)

## Execução

1. Faça o clone do repositório;
2. Instale as dependências do projeto `npm install`;
3. Rode o servidor com `npm start` ou `nodemon server.js`.

### Tecnologias

* `HTML` (estrutura);
* `CSS` (estilo);
* `JavaScript` (inteligência);
* `Node.js` (sevidor, motor de JavaScript);
* `PostgreSQL` (banco de dados).

### Apresentação

<p align="justify">
	Você sabia que uma simples doação de sangue pode salvar até 3 vidas?
	<br/><br/>
	No cenário brasileiro, a doação de sangue não se é uma prática tão corriqueira, apesar de sempre estarmos cientes que a doação de sangue é importante e, vermos várias campanhas, apenas <b>1.9</b>% da população brasileira realiza a doação de sangue constantemente. Todos os dias são necessárias mais de <b>38.000</b> doações para que atenda a demanda dos hemocentros. Sendo assim, este projeto visa proporcionar o alcançe à mais pessoas por ser disponível na web e, maior facilidade para encontrar os tipos sanguíneos podendo entrar em contato com a pessoa via e-mail quando necessitar de doações de um determinado tipo.
	<br/><br/>
	<b>P.S.</b>: <i>Esta aplicação foi criada à partir da 3ª MaratonaDev disponibilizada pela Rocketseat, um evento on-line ministrado por <a href="https://github.com/maykbrito">Mayk Brito</a> entre os dias 17/02/2020 à 19/02/2020</i>.
<p>

### Interface

<h1 align="center">
	<img alt="Interface Visual" src="./src/frontend/public/interface.png" />
</h1>

### Extensões

* `Live Server`: Ritwick Dey - permite atualização automática da conteúdo da página `HTML`.

### Sites

* [CSS-Tricks](https://css-tricks.com);
* [Google Fonts](https://fonts.google.com/);
* [Imgur](https://imgur.com/).

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.