<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projeto de Teste</title>
    <meta name="description" content="Site de teste para GitHub Pages com estrutura base extensível.">
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --background-color: #f4f6f8;
            --text-color: #333;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: Arial, Helvetica, sans-serif;
        }

        body {
            background-color: var(--background-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        header {
            background-color: var(--primary-color);
            color: #fff;
            padding: 2rem 1rem;
        }

        header h1 {
            margin-bottom: 0.5rem;
        }

        header p {
            max-width: 700px;
        }

        nav {
            background-color: #1f2d3a;
            padding: 0.75rem 1rem;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 1.5rem;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        main {
            max-width: 1100px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        section {
            margin-bottom: 3rem;
        }

        section h2 {
            margin-bottom: 1rem;
            color: var(--primary-color);
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }

        .card {
            background: #fff;
            border-radius: 6px;
            overflow: hidden;
            box-shadow: 0 2px 6px rgba(0,0,0,0.08);
        }

        .card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .card-content {
            padding: 1rem;
        }

        .card-content h3 {
            margin-bottom: 0.5rem;
        }

        footer {
            background-color: var(--primary-color);
            color: #fff;
            text-align: center;
            padding: 1.5rem 1rem;
            margin-top: 3rem;
        }

        footer p {
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

<header>
    <h1>Projeto de Teste</h1>
    <p>
        Este site serve como base para testes em GitHub Pages. A estrutura é simples,
        modular e pensada para crescer com novas secções, páginas e funcionalidades.
    </p>
</header>

<nav>
    <ul>
        <li><a href="#">Início</a></li>
        <li><a href="#">Sobre</a></li>
        <li><a href="#">Projetos</a></li>
        <li><a href="#">Contacto</a></li>
    </ul>
</nav>

<main>

    <section>
        <h2>Sobre o Projeto</h2>
        <p>
            Este é um texto genérico introdutório. Pode ser utilizado para descrever
            o objetivo do site, o contexto do projeto ou qualquer outra informação relevante.
            A ideia é servir como placeholder até existir conteúdo definitivo.
        </p>
    </section>

    <section>
        <h2>Conteúdo em Destaque</h2>
        <div class="grid">
            <div class="card">
                <img src="https://picsum.photos/600/400?random=1" alt="Imagem genérica">
                <div class="card-content">
                    <h3>Secção Exemplo 1</h3>
                    <p>
                        Texto de exemplo para demonstrar como poderá ser apresentado
                        conteúdo estruturado em cartões.
                    </p>
                </div>
            </div>

            <div class="card">
                <img src="https://picsum.photos/600/400?random=2" alt="Imagem genérica">
                <div class="card-content">
                    <h3>Secção Exemplo 2</h3>
                    <p>
                        Esta área pode ser facilmente adaptada para projetos, artigos,
                        serviços ou outro tipo de informação.
                    </p>
                </div>
            </div>

            <div class="card">
                <img src="https://picsum.photos/600/400?random=3" alt="Imagem genérica">
                <div class="card-content">
                    <h3>Secção Exemplo 3</h3>
                    <p>
                        O layout é responsivo e ajusta-se automaticamente a diferentes
                        tamanhos de ecrã.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section>
        <h2>Próximos Passos</h2>
        <p>
            Algumas ideias para expansão futura:
        </p>
        <ul>
            <li>Separar o CSS para um ficheiro externo</li>
            <li>Adicionar múltiplas páginas HTML</li>
            <li>Integrar JavaScript para interatividade</li>
            <li>Substituir imagens placeholder por conteúdo real</li>
        </ul>
    </section>

</main>

<footer>
    <p>
        © 2026 - Projeto de Teste | GitHub Pages
    </p>
</footer>

</body>
</html>
