Como Criar variáveis, Ex: var nome ou let nome

para uma variável receber um valor usamos var nome = Gustavo (desta forma criamos uma variável e ao mesmo tempo demos uma valor a ela) 

nome = Gustavo (desta forma apenas demos um valor para a variável )

----------------------------------------------------------------------------

Regras das variáveis:

1. Podem começar com letra, $ ou _
2. Não podem começar com números
3. É possível usar letras ou números
4. É possível usar acentos e símbolos
5. Não podem conter espaços
6. Não podem ser palavras reservadas

Dicas

1. Maiúsculas e minúsculas fazem diferença
2. Tente escolher nomes coerentes para as variáveis
3. Evite se tornar um 'programador alfabeto' ou um 'programador contador' Ex: Não usar os nomes das variáveis como “a”, “b”, “c”, etc; ou “a1”, “a2”, “a3”, etc.
4. Variáveis servem pra guardar dados

----------------------------------------------------------------------------

Data Types
1. number
-Infinity
-NaN (Not a Number)

2. string

3. boolean

4. null

5. undefined

6. object
-array

7. function

EXTRA

Numbers: 1; -2; 4.5; 6.555 -> Basicamente números
Strings: Maria, Google, João, pedreiro, (seu CPF) -> Basicamente cadeia de caracteres
Boolean: True; False ->

----------------------------------------------------------------------------

Comandos

