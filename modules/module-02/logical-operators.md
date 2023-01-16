# Operadores Lógicos em JavaScript

Os operadores lógicos em JavaScript são utilizados para comparar valores e retornar true ou false. Eles são bastante úteis na programação para determinar se uma determinada condição é verdadeira ou falsa. Os operadores lógicos mais comuns em JavaScript são:

-   `&&` (E lógico): retorna true se ambas as expressões forem verdadeiras
-   `||` (OU lógico): retorna true se pelo menos uma das expressões for verdadeira
-   `!` (Não lógico): inverte o valor da expressão, ou seja, se o valor for verdadeiro, retorna falso e vice-versa

Exemplos:

```javascript
// && (E lógico)
console.log(true && true); // true
console.log(true && false); // false
console.log(false && true); // false
console.log(false && false); // false

// || (OU lógico)
console.log(true || true); // true
console.log(true || false); // true
console.log(false || true); // true
console.log(false || false); // false

// ! (Não lógico)
console.log(!true); // false
console.log(!false); // true
```

É importante lembrar que os operadores lógicos possuem ordem de precedência, assim como os operadores matemáticos, e as expressões dentro de parênteses são avaliadas primeiro.

```javascript
console.log((true && false) || true); // true
console.log((true && false) || true); // true
```

É possível também utilizar operadores lógicos dentro de condicionais, como por exemplo if e while, para determinar quando determinadas ações devem ser realizadas.

```javascript
let idade = 30;
if (idade >= 18 && idade < 60) {
    console.log('Você pode votar!');
}
```

Em resumo, os operadores lógicos em JavaScript são ferramentas poderosas para controlar o fluxo de execução do seu código e tomar decisões baseadas em valores verdadeiros ou falsos.

---

### [Voltar ao ínicio](./index.md)
