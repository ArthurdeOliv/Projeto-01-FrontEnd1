# Projeto 1 – Página de Filme

Arthur de Oliveira  
Curso: Análise e Desenvolvimento de Sistemas  
Disciplina: Programação Frontend I

## Sobre o Projeto

O filme que eu escolhi foi **Interestelar**, um filme de ficção científica que fala sobre exploração espacial, relatividade do tempo e a sobrevivência da humanidade. Achei interessante porque dá pra usar bastante conteúdo visual e texto, o que ajudou a praticar vários recursos de HTML e CSS.

O projeto tem três páginas:

- index.html` — página principal com informações gerais do filme
- elenco.html` — página com o elenco e a equipe de produção
- extras.html` — página com prêmios, cenários marcantes e curiosidades

Recursos de HTML usados

    Estrutura básica (<!DOCTYPE html>, <html>, <head>, <body>)  
    Aparece logo no começo de todos os arquivos .html.

    Tags de mídia (<audio>, <video>, <img>)

        index.html, linha 7: <audio autoplay hidden loop> para tocar a trilha sonora.

        index.html, linha 54: <video controls> para o trailer.

        elenco.html, várias linhas dentro das <div class="card"> com <img> para fotos dos atores.

    Navegação (<nav>, <ul>, <li>, <a>)  
    Em todos os arquivos HTML, dentro do <header>. Exemplo: index.html, linha 12.

    Seções (<section>)  
    Usadas para organizar conteúdo em blocos. Exemplo: extras.html, linha 21 para a seção de prêmios.

    Textos e títulos (<h1>, <h2>, <h3>, <p>)  
    Espalhados por todo o projeto. Exemplo: elenco.html, linha 23: <h1>INTERSTELAR <span>Elenco e Equipe</span></h1>.

    Links externos (<a href="...">)  
    index.html, linha 41: link para Prime Video e HBO Max.

# Recursos de HTML usados

    Estrutura básica (<!DOCTYPE html>, <html>, <head>, <body>)  
    Aparece logo no começo de todos os arquivos .html.

    Tags de mídia (<audio>, <video>, <img>)

        index.html, linha 7: <audio autoplay hidden loop> para tocar a musica tema.

        index.html, linha 54: <video controls> para o trailer.

        elenco.html, várias linhas dentro das <div class="card"> com <img> para fotos dos atores.

    Navegação (<nav>, <ul>, <li>, <a>)  
    Em todos os arquivos HTML, dentro do <header>. Exemplo: index.html, linha 12.

    Seções (<section>)  
    Usadas para organizar conteúdo em blocos. Exemplo: extras.html, linha 21 para a seção de prêmios.

    Textos e títulos (<h1>, <h2>, <h3>, <p>)  
    Espalhados por todo o projeto. Exemplo: elenco.html, linha 23: <h1>INTERSTELAR <span>Elenco e Equipe</span></h1>.

    Links externos (<a href="...">)  
    index.html, linha 41: link para Prime Video e HBO Max.

# Recursos de CSS usados

    Fonte e cores básicas

        styles.css, linha 1: font-family: 'Arial', sans-serif;

        styles.css, linha 2: color: #fff; background-color: #000;

    Navbar fixa

        styles.css, linha 7: .navbar { position: fixed; top: 0; width: 100%; }

    Hero section com imagem de fundo

        styles.css, linha 20: .hero { background: url('/imagens/interestellar.jpg') no-repeat center center/cover; }

    Grid layout

        styles.css, linha 70: .conteudo { display: grid; grid-template-columns: 1fr 1fr 1fr; } usado para organizar logos, trailer e frase.

    Flexbox

        styles.css, linha 13: .navbar ul { display: flex; justify-content: center; gap: 30px; } também em .trailer, .logos, .cards-grid.

    Cards com imagens e textos

        styles.css, linha 160: .card { width: 170px; }

        styles.css, linha 165: .card img { border-radius: 8px; object-fit: cover; }

    Responsividade com media queries

        styles.css, linha 270: @media (max-width: 900px) ajusta navbar, hero e trailer para telas menores. Também tem breakpoints em 768px e 600px.

    Efeitos visuais

        styles.css, linha 190: .cenario-card { box-shadow: 0 1px 4px rgba(0,0,0,0.08); border-radius: 8px; } dá um efeito de cartão com sombra.