window.alert(‘este comando emite uma mensagem!')
window.confirm(‘este comando faz uma pergunta de confirmação')
window.prompt(‘este comando faz um pergunta de resposta!')

----------------------------------------------------------------------------

Conversão de String -> Number

Number.parseInt(n)
Number.parseFloat(n)
Number(n)

----------------------------------------------------------------------------

Transformando um number em uma string

window.alert ('a soma dos números é: ' + soma.toString())  // Jeito mais antigo
ou
window.alert ('a soma dos números é: ' + String(soma))      // Jeito mais simples

----------------------------------------------------------------------------

Formatando Strings

Template String: Eu estou aprendendo ${s}
s.length // Quantos caracteres a string tem
s.toUpperCase() // tudo para 'MAIÚSCULAS'
s.toLowerCase() // tudo para 'minúsculas'

----------------------------------------------------------------------------

Float Number

n.toFixed(2) // duas casas decimais
n.toFixed(2).replace('.', ',') // trocar ponto (padrão) para vírgula
n.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'}) // coloca o R$

----------------------------------------------------------------------------

Operadores:

Tipos de operadores que vamos estudar:

Aritméticos
Atribuição
relacionais
lógicos
ternários

----------------------------------------------------------------------------

Ordem de Precedência:

[1. Aritméticos]

1. ( ) 

2. **

3. [{*   /   % } 
Mesma ordem de Precedência e se por acaso mais de um deles estiver na mesma linha vai fazer da ESQUERDA pra DIREITA qual aparecer PRIMEIRO]

4. [{+  - }
Mesma ordem de Precedência e se por acaso mais de um deles estiver na mesma linha vai fazer da ESQUERDA pra DIREITA qual aparecer PRIMEIRO]

----------------------------------------------------------------------------

[2. Relacionais]
NÃO TEM ORDEM DE PRECEDÊNCIA QUEM APARECER PRIMEIRO VAI SER FEITO PRIMEIRO

>
<
>=
<=
==
===
!=
!==

----------------------------------------------------------------------------

[3. lógicos {! -> && -> ||}]

----------------------------------------------------------------------------

Operadores Aritméticos:

+     // Somar   
-    // Subtrair
*    // Multiplicação 
/    // Divisão
%   // Resto de uma divisão 
**   // Potencia do primeiro numero elevado ao segundo

5 + 3   = 8
5 - 3    = 2
5 * 3    = 15
5 / 3    = 1,6
5 % 3  =  2
5 ** 3   = 125

Precedência dos operadores↓

( ) 
**
*   /   %  : Mesma ordem de Precedência e se por acaso mais de um deles estiver na mesma linha vai fazer da ESQUERDA pra DIREITA qual aparecer PRIMEIRO
+  - : Mesma ordem de Precedência e se por acaso mais de um deles estiver na mesma linha vai fazer da ESQUERDA pra DIREITA qual aparecer PRIMEIRO

Operadores de Atribuição:

Auto Atribuições:                                                      Forma Simplificada:

var  n = 3                                                              var n = 3

n = n + 4    // ele vai somar ele mesmo a 4                              |   n += 4 
n = n - 5    // ele vai pegar ele mesmo e subtrair 5                     |   n -= 2
n = n  * 4   // ele vai pegar ele mesmo e multiplicar por 4              |   n *= 5
n = n  / 2   // ele vai pegar ele mesmo e dividir por 2                  |   n /= 2
n = n ** 2  // ele vai pegar ele mesmo e elevar a 2 potência             |   n **= 2
n = n %  5 // ele vai pegar ele mesmo, dividir por 5 e dar o resto       |   n %= 5

Incremento:

n++     // é a mesma coisa que n = n + 1 ou n += 1
n—     // é a mesma coisa que n = n - 1 ou n -= 1
++n    // ele vai somar antes
—n    // ele vai diminuir antes

----------------------------------------------------------------------------

Operadores Relacionais:

TRUE (Verdadeiro)
FALSE (FALSO)

5 > 2 : 5 É MAIOR QUE 2 [Sim] Então o Resultado é True
7 < 4 : 7 é MENOR que 4 [Nâo] Então o Resultado é False
8 >= 8 : 8 MAIOR OU IGUAL a 8 [Sim] Então o Resultado é True
9 <= 7 : 9 MENOR OU IGUAL 7 [Não] Então o Resultado é False
5 == 5 : 5 é IGUAL a 5 [Sim] Então o Resultado é True
4 != 4 : 4 e DIFERENTE de 4 [Não] Então o Resultado é False

----------------------------------------------------------------------------

Operador de Identidade ou igualdade restrita:

5 == 5 : TRUE
5 == '5' : TRUE // TEM O MESMO VALOR OU PESO 
5 === '5' : FALSE // TESTANDO SE SÃO O MESMO VALOR E O MESMO TIPO
5 === 5 : TRUE
5 != 5 : FALSE // SÃO DE TIPOS DIFERENTES 
5 !== : TRUE // SÃO DE TIPOS DIFERENTES MAIS O VALOR INTERNO É O MESMO

----------------------------------------------------------------------------

Operadores Lógicos ( ! -> && -> || ):

! é NEGAÇÃO // Só tem uma operação ou é TRUE ou é FALSE, (UMA COISA QUE NÃO É [TRUE] É (FALSE)), (UMA COISA QUE NÃO É (FALSE) É [TRUE])

&& é CONJUNÇÃO // OS 2 RESULTADOS PRECISAM SER VERDADEIROS ([TRUE] and [TRUE] = [TRUE]), ([TRUE] and (FALSE) = (FALSE)), ((FALSE) and [TRUE] = (FALSE)), ((FALSE) and (FALSE) = (FALSE))

|| é DISJUNÇÃO // BASTA QUE 1 DOS RESULTADOS SEJA VERDADEIRO ([TRUE] and [TRUE] = [TRUE]), ([TRUE] and (FALSE) = [TRUE]), ((FALSE) and [TRUE] = [TRUE]), ((FALSE) and (FALSE) = (FALSE))

----------------------------------------------------------------------------

Operador Ternário

Este operador condicional ternário é o semelhante a

if(condição) { //faz algo se a condição for verdadeira }
else { //faz outra coisa caso contrário }

? = então
: = se não

condição ? "valor 1" : "valor 2"

CONDIÇÃO = CONDIÇÃO A SER TESTADA

* CASO A CONDIÇÃO SEJA VERDADEIRA, É ATRIBUÍDO 'VALOR1'
* CASO A CONDIÇÃO SEJA FALSA, É ATRIBUÍDO O 'VALOR2'

Exemplo de condições:

var valor = 10;
valor == 20 ? 'sim' : 'não' // retorna 'não'
valor !=20 ? 'sim' : 'não' // retorna 'sim'
valor < 20 ? 'sim' : 'não' // retorna 'sim'

----------------------------------------------------------------------------

Entendendo o DOM

A sigla DOM significa "Document Object Model" ("Modelo de Objetos para Documentos) e é utilizada nos navegadores como o Google Chrome quando o JavaScript é utilizado.

Basicamente, é composto por um conjunto de Objetos dentro do navegador que dão acesso aos componentes presentes dentro do site. Ele não funciona dentro do NodeJS, por exemplo, apenas em navegadores.

Para compreender bem o DOM, é preciso conhecer a "Árvore DOM": um modelo de hierarquias entre objetos que é a maneira como o DOM "observa" e trabalha com os elementos dentro de um navegador. A raiz dessa árvore começa na janela do navegador -> "window". A partir daí, pode seguir diversos caminhos da hierarquia de objetos.

Um exemplo de rota dentro da Árvore de Hierarquias do DOM:

WINDOW -> DOCUMENT -> HTML -> BODY -> P -> STRONG.

Acima temos elementos de window até strong. Por meio do DOM, posso também selecionar cada elemento de uma rota na árvore e usá-los para fazer alguma coisa com o JavaScript.

----------------------------------------------------------------------------

Métodos de Acesso no DOM

Para acessar meus elementos (e usá-los para algo), são cinco métodos:

1. Ex por Marca: getElementsByTagName('p')[0]
2. por ID: getElementById('div#msg')
3. por Nome: getElementsByName('msg')[0]
4. por Classe: getElementsByClassName('msg')[0]
5. por Seletor (CSS): querySelector('div#msg') ou querySelectorAll('div#msg')[0]
Para usar meus elementos, devo acessá-los por um dos métodos acima e guardar esse elemento em uma variável. Agora, com JavaScript, consigo manipular esta variável para fazer outras coisas.

Lembrando que, dentro do querySelector() e querySelectorAll, utilizar # é para div e . é para classe.

OBS: Se estiver usando o querySelectorAll() deve colocar os [] e dentro dos [] escolher qual o número vc deseja selecionar levando em consideração que o primeiro sempre será 0 (ZERO).

----------------------------------------------------------------------------

Eventos DOM

Evento é tudo que pode acontecer com um elemento da janela.

No exercício 06 da aula 10 (no código) vemos vários eventos de mouse (clique, entrada e saída do cursos sobre uma área delimitada [em uma div]) que quando detectados (listen) produzem um efeito na janela.

Procurar mais sobre eventos que podem acontecer no DOM (DOM Events) em: https://developer.mozilla.org/pt-BR/docs/Web/Events

----------------------------------------------------------------------------

Switch (Condição Múltipla)

Switch é um tipo de condicional que, diferente do IF/ELSE, não serve para todos os momentos. Sua estrutura é:

switch (expressão) {
    case valor1:
    {bloco aqui}
    break                   //obrigatório//

    case valor2:
    {bloco aqui}
    break

    case valor3:
    {bloco aqui}
    break

    default:
    {bloco aqui}
    break
}
O switch só funciona com números ou strings. É mais válido se você tem valores pontuais, não para avaliar intervalos de informação -> neste caso, é mais interessante utilizar o IF/ELSE.

----------------------------------------------------------------------------

Estruturas de Repetição no JS

São três estruturas de repetição estudadas neste curso:

Repetições com teste no início (WHILE)
Repetições com teste no final (DO WHILE)
Repetições com controle (FOR)

----------------------------------------------------------------------------

Sobre estrutura de repetição com variável de controle

A estrutura "for" tem três partes:

for(inicio; teste; inc) {

}
O início é a inicialização da estrutura; teste é referente ao teste lógico que é realizado; e inc refere-se a incrementação (adição de uma unidade na variável). Enquanto o resultado do teste lógico for (normalmente) True, a repetição acontece. No momento que o resultado do teste lógico for False, o laço de repetição é desfeito e a estrutura é encerrada.

Lembrando: o resultado do teste lógico pode mudar porque ocorre um incremento. A cada incremento, o teste lógico é feito novamente.

----------------------------------------------------------------------------

Comparação entre estrutura while e for

Abaixo, as duas estruturas realizam a mesma operação.

var c = 1
while (c <= 10) {
    bloco A
    c++
}

for (var c = 1; c <= 10; c++) {
    bloco A
}

----------------------------------------------------------------------------

Variáveis
São de 2 tipos: simples e composta.

Variáveis Simples
Capaz de armazenar apenas um valor por vez.

Variáveis Compostas
São capazes de armazenar vários valores em uma mesma estrutura.

A variável composta também conhecido como "array" ou vetor. O vetor é uma variável que tem vários elementos e cada elemento é composto por seu valor e por uma chave de identificação.

----------------------------------------------------------------------------

Exemplos com Array (Variável Composta)

let num = [5, 8, 4]

num[3] = 6      // Adiciona 6 depois do 4
num.push(7)     // Adiciona 7 depois do 6
num.length      // Sem parênteses, é atributo

// Resultado: num = [5, 8, 4, 6, 7]

num.sort()      // Reorganiza em ordem crescente

// Resultado: num = [4, 5, 6, 7, 8]
Eu também posso utilizar uma estrutura de repetição para mostrar o conteúdo do meu array, ou seja, seus elementos. No exemplo a seguir, a escolha foi pela estrutura de repetição "for" - mesmo conteúdo exposto em uma das aulas explicativas.

for (let pos=0; pos <= num.length; pos++) {
    console.log(num[pos])
}
Valor -1
Para o JS, quando o usuário busca um valor no array e ele não é encontrado, o JS retorna por padrão este valor como -1.

----------------------------------------------------------------------------

Funções

Uma função JavaScript só pode executar um único retorno.

----------------------------------------------------------------------------


A seguir

O prof. Guanabara recomenda os seguintes próximos passos.

1. Fazer o curso de HTML5 + CSS3
2. Estudar functions (funções): tem muito conteúdo, por exemplo, arrow functions, callbacks, funções anônimas, JavaScript funcional, etc.
3. Objetos: declarar objetos, usar objetos, orientação a objetos
4. Modularização: reusar os códigos
5. Estudar expressões regulares (RegEx): validação de dados, economizada de tempo, etc.
6. Estudar JSON
7. AJAX
8. NodeJS: rodar os scripts no lado do servidor