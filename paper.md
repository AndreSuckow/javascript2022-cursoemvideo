# CADERNO DO CURSO

## MÓDULO A - AULA 1 - O que javascript é capaz de fazer?

- o que javascript é capaz de fazer;
- dicas de aprendizagem;
- JS versus ECMAscript;
- requisitos de software;
- primeiros scripts em js;

dicas para aprender:
- não pule; ok
- anote tudo; ok
- duas telas; ok


## MÓDULO A - AULA 2 - Como chegamos até aqui?

Q01. Sabe a diferença entre um cliente e um servidor para Internet?

⋅⋅⋅ client side: tecnologias front-end que fazem requisições para acessar/baixar,etc o conteúdo que está armazenado em algum servidor.
⋅⋅⋅ server side: tecnologias back-end que armazenam o conteúdo que o cliente quer acessar.


Q02. HTML/CSS/JS - para que servem, como funcionam?

⋅⋅⋅ HTML: linguagem de marcação de texto, cria o esqueleto do que vai ser colocado no conteúdo da página da internet.
⋅⋅⋅ CSS: linguagem que coloca cores, modifica posicionamento de elementos, define tamanho de letras, imagens, ícones, etc. Tudo que é estilo, o css alcança.
⋅⋅⋅ JS: se seu site está interativo, como cliques executando funcionalidades, é muito provável que o site esteja rodando javascript do lado clientside.


Q03. Sites grandes que utilizam Javascript em seu site?

⋅⋅⋅ Google;
⋅⋅⋅ Youtube;
⋅⋅⋅ LinkedIn;


### Conteúdo da aula:

1. 1970 - meados de 1970 (criação da internet)
2. Criação da Darpa - No auge da guerra fria, os estados unidos criaram a DARPA (Defense Advanced Research Projects Agency) "Agência de Projetos de Pesquisa Avançada de Defesa" criou uma
rede chamada de Arpanet

Governo e militares e Universidades dos estados unidos estavam presentes no desenvolvimento da Arpanet.
A rede cresceu muito e precisou de diversas atualizações e veio a chamar de Internet.

3. 1993 - Timothy berners lee cria uma nova tecnologia, um divisor de águas... linguagem HTML, protoco HTTP, fundação da world wide web "www" (trabalham no cern).
para que isso fosse usado, era necessário um navegador. então foi criado Mosaic 
"A versão 1.0 do Mosaic foi lançada em setembro de 1993 por Marc Andreesen, o líder do projeto. Criado por Tim Berners-Lee, o WorldWideWeb foi o primeiro navegador da web."


## MÓDULO A - AULA 3 - Dando os primeiros passos

Métodos de aprendizagem:

Livros:

1. Javascript o guia definitivo (rinoceronte na capa)

acesse: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript
acesse: https://262.ecma-international.org/6.0/ (ECMA SCRIPT 6.0 DO ANO DE 2015)


## MÓDULO A - AULA 4 - Criando o seu primeiro script

    window.alert('Minha primeira mensagem')
    window.confirm('está gostando de javascript?')
    window.prompt('qual é o seu nome?')


# O que aprenderemos no módulo B?
--> Armazenamento de dados
--> Tratamento de dados
--> Operações com estes dados (aritmédica, lógica, relacional...)


## MÓDULO B - AULA 5 - Variáveis e tipos primitivos

Q01. Já sabe organizar suas pastas no VSCode?
r: sim

Q02. O Node.js está instalado no seu computador?
r: sim

Q03. Sabe diferenciar HTML5, CSS3 E JS dentro de um código?
r: sim

Q04. Sabe disparar alertas, confirmações e perguntas?
r: sim
```javascript
window.alert('Cuidado')
window.confirm('Você está gostando da aula?')
window.prompt('Qual o nome do seu cachorro?')
```

Explicando como comentar códigos:

```javascript
// comenta o código em uma única linha
 
/*
    comenta o código
    várias linhas
    ao mesmo tempo
*/
```
Explicando como guardar dados:
```javascript
var vaga1 = carro1 // (vaga 1 recebe carro1)
var vaga2 = carro2 // (vaga 2 recebe carro2)
var vaga3 = carro3 // (vaga 3 recebe carro3)
var vaga4 = null // (vaga vazia, sem nenhum carro preenchendo)
```

## DICIONÁRIO JS ##
ATRIBUIÇÃO: Armazenar determinado dado em determinada variável.
IDENTIFICADOR: Nome dado a variável.

Regras para atribuir um identificador à uma variável:
- Podem começar com letra, $ ou _;
- não podem começar com números;
- é possível usar letras ou números;
- é possível usar acentos e símbolos;
- não podem conter espaços;
- não podem ser palavras reservadas (exemplo: var, let, const).

Mostrando como abrir o node.js no terminal do vsc:

- Abra um terminal, digite apenas "node" e dê enter.

Dicas de criação de nome de variáveis:

- Maiúsculas e minúsculas fazem diferença;
- tente escolher nomes coerentes para identifar uma variável;
- evite se tornar um 'programador alfabeto' ou 'programador contador' (variáveis A,B,C,D,E,F,G,H)


variáveis servem para guardar dados.
```javascript
var numero1 = 5 // tipo Number (inteiro)
var numero2 = 18 // tipo Number (inteiro)
var numero3 = -12 // tipo Number (inteiro)
var numero4 = 0.5 // tipo Number (float)
var numero5 = -15.9 // tipo Number (float)
var numero6 = 3.14 // tipo Number (float)
var numero7 = 8.0 // tipo Number (float)

var ehVerdade = true // tipo Boolean (verdadeiro ou falso)
var ehMentira = false // tipo Boolean (verdadeiro ou falso)

var empresa = "Google" // tipo String
var linguagemProgramacao = 'JavaScript' // tipo String
var nomeUsuario = `Maria` // tipo String
```
Tipos de dado (Data Types):

- number;
    - Infinity;
    - NaN;
- string;
- boolean;
- null;
- undefined;
- object;
    -   Array;
- function;

Abrindo o NodeJS no terminal (para limpar os comandos CTRL + L )

```node.js
> var numero = 200
undefined
> numero
200
> typeof numero
'number'
> typeof 10
'number'
> typeof 10.5
'number'
> typeof "10.5"
'string'
> typeof []
'object'
> typeof function(){}
'function'
> typeof undefined
'undefined'
> typeof NaN
'number'
> typeof Infinity
'number'
> typeof null
'object'
>
```


## MÓDULO B - AULA 6 - Tratamento de dados

Q01. O que é uma variável?
r: variável é um espaço ou memória alocada para armazenar algum tipo de dado.

Q02. Como declarar uma variável numérica inteira ou real usando JS.
r: 
```node.js
> var numInt = 10
undefined
> var numFloat = 10.5
undefined
> numInt
10
> numFloat
10.5
> typeof numInt
'number'
> typeof numFloat
'number'
> var resultado = numInt + numFloat
undefined
> resultado
20.5
```

Q03. Quais são os tipos primitivos do JS?
r: 
String.
Number.
Boolean.
Null.
undefined.
Symbol (novo no ECMAScript (en-US) 6)

Q04. O que significa colocar o valor null dentro de uma variável?
r: Significa dizer que aquela memória está vazia. Significa dizer também que o é um objeto inexistente.

## DICIONÁRIO ##

CONCATENAÇÃO: Concatenar é uma palavra que significa "colocar junto". Para colocar strings juntas em JavaScript, usamos o operador (+), o mesmo usamos para colocar junto vários tipos de váriáveis, como por exemplo:

```Javascript
var nameUser = window.prompt('Qual é o seu nome?')
window.alert('É um prazer em te conhecer, ' + nameUser + '.')
```

## MÓDULO B - AULA 7 - Operadores (Parte 1)
## MÓDULO B - AULA 8 - Operadores (Parte 2)


