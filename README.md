<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./styles.css">
    <title>teste HTML e CSS</title>
</head>
<body>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Meu Site</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      scroll-behavior: smooth;
    }

    nav {
      background-color: #333;
      padding: 10px;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 1000;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      color: #ffcc00;
    }

    section {
      padding: 100px 20px;
      margin-top: 60px;
      height: 100vh;
    }

    #inicio { background: #f2f2f2; }
    #sobre  { background: #e0f7fa; }
    #projetos { background: #fff3e0; }
    #contato { background: #fce4ec; }
  </style>
</head>
<body>

  <nav>
    <a href="#inicio">Início</a>
    <a href="#sobre">Sobre</a>
    <a href="#projetos">Projetos</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="inicio">
    <h1>Bem-vindo!</h1>
    <p>Essa é a seção de início.</p>
  </section>

  <section id="sobre">
    <h1>Sobre mim</h1>
    <p>Algumas informações sobre você.</p>
  </section>

  <section id="projetos">
    <h1>Meus Projetos</h1>
    <p>Aqui você mostra os seus projetos.</p>
  </section>

  <section id="contato">
    <h1>Contato</h1>
    <p>Como as pessoas podem falar com você.</p>
  </section>

</body>
</html>

 <!-- aqui -->
<div>
    <h1>TABLE</h1>
    <table>
        <caption>uma descrição para a table </caption>
        <thead>
            <tr>
                <th>NADA</th>
                <th>NADA</th>
                <th>NADA</th>
               
            </tr>
        </thead> 

        <tbody>
            <tr>
                <td> class-colspan="1"</td>
                <td>serve para deixar um espaço entre a table</td>
                <td>"1" esse serve para quandos espaços vai ter</td>
            </tr>

            <tr>
                <td>tr cria a "table"</td>
                <td>th cria o titulo da table</td>
                <td>td cria o "texto"</td>
            </tr>

            <tr>
                <td>thead é a cabeça da tabela</td>
                <td>tbody é o corpo da tabela</td> @@101122008
                <td>tfoot é o pé da tabela</td>
            </tr>
            <tr>
                <td>justify-content: space-between</td>
                <td>deixa o texto à esquerda e a imagem à direita, com espaço entre eles.</td>
                <td>NADA</td>
            </tr>
        <tfoot>
            <tr>
                <td>matheus1012@gmail <span>senha=cruz_1012</span></td>
                <td>meliodas911@gmail <span>senha=matheus_1012</span></td>
                <td>ferreira302@gmail <span>senha=@@10122008</span></td>
                <td>GitHubUsuario=matheus101208<span>senha=ferreira_1012</span></td>
            </tr>
        </tfoot>
        
    </table>
</div>

<img src="./ima/download.jpg" alt="">

<h1>teste</h1>

  <form onsubmit="enviarFormulario(e)">
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome" required>

        <label for="email">E-mail:</label>
        <input type="email" id="email" name="email" required>

        <label for="mensagem">Mensagem:</label>
        <textarea id="mensagem" name="mensagem" rows="4" required></textarea>

        <button type="submit">Enviar</button>
    </form>

<a href="https://meusite.com" class="meu-link">Visite meu site</a>



