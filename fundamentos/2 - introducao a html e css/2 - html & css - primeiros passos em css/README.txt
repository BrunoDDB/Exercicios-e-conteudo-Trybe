# Primeiros passos em CSS

## Introdução ao CSS

<style></style> : essa tag é colocada dentro do <head> e tudo dentro de <style> vai estilizar meu site

<head>
    <style>
        h2 {
            color: green;     : cria uma estilização para todas as tags h2 mudando a cor delas para verde
        }

        body {
            background-color: red;       : muda a cor de fundo do site para vermelho
        }

        #nome-id {
            background-color: red;       :estiliza um item através do seu id, no caso foi mudar a cor de fundo de um paragrafo
        }

        .nome-da-classe {
            background-color: blue;     : estiliza todos os itens que tiverem a classe "nome-da-classe"
        }

    </style>
</head>
<body>

    <p id="nome-id¨>Conteudo do paragrafo</p>
    <br>
    <h2 class="nome-da-classe">Conteudo do h2</h2>

</body>

## Propriedades de Texto no CSS

p {
    font-family: fantasy, sans-serif;  : modifica a fonte de texto de todos os paragrafos para o estilo fantasy, caso meu computador não tiver a fonte fantazy
}                                        ele vai colocar a fonte reserva que é a sans-serif 

.classe-qualquer {
    font-size: 20px;            : aumentou o tamanho da fonte em 20 pixels
}

h2 {
    font-size: 2em:     : aumentou o tamanho da fonte 2 vezes mais do que o padrão no body
}

#id-qualquer {
    font-weight: bold;     :as palavras com o id "id-qualquer" vão estar em negrito
    font-style: italic;    : as palavras com o id "id-qualquer" vão estar em italico
}

.classe-teste {
    line-height: 40px;     : vai ter um espaçamento entre as linhas de 40 pixels
    text-align: center;    : vai alinhar o texto no centro
}


## CSS inline e externo

_ Criar um arquivo style.css
_ crie um link entre o arquivo style.css e nosso arquivo html:

    <head>
        <link rel="stylesheet" type="texto/css" href="style.css">     : cria um link entre o arquivo style.css e o arquivo html (href é o endereço)
    </head>