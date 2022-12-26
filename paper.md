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

Regras doo identificador da variável:
- Podem começar com letra, $ ou _;
- não podem começar com números;
- é possível usar letras ou números;
- é possível usar acentos e símbolos;
- não podem conter espaços;
- não podem ser palavras reservadas (exemplo: var, let, const).

Mostrando como abrir o node.js no terminal do vsc:

- Abra um terminal, clicando com o botão direito no campo "explorer" do menu e clique em "Open in Integrated Terminal".
- Digite "node" na linha de comando e dê ENTER.


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
r: variável é um espaço de memória alocada para armazenar algum tipo de dado.

Q02. Como declarar uma variável numérica inteira ou real usando JS e node.js.
r: 

```javascript
 var numeroInteiro = parseInt(window.alert('10'))
var numeroFloat = parseFloat(window.alert('10.1'))

```

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

var number1 = window.prompt('Digite o primeiro número.') // recebe dado da primeira variável.
var number2 = Number(window.prompt('Digite o segundo número')) // recebe dado da segunda variável.
var result = number1 + number2 // cria uma variável aonde a soma dos dados ficam armazenados.
window.alert('O resultado dessa soma é: ' + result + '.') // concatena variáveis e informa o resultado.

// abrindo o f12, olhando o console e vendo o tipo da variável.
console.log('o tipo da variável number1 é: ' + typeof number1)
console.log('o tipo da variável number2 é: ' + typeof number2)
console.log('o tipo da variável result é: ' + typeof result)

/* 

"var result = number1 + number2" - O + tem duas funções dentro do javascript.

concatenação ou soma.

o window.prompt por default retorna uma string no tipo de dado mesmo que seja digitado um número.
se o número é entendido como uma cadeia de caracteres, o programa pensa que é para concatenar e não somar.

se um ou mais tipos de dados informados, armazenados nas variáveis em uma soma aritmética for string, o resultado da soma será string. Portanto se precisarmos fazer somas, precisamos alterar o tipo do dado String para Number.

*/

var number1fix = Number(window.prompt('informe o primeiro número novamente.')) // Convertendo antes de armazenar o valor na variável
var number2fix = Number(window.prompt('informe o segundo número.')) // Convertendo antes de armazenar o valor na variável
var resultFix = number1fix + number2fix
console.log('o tipo da variável number1fix é: ' + typeof number1fix)
console.log('o tipo da variável number2fix é: ' + typeof number2fix)
console.log('o tipo da variável resultFix é: ' + typeof resultFix)
window.alert('o resultado correto é: ' + resultFix + ".")

// seria possível também ao invés de usar o Number, usar o Number.parseInt(n) ou Number.parseFloat(n) ... inteiros e numeros reais

// é possível também converter o contrário, da seguinte forma:
      
var numero = Number(window.prompt('informe um número.'))
numero = numero.toString() // transformando para tipo string ou String(numero)
console.log(typeof numero)
```
Formatando Strings: (node)

```node.js
> var s = 'JavaScript'
undefined
> s
'JavaScript'
> 'Eu estou estudando s'
'Eu estou estudando s'
> 'Eu estou estudando ' + s
'Eu estou estudando JavaScript'
> nome = 'André'
'André'
> idade = 32
32
> nota = 5.5
5.5
> nome
'André'
> idade
32
> nota
5.5
> 'O aluno ' + nome + ' com ' + idade + ' anos tirou a nota ' + nota + '.'
'O aluno André com 32 anos tirou a nota 5.5.'
> `O aluno ${nome} com ${idade} anos tirou a nota ${nota}.`
'O aluno André com 32 anos tirou a nota 5.5.'
```

## APRENDENDO NOMES CORRETOS ##

```javaScript
    var linguagem = 'JavaScript'
    var frase1 = 'Eu estou aprendendo linguagem' // não faz interpolação
    var frase2 = 'Eu estou aprendendo ' + linguagem // usa concatenação
    var frase3 = `Eu estou aprendendo ${linguagem}` // usa template string com placeholder pra armazenar variáveis dentro.

     var username = window.prompt('Qual seu nome?')
    window.document.write(`Seu nome tem ${username.length} letras.<br>`) // quantidade da letras na variável (ele também conta os espaços caso digite nome completo.)
    // aprimorando um pouco ficaria:
    var username2 = window.prompt('Qual seu nome?')
    window.document.writeln(`Olá, <strong>${username2}</strong>! Seu nome tem ${username2.length} letras.<br>`)
    window.document.writeln(`Seu nome em letras maiúsculas é ${username2.toUpperCase()}.<br>`)
    window.document.writeln(`Seu nome em minúsculas é ${username2.toLowerCase()}.`)
    var n1 = 1545.5 // declara variável com identificador de nome "n1" e informa que ela recebe um dado do tipo number(float).
    n1 = n1.toFixed(2).replace('.', ',')  // fixa o valor de casas decimais depois da virgula em 2 / substitui ponto por virgula.
    console.log(n1)
    
    var salary = 1850.9
    salary = salary.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'}) // formata para informar cifrão R$, se quiser transformar para DOLLAR troca pra 'USD' ao invés do 'BRL' ou 'EUR' para euro.
    console.log(salary)
