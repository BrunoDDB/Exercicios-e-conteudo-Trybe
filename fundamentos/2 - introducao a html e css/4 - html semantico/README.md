# HTML Semântico

## Tags

<header>   : cabeçalho
<nav>      : links de navegação
<aside>    : barra lateral
<article>  : artigo 
<section>  : seção
<footer>   : rodapé
<img>      : imagem
<main>     : conteudo principal 


<body>
    <header id="header">Cabeçalho</header>
    <nav id="nav">Links de navegação</nav>
    <main id="group">
        <article id="article">
            Artigo
            <section id="section">Seção</section>
        </article>
        <aside id="aside">Barra Lateral</aside>
    </main>
    <footer id="footer">Rodapé</footer>
</body>


## Elementos de bloco e elementos inline

### Elementos block:

div, section, ul, li, header, p, etc
Ocupam 100% da largura do elemento pai
Ocupam a propria linha, sendo posicionados abaixo do elemento anterior

### Elementos inline:

a, span, b, i, etc
Ocupam a largura do proprio conteudo
Não é possivel alterar as propriedades de altura e largura
Dois ou mais elementos inline em sequencia são posicionados lado a lado
Somente é possivel alterar as margens horizontais
Ao aplicar float automaticamente se transformam em elementos block
Se comportam como texto

li {
    display: inline;     : muda o comportamento de elementos para inline
}

### Elementos inline-block:

Ocupam a largura do proprio conteúdo
Dois ou mais elementos inline-block em sequência, são posicionados lado a lado
É possivel alterar as propriedades de tamanho e largura
