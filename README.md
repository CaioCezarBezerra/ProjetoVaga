<h1>Passo a Passo para Testar a Aplicação</h1>
<p>Este tutorial explica como configurar e testar uma aplicação que consiste em:</p>

<li>Backend: Uma API que realiza operações matemáticas (soma, subtração, multiplicação e divisão) e usa autenticação e autorização via JWT (JSON Web Tokens).</li>

<li>Frontend: Uma interface em Angular ou React para interagir com a API.</li>

<li>Docker: Utilização do Docker e Docker-Compose para rodar ambos os projetos de forma isolada e simples.</li>

<h2>Requisitos</h2>
<li>Docker e Docker-Compose instalados.</li>

<li>Node.js (para backend em Node.js) ou .NET Core (para backend em C#) ou Python com Flask/Django.</li>

<li>Angular ou React instalado.</li>

<h2>Estrutura do Projeto</h2>
<li>Backend: Uma API que implementa as operações matemáticas e autenticação JWT.</li>
<li>Frontend: Uma interface que permite ao usuário inserir valores e escolher uma operação matemática.</li>
<li>Docker: Ambos os projetos estarão configurados para rodar via Docker</li>
<h2></h2>

![image](https://github.com/user-attachments/assets/6245e111-0ba8-4e1a-9421-571d23eab957)
<h2></h2>

<h2>Rodando os Projetos com Docker-Compose</h2>
<h3>Subir o Docker Compose</h3>
<li>No diretório raiz, onde estão localizados os arquivos docker-compose.yml do frontend e backend, execute:</li>

![image](https://github.com/user-attachments/assets/07730b9d-9adf-4f44-9c40-1a5a7b5ff452)

<p>Isso irá construir e rodar ambos os containers.</p>

<h2> Testando a Aplicação</h2>
<li>Abra seu navegador e acesse <h4>http://localhost:8080/</h4></li>
<li>Na tela de login, insira o usuário e senha corretos ('user' e 'password').</li>
<li>Após o login, a aplicação deverá redirecionar para a tela de cálculo.</li>
<li>Realize as operações matemáticas e veja os resultados sendo exibidos na tela.</li>

![image](https://github.com/user-attachments/assets/b2c57e99-d357-4020-ba03-470be3c82b96)
