
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">Sobre</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="intro">
            <h1>Bem-vindo ao meu portfólio!</h1>
            <p>Sou um desenvolvedor apaixonado por tecnologia e sempre em busca de novos desafios.</p>
            <button id="alertButton">Clique para saber mais!</button>
        </section>
    </main>

    <footer>
        <p>Feito por [ Luana Fernandes ]</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre Mim</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">Sobre</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="about-me">
            <h2>Sobre Mim</h2>
            <p>Sou estudante de Ciência da Computação com paixão por JavaScript, HTML e CSS. Busco sempre aprender novas tecnologias e aprimorar minhas habilidades em desenvolvimento web.</p>
            <h3>Competências</h3>
            <ul>
                <li>JavaScript</li>
                <li>HTML/CSS</li>
                <li>Git/GitHub</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>Feito por [Seu Nome]</p>
    </footer>

</body>
</html>
/* Reset de margens e padding */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60vh;
    flex-direction: column;
    text-align: center;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}

button {
    padding: 10px 20px;
    background-color: #333;
    color: white;
    border: none;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background-color: #444;
}

.about-me {
    margin: 20px;
}

.about-me ul {
    list-style-type: none;
}

.about-me li {
    margin: 5px 0;
}
// Função simples de JavaScript
document.getElementById('alertButton').addEventListener('click', function() {
    alert("Obrigado por visitar meu portfólio!");
});
# Meu Portfólio

Este é o meu portfólio desenvolvido com HTML, CSS e JavaScript. A página apresenta informações sobre mim, meus projetos e a maneira de entrar em contato.

## Tecnologias Usadas

- HTML5
- CSS3 (Flexbox)
- JavaScript
- Git/GitHub

## Como rodar o projeto

1. Clone o repositório.
2. Abra o arquivo `index.html` em um navegador.

## Funcionalidades

- Navegação entre páginas (Home e Sobre).
- Recurso de JavaScript para exibir um alerta de boas-vindas.
- Layout responsivo com Flexbox.
- Estrutura semântica e acessível.
