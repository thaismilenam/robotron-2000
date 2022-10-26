# Robotron 2000 - Curso JavaScript: manipulando DOM
Repositório destinado ao curso de JavaScript DOM da Plataforma Alura.

## Java Script para Web

Selecionar um elemento pelo ID
###
        document.getElementByID(id)

Selecionar um elemento pelo nome
###
        document.getElementsByTagName(name) 

Selecionar um elemento pelo nome da classe
###
        document.getElementsByClassName(name)

Procurar elemento, sem dizer se é classe ou id, definida no html:

###
        document.querySelector()

"#" para procurar id
"." para procurar class

###
        document.querySelector('#producao')

Esta propriedade obtém ou altera qualquer elemento no HTML, inclusive tags.
###
        element.innerHTML 
Esta propriedade permite inserir textos no HTML.
###
        element.innerText
Esta propriedade altera o valor de um elemento HTML
###
        element.attribute 

Este método altera o valor de um atributo de um elemento HTML.
###
        element.setAttribute(atributo, valor)