# Funções em JavaScript

Uma função em JavaScript é um bloco de código reutilizável que pode ser invocado para realizar uma tarefa específica. Elas são usadas para organizar o código e facilitar a manutenção e reutilização.

Existem várias maneiras de criar uma função em JavaScript, mas a mais comum é usando a palavra-chave `function` seguida pelo nome da função e parênteses `()`. Dentro dos parênteses, você pode incluir parâmetros, que são valores que a função espera receber quando for chamada.

```javascript
function sayHello(name) {
    console.log(`Hello, ${name}!`);
}
```

Para chamar (ou invocar) uma função, você simplesmente usa seu nome seguido de parênteses e, se necessário, passa os parâmetros necessários.

```javascript
sayHello('John'); // imprime "Hello, John!"
```

Funções também podem retornar valores usando a palavra-chave `return`.

```javascript
function add(a, b) {
    return a + b;
}

let result = add(3, 4);
console.log(result); // 7
```

Além das funções tradicionais, também existem funções de seta (arrow functions) e funções construtoras. As funções de seta são uma forma mais curta de escrever funções e as funções construtoras são usadas para criar objetos personalizados.

```javascript
// arrow function
let multiply = (a, b) => a * b;
console.log(multiply(3, 4)); // 12

// constructor function
function Person(name, age) {
    this.name = name;
    this.age = age;
}

let john = new Person('John', 30);
console.log(john.name); // "John"
console.log(john.age); // 30
```

É importante lembrar que as funções em javascript possuem escopo, isso significa que as variáveis declaradas dentro de uma função só estão disponíveis dentro da função.