```


## MÓDULO B - AULA 7 - Operadores (Parte 1)

Q01. Como é possível guardar o valor digitado no prompt() dentro de uma variável?
r: 
```javascript
    var dado_passado = window.document.prompt('informe o valor do dado')
    console.log(dado_passado)
```
Q02. Como fazer com que um número digitado em um prompt() possa ser usado em cálculos?
r: transformando o tipo do valor das variáveis armazenadas de string para number.
```javascript
    var numero1 = Number(window.document.prompt('informe numero 1')) // possível usar parseFloat ou parseInt tb
    var numero2 = Number(window.document.prompt('informe numero 2')) // possível usar parseFloat ou parseInt tb
    var resultado = numero1 + numero2
    window.alert(`o resultado da operação é: ${resultado}.`)
```
Q03. Como transformar um texto todo para letras MAIÚSCULAS?
r:
```javascript
    var textoRecebido = window.prompt('informe texto')
    var textoCaixaAlta = textoRecebido.toUpperCase()
    window.document.write(`o texto ficou: <strong>${textoCaixaAlta}.</strong>`)

```
Q04. Como mostrar um número formatado como um valor monetário?
```javascript
    var userName = window.prompt('informe seu nome.')
    var userSalary = Number(window.prompt(`Certo, ${userName}. Agora, informe seu salário.`))
    userSalaryBRL = userSalary.toFixed(2).replace('.',',').toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'})
    var BRLtoUSDSalary = userSalaryBRL / 5.26
    var messageReturn = document.write(`O salário em real ${userSalaryBRL} convertido para Dóllar fica em ${BRLtoUSDSalary}.`)
    
```

Operadores vistos neste curso

- ARITMÉTICOS
- ATRIBUIÇÃO
- RELACIONAIS
- LÓGICOS
- TERNÁRIO



OPERADORES ARITMÉTICOS:
- operadores usados para fazer cálculo:

5 + 2 = 7 (adição)
5 - 2 = 3 (subtração)
5 * 2 = 10 (multiplicação)
5 / 2 = 2.5 (divisão real)
5 % 2 = 1 (resto da divisão inteira)
5 ** 2 = 25 (potência)

Ordem de precedência:

1. Parênteses ()
2. Expoentes (potências) **
Multiplicações e divisões; (da esquerda para a direita) * / %
Somas e subtrações. (da esquerda para a direita) + -


OPERADORES DE ATRIBUOÇÃO: 

Autoatribuições:

var n = 3 (n valendo 3)
n = n + 4 (agora n vale 7)
n = n -5 (agora n vale 2)
n = n * 4 (agora n vale 8)
n = n / 2 (agora n vale 4)
n = n ** 2 (agora n vale 16)
n = n % 5 (agora n vale 1)

Simplificando

funciona para encurtar o código e só funciona se a variável receber ela mesma, seguida de algum operador aritmédico, exemplo:
supondo que o valor de n seja 1, no método comum temos:
var n = 3
n = n + 4 
n = 7 

simplficando ficaria assim:
var n = 3
n += 4
n = 7
------
var n = 3
n -= 5
n = -2
------
var n = 3
n *= 4
n = 12
------
var n = 3
n /= 2
n = 1.5
------
var n = 3
n **= 2
n = 9
------
var n = 3
n %= 5
n = 3

operador de incremento

o normal:
var x = 5
x = x + 1

simplificando:

x += 1
x -= 1

simplicando ainda mais

x ++ 
x -- 

```node.js
(pós encremento)
> var n = 10
undefined
> n++
10
> n
11
> n--
11
> n
10
>

