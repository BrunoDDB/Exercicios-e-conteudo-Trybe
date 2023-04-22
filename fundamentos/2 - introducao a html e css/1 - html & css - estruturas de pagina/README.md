# Introdução HTML & CSS

HTML = Linguagem de marcação de texto

# Primeiras tags

## Estrutura das tags:

<nomeTag atributo="valor">
    conteúdo da tag
</nomeTag>

Começando por 2 tags principais:
<head>
<body>

<head> : não tem as informações visíveis da página, e sim as configurações da página
<body> : dentro do body vão vir todas as tags visiveis da página
        Exemplo: <h1> , <p> , etc

## Algumas tags:

<br> : quebra linha do texto (ela não precisa de fechar)

<strong>conteudo do texto</strong> : essa tag reforça o que foi escrito entre ela colocando em negrito

<em>conteudo</em> coloca em itálico mas essa tag tem um valor no html semantico

<ul></ul> : tag para criar listas não ordenadas

<ol></ol> : tag para criar listas ordenadas

<li>item da lista</li> : tag para criar os itens da lista (fica dentro de ol/ul)

<img src="caminho da imagem externo ou interno" alt="descrição da imagem" width="largura da imagem em % ou px"> : tag para carregar uma imagem


# HTML - Links externos e internos

<a href="link de referencia" target="_blank">Texto</a> : tag para criar um texto que linka com um endereço interno ou externo (a propriedade target="_blank" faz abrir a pagina em outra aba)

