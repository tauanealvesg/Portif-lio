# Portif-lio
Primeira Parte do Código - index.html

Index.html 
   Esse site é o meu portfólio, ele foi dividido em três páginas: Sobre Mim, Hobbies e Interesses e Formulário, o site tem como objetivo falar um pouco sobre quem eu sou, usando o básico do HTML e CSS, a intenção do site é ser bem simples e intuitivo, eu dividi os códigos por index.html (a página principal), index.css (a parte de estilização das páginas), hobbieseinteresse.html (segunda página) e formulario.html (terceira página).


<!DOCTYPE html>
<html lang="pt-br">
	<head>
   	<meta charset="utf-8">
   	<meta http-equiv="X-UA-Compatible" content="IE=edge">
   	<meta name="viewport" content="width=device-width, initial-scale=1.0">
   	<title>Coisa & Tau</title>
   	<link rel="stylesheet" href="index.css">
<!-- É necessário colocar href indexcss para estilizar o site. -->
<!-- É necessário referenciar todas as três páginas para isso se abre o ''a'' e coloca href. -->
 
 
</head>
<body>
	<div class="container">
        <nav>
    	<ul>
     	<li>
       	<a href="index.html"> Sobre Mim </a>
    	</li>
    	<li>
       	<a href="hobbieseinteresses.html"> Hobbies e Interesses</a>
     	<li>
       	<a href="formulario.html"> Formulário</a>
    
         </li>
   	</ul>
 	</nav>
 	<header>
   	<div class="center">
       	<img src="./img/Tauane.png"></img>
       </div>
   	<h1>Tauane Alves</h1>
       <h2>Full Stack Jr.</h2>
<!-- Essa é a primeira parte e contém referências às outras duas páginas para poder enviar para o CSS. -->
<!-- os subtítulos das outras páginas estão no ‘’a href’’ e vão ficar no topo da página. -->
 
 
 	</header>
 	<main>
   	<section>
       	<h3>Sobre Mim</h3>
       	<p>Meu nome é Tauane, tenho 24 anos, moro na Vila da Penha sou graduanda em Defesa e Gestão e Estratégica  Internacional (UFRJ), atualmente estudo programação, inglês e espanhol. Na faculdade, participei do projeto de extensão: Alunos Contadores de Histórias, no qual alunos da UFRJ contam histórias para crianças em situação de internação e cuidados diários no hospital infantil. Outro projeto de extensão na qual fiz parte é o Ubuntu_Labe, tem como objetivo desenvolver cidades inteligentes, eu e a minha dupla desenvolvemos um escopo
       	de aplicativo para denuncia de assédios em transportes públicos do Rio de Janeiro, o nome do aplicativo é ANAS - RJ.
           Essa é um pouco da minhas história, obrigada por ter lido até aqui e continue se você quer saber mais sobre meus hobbies e interesses.</p>
       </section>
 
 	</main>
 	<footer>
    	<a href="https://github.com/tauanealvesg" target="_blank" rel="noopener noreferrer">
        	<img src="./img/github.svg"></img>
    	<p>GitHub</p>
	</a>
   
    <a href="https://www.linkedin.com/in/tauanealvesg" target="_blank" rel="noopener noreferrer">
    	<img src="./img/linkedin.svg"></img>
	<p>Linkedin</p> </a>
 	</footer>
    </div>
   
 </body>
</html>


Segunda Parte do Projeto - hobbies.html

hobbieseinteresses.html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="index.css">

</head>
</html>
</head>
<body>
<!-- Foi necessário separar por div class= container e novamente referenciar as outras páginas. -->
<!-- Eu repeti a minha foto como forma de deixar as páginas padronizadas. -->


    <div class="container">