(pré encremento)
> x = 10
10
> --x
9
> ++x
10
> x
10
>
```


## MÓDULO B - AULA 8 - Operadores (Parte 2)

Q01. Para que serve o operador % em JS? Seria para calcular porcentagem?
r: não. Ele é usado para obter o valor do resto de uma divisão

Q02. 6 + 4 / 2 é igual a 5 ou igual a 8?
r: 8 divisão antes da adição, ordem de precedência.

Q03. Se uma variável n está valendo 10 e executamos um n += 5, qual será o seu novo valor?
r: n = 15

```node.js
> var n = 10
undefined
> n += 5
15
>
```
Q04. O que acontece quando colocamos os operadores ++ ou -- do lado de uma variável?
r: ela soma +1 a essa variável ou -1 a essa variável.

```node.js
(pós encremento)
> var n = 10
undefined
> n++
10
> n
11
> n--
11
> n
10
>

(pré encremento)
> x = 10
10
> --x
9
> ++x
10
> x
10
>
```

OPERADORES RELACIONAIS:

Para toda expressão que tenha um operador relacional ligado a ela, o resultado dessa expressão sempre será um valor booleano (true or false)

```javascript
5 > 2 // 5 maior que 2 = true
7 < 4 // 7 menor que 4 = false
8 >= 8 // 8 maior ou igual 8 = true
9 <= 7 // 9 menor ou igual 7 = false
5 == 5 // 5 igual a 5 = verdadeiro
4 != 4 // 4 não igual 4 (algo que não é igual é diferente) = false
```

Abrindo o node.js

```node.js
> 5 < 2
false
> 5 <= 5
true
> 5 >= 5
true
> 5 != 5
false
> 5 != 4
true
> var a = 8
undefined
> var b = 15
undefined
> a > b
false
> b > a
true
> a <= b - 10
false
> a == b
false
> a != b
true
```

OPERADORES DE IDENTIDADE:



```javascript

// var x = 5 (var x recebe 5)
// x == '5' (true, x tem o mesmo valor que '5')
// x === '5' (false, x tem o mesmo valor que '5' mas não tem o mesmo tipo de dados (number e string))
5 == 5 // true  
5 == '5' // true 
5 === '5' // false
5 === 5 // true

var a = 10
var b = '10'

a != b // false
a !== b // true
```

```node.js
> var a = 10
undefined
> var b = '10'
undefined
> typeof a
'number'
> typeof b
'string'
> a != b
false
> a !== b
true
```

 OPERADORES LÓGICOS:

 ! --> negação (eu quero uma caneta diferente de azul... qualquer cor menos azul)
 && -- conjunção (eu quero uma caneta azul e uma vermelha... precisa ser essas duas, não apenas uma delas, mas as duas juntas)
 || -- disjunção (eu quero uma caneta azul ou uma vermelha... pode ser ambas, pode ser apenas uma das duas, só não pode não ter nenhuma delas)

 exemplos no node.js

 ```node.js
    > var a = 8
undefined
> var b = 15
undefined
> a > b
> var a = 10
undefined
> var b = '10'
> var a = 5
undefined
> var b = 8
undefined
> true && false
false
> true && true
true
> false && false
false
> false || false
false
> false || true
true
> true || false
true
> true || true
true
> a > b && b % 2 == 0
false
>
 ```
```javascript

 ordem de precedência entre tipos de operadores
 Operadores aritméticos:
 +
 -
 *
 /
 **
 Operadores relacionais:
 // < maior que
 // > menor que
 // <= maior ou igual
 // >= menor ou igual
 // <== maior ou identico
 // >== menor ou identico
 Números lógicos:

 exemplo:
 var a = 5
 var b = 8
 então: > a > b && b % 2 == 0 (tem que dar false)

 desmembrando:  0 == 0 ? (verdade) mas precisa ver a condição que vem antes do &&, se ela também for verdade, aí sim é verdade, porque o operador && precisa que ambos sejam verdade ou mentira.

 continuando: 5 > 8 ? (falso)

 ou seja: se as duas condições fossem true, aí o resultado da expressão era true, mas por ser o elemento de conjunção se um não for false, sempre será false.
```

### ORDEM DE PRECEDÊNCIA DE TODOS OPERADORES

```javascript
    //Aritméticos: 

    1º () // parênteses
    2º ** // expoentes
    3º /,% // multiplicadores e divisores

```



