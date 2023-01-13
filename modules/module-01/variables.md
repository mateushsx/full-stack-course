# Variáveis em JavaScript

Em JavaScript, as variáveis são usadas para armazenar valores. Elas podem ser declaradas usando a palavra-chave `var`, `let` ou `const`.

## var

A palavra-chave `var` é usada para declarar variáveis tradicionais no JavaScript. Elas são visíveis em todo o escopo do script e podem ser reatribuídas a qualquer momento.

Exemplo:

```javascript
var nome = 'João';
console.log(nome); // imprime "João"
nome = 'Maria';
console.log(nome); // imprime "Maria"
```

## let

A palavra-chave `let` é usada para declarar variáveis que possuem escopo de bloco. Isso significa que elas só são visíveis dentro do bloco em que foram declaradas e podem ser reatribuídas a qualquer momento.

Exemplo:

```javascript
let idade = 25;
console.log(idade); // imprime 25
idade = 30;
console.log(idade); // imprime 30
```

## const

A palavra-chave `const` é usada para declarar variáveis constantes. Isso significa que uma vez atribuído um valor à variável, ele não pode ser mais modificado.

Exemplo:

```javascript
const pi = 3.14;
console.log(pi); // imprime 3.14
pi = 3.1415; // gera um erro, pois a variável "pi" é uma constante
```

Em geral, é recomendado usar `const` sempre que possível, pois isso ajuda a evitar erros e torna o código mais fácil de entender.

---

### [Voltar ao ínicio](./index.md)