<nav>
        <ul>
         <li>
           <a href="index.html"> Sobre Mim </a>
        </li>
        <li>
           <a href="hobbieseinteresses.html"> Hobbies e Interesses</a>
         <li>
           <a href="formulario.html"> Formulário</a>
     
         </li>
       </ul>
     </nav>
     <header>
       <div class="center">
           <img src="./img/Tauane.png"></img>
       </div>
       <h1>Hobbies e Interesses</h1>
       <h2>Eu sou uma pessoa bastante curiosa e que gosta de desafios, por isso eu estou fazendo inglês, espanhol e o 
curso de programação porque os três cursos me tiram da zona de conforto. Como uma boa flamenguista, eu adoro 
assistir os jogos do meu time, porém evito assistir jogos decisivos. Gosto de passar o meu tempo livre
assisindo séries, filmes, ouvindo músicas ou lendo livros.</h2>
<!-- Não consegui colocar os hobbies em forma de lista. -->
<!-- Não acho que tenha interferido muito no entendimento e estética da página. -->


<ul>
    <li>Eu gosto de ler;</li>
    <li>Aprender novos idiomas;</li>
    <li>Assistir séries;</li>
    <li>Assistir filmes;</li>
  </ul>

     </header>

    
      
     </div>
 
 

</body>
</html>




Terceira Parte - formulario.html

Formulario.html


<!DOCTYPE html>
<html lang="pt-br">
    <head>
       <meta charset="utf-8">
       <meta http-equiv="X-UA-Compatible" content="IE=edge">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Formulario</title>
       <link rel="stylesheet" href="index.css">
</head>
<body>
    <div class="container">
<nav>
        <ul>
         <li>
           <a href="index.html"> Sobre Mim </a>
        </li>
        <li>
           <a href="hobbieseinteresses.html"> Hobbies e Interesses</a>
         <li>
           <a href="formulario.html"> Formulário</a>
     
         </li>
       </ul>
     </nav>
     <header>
       <div class="center">
           <img src="./img/Tauane.png"></img>
       </div>
       <h1>Formulário</h1>
       <h2>Se você assim como eu quer praticar a conversação em inglês e/ ou espanhol 
é só preencher o formulário abaixo!<h2/></h2>
<!-- Coloquei uma frase antes do formulário para identificar sua funcionalidade. -->
<!-- O formulário está ativado, eu sei que não precisava. -->


     </header>

    
      <form class="contact-form" action="https://formsubmit.co/contatotauane@gmail.com" method="POST">
      <label for="email">E-mail</label>
      <input type="email" name="email" id="email" required>
      <label for="message">Mensagem</label>
      <input type="text" name="message" id="message" required>
      <button type="submit">Send</button> 
     </div>
 
 

</body>
</html>



Quarta Parte - index.css

Index.css

body{
    color: white; 
    background-color: sienna;
    font-family: Arial, Helvetica, sans-serif;
/* Aqui eu estilizar a cor da fonte dos textos e o background do site */ 
  }
  
  ul{
    display:flex;
    justify-content: space-around;
    list-style-type: none;
    align-items: center;
    padding: 16px;
  }
  
  a{
    color: white; 
    text-decoration: none; 
  }
/* a parte principal do site se encontra nessa seção */
  header img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 5px solid yellow;
  }
  .center {text-align: center;}

  h1 {
    color: yellow;
  }

  .container {
    padding: 0px 50px;
  }

  nav a:hover {
    color: yellow;
  }
/* a estilização dos icons das redes sociais precisou ser distinguida da foto principal */
  footer img {
    width: 40px;
    height: 40px;
  }

  footer {
    display: flexbox;
    justify-content: center;
  }

  footer a {
    margin-top: 10px;
  }

  footer p {
    margin-top: 20px;
  }

  nav a:hover {
    color: yellow;
}

.contact-form input {
    width:100%; 
    padding: 8px 0px;
    margin: 8px 0px;
}
/* especificando que era para modificar o formulário da página ‘’formulário’’ */
.contact-form input[type=text] {
height: 100px;
}
/* não mudei a borda do botão para deixar ele padronizado */
.contact-form button {
background-color: white;
border: none;
width: 100px;
height: 30px;

}

