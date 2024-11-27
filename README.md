<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biblioteca Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #eef;
        }
        header {
            background-color: #003366;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        nav {
            background-color: #0055cc;
            padding: 1rem;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 1rem;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 1rem;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .search-bar {
            text-align: center;
            margin-bottom: 2rem;
        }
        .search-bar input[type="text"] {
            padding: 0.5rem;
            width: 300px;
            margin-right: 0.5rem;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .search-bar input[type="submit"] {
            padding: 0.5rem 1rem;
            background-color: #003366;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .book-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .book {
            border: 1px solid #ddd;
            margin: 1rem;
            padding: 1rem;
            width: 200px;
            text-align: center;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>Biblioteca Online</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Início</a></li>
            <li><a href="#">Livros</a></li>
            <li><a href="#">Autores</a></li>
            <li><a href="#">Gêneros</a></li>
            <li><a href="#">Contato</a></li>
        </ul>
    </nav>
    <div class="container">
        <div class="search-bar">
            <input type="text" placeholder="Buscar livros..." />
            <input type="submit" value="Buscar" />
        </div>
        <h2>Livros Disponíveis</h2>
        <div class="book-list">
            <div class="book">
                <h3>Título do Livro 1</h3>
                <p>Autor: Autor 1</p>
                <p>Descrição breve do livro.</p>
            </div>
            <div class="book">
                <h3>Título do Livro 2</h3>
                <p>Autor: Autor 2</p>
                <p>Descrição breve do livro.</p>
            </div>
            <!-- Adicione mais livros aqui -->
        </div>
    </div>
</body>
</html>
