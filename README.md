<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AluraBooks</title>
    <style>
        body {
            background-color: #000;
            color: #fff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #1a1a1a;
            padding: 10px 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        .container {
            padding: 20px;
        }

        .search-bar {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: none;
            border-radius: 5px;
            background-color: #333;
            color: #fff;
        }

        .categories {
            margin-bottom: 20px;
        }

        .categories h2 {
            margin-bottom: 10px;
        }

        .categories ul {
            list-style: none;
            padding: 0;
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
        }

        .categories li {
            background-color: #333;
            padding: 10px 15px;
            border-radius: 5px;
        }

        .book-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
        }

        .book {
            background-color: #333;
            padding: 10px;
            border-radius: 10px;
            text-align: center;
        }

        .book img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }

        footer {
            background-color: #1a1a1a;
            padding: 10px 20px;
            text-align: center;
            margin-top: 20px;
        }

        /* Estilos responsivos */
        @media (min-width: 600px) {
            .book-grid {
                grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            }

            .categories ul {
                gap: 20px;
            }

            .categories li {
                padding: 15px 20px;
            }

            .search-bar {
                padding: 15px;
            }

            .container {
                padding: 40px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>AluraBooks</h1>
    </header>
    <div class="container">
        <input type="text" class="search-bar" placeholder="Pesquisar livros...">
        <div class="categories">
            <h2>Categorias</h2>
            <ul>
                <li>Ficção</li>
                <li>Não-Ficção</li>
                <li>Romance</li>
                <li>Fantasia</li>
                <li>Ciência</li>
                <li>História</li>
                <!-- Adicione mais categorias conforme necessário -->
            </ul>
        </div>
        <div class="book-grid">
            <div class="book">
                <img src="capa-do-livro1.jpg" alt="Livro 1">
                <p>Livro 1</p>
            </div>
            <div class="book">
                <img src="capa-do-livro2.jpg" alt="Livro 2">
                <p>Livro 2</p>
            </div>
            <div class="book">
                <img src="capa-do-livro3.jpg" alt="Livro 3">
                <p>Livro 3</p>
            </div>
            <!-- Adicione mais livros conforme necessário -->
        </div>
    </div>
    <footer>
        <p>&copy; 2024 AluraBooks. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
