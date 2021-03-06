# Chat utilizando sockets e threads

**Disciplina:** Redes de Computadores <br/>
**Docente:** Carlos Vinícius <br/>
**Discente:** Jonathan Lopes

### Descrição do projeto
Chat feito na linguagem Java, utilizando sockets, thread e banco de dados. <br/> <br/>
Esta é a tela de login com validação dos campos e validação de email e senha no banco de dados.
<img src="http://image.prntscr.com/image/eb2c813040db43a39ca97cafea297cdb.png" alt="Tela de login" /><br/>**Figura 01: Tela de login** 

Se o usuário não tiver login, ele poderá fazer seu cadastro, todos os campos são validados, a senha é convertida para MD5, os dados são enviados e salvos no banco de dados. <br/>
<img src="http://image.prntscr.com/image/04ffd20b47e14b808b7f9aa753d38e04.png" alt="Tela de cadastro" /><br/>**Figura 02: Tela de cadastro** 

O chat funciona com multithreading, vários usuários podem se conectar ao mesmo tempo e trocar mensagens.
<img src="http://image.prntscr.com/image/fb039454e3114e53bc2bfb28ba7c9585.png" alt="Tela de cadastro" /><br/>**Figura 03: Tela do chat** 

### Para rodar o projeto
1. Criar a base de dados projeto_redes (MySQL) no PC do servidor, sql está disponível na pasta ServidorBD;
2. O ServidorChat usa a porta 3333, e o ServidorBD usa a porta 4444, ambos utilizam o ip local: 127.0.0.1;
3. Executar o projeto ServidorBD e ServidorChat;
4. Executar o projeto cliente. 
<br/>Obs.: Para alterar as "portas" utilizadas ou o IP, devesse alterar diretamente no código do projeto.
