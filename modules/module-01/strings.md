# Strings em JavaScript

Em JavaScript, uma string é uma sequência de caracteres encerrada em aspas simples ou duplas. As strings são usadas para representar texto em JavaScript.

Aqui estão alguns exemplos de criação de strings em JavaScript:

```javascript
const string1 = 'Este é uma string';
const string2 = 'Este também é uma string';
const string3 = 'Esta string tem uma "aspa" dentro';
const string4 =
    'Este é um exemplo de string com \'aspas simples\' e "aspas duplas"';
```

Algumas operações comuns que podemos fazer com strings incluem:

-   Concatenação: usando o operador + para juntar duas ou mais strings.

```javascript
const string1 = 'Hello, ';
const string2 = 'world!';
const concatenatedString = string1 + string2; // "Hello, world!"
```

-   Tamanho da string: usando a propriedade .length para obter o comprimento da string.

```javascript
const string1 = 'Hello, world!';
const stringLength = string1.length; // 13
```

-   Busca: usando o método .indexOf() para encontrar a primeira ocorrência de um caractere ou substring dentro da string.

```javascript
const string1 = 'Hello, world!';
const searchIndex = string1.indexOf('l'); // 2
```

-   Substituição: usando o método .replace() para substituir uma substring por outra dentro da string.

```javascript
const string1 = 'Hello, world!';
const newString = string1.replace('world', 'javascript'); // "Hello, javascript!"
```

-   Fatiamento: usando o método .slice() ou o operador [] para selecionar um trecho de uma string.

```javascript
const string1 = 'Hello, world!';
const slicedString = string1.slice(7, 12); // "world"
```

-   Transformação: usando métodos como .toUpperCase() ou .toLowerCase() para mudar as letras de maiúsculas para minúsculas ou vice-versa.

```javascript
const string1 = 'Hello, world!';
const upperCaseString = string1.toUpperCase(); // "HELLO, WORLD!"
const lowerCaseString = string1.toLowerCase(); // "hell0, word!"
```

### Mais Métodos de Strings em JavaScript

Aqui estão alguns métodos adicionais que você pode usar para trabalhar com strings em JavaScript:

-   **.charAt()**: retorna o caractere em um índice especificado em uma string

```javascript
const string1 = 'Olá, mundo!';
const caractere = string1.charAt(7); // "m"
```

-   **.substring()**: retorna uma porção de uma string entre dois índices especificados

```javascript
const string1 = 'Olá, mundo!';
const substring = string1.substring(7, 12); // "mundo"
```

-   **.split()**: divide uma string em um array de substrings usando um separador especificado

```javascript
const string1 = 'uma,string,separada,por,virgulas';
const arraySubstrings = string1.split(','); // ["uma", "string", "separada", "por", "virgulas"]
```

-   **.trim()**: remove espaços em branco do início e fim de uma string

```javascript
const string1 = '    string com espacos no inicio e fim    ';
const trimmedString = string1.trim(); // "string com espacos no inicio e fim"
```

-   **.concat()**: concatena duas ou mais strings

```javascript
const string1 = 'Hello';
const string2 = 'world';
const concatenatedString = string1.concat(' ', string2); // "Hello world"
```

-   **.repeat()**: retorna uma nova string com o valor original repetido n vezes

```javascript
const string1 = 'Hello';
const repeatedString = string1.repeat(3); // "HelloHelloHello"
```

Essas são apenas algumas das operações básicas que podemos fazer com strings em JavaScript, existem vários outros métodos e propriedades disponíveis. É importante notar que as strings são imutáveis, isso significa que uma vez criada uma string, suas propriedades não podem ser mudadas.

---

### [Voltar ao ínicio](./index.md)
