# Robotron 2000 - Curso JavaScript: manipulando DOM
Repositório destinado ao curso de JavaScript DOM da Plataforma Alura.

## 01 - Java Script para Web

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

## 02 - Interagindo com uma página

Selecionar o identificador "robotron" do nosso html:
###
        const robotron = document.querySelector("#robotron")

Função declarada: ela é nomeada como "dizOi" nela um evento ouve as funções e devolvem o que a função ordena, nesse caso é dizer "Oi" e dar as boas vindas.
###
        robotron.addEventListener("click", dizOi)

        function dizOi() {
        console.log('Oi')
        console.log("Bem-vindo ao Robotron 2000")
        }
Função anônima não está sendo nomeada, mas está sendo processada pelo click no robô.
###
        robotron.addEventListener("click", function() {
        console.log('Cliquei no robô.')
        })
Função em flecha: manipula uma sequência de eventos: clique no robô > causa > "Cliquei no robô"
###
        robotron.addEventListener("click", () => {
        console.log('Cliquei no robô.')
        })

## 03 - Montando uma peça

Criar lista com todos os elementos HTML que possuem a classe .controle-ajuste:
###
        const controle = document.querySelectorAll(".controle-ajuste")

## 04 - Montando um robô

Ir na raiz do elemento do evento pelo console:
###
        evento.target.textContent

## 05 - Calculando o poder