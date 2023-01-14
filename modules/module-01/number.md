# Number em JavaScript

O JavaScript possui um tipo de dados chamado `Number` que é utilizado para representar números. Ele pode ser usado para representar tanto números inteiros quanto números de ponto flutuante.

```javascript
let int = 42; // número inteiro
let float = 3.14; // número de ponto flutuante
```

Além disso, o JavaScript possui algumas propriedades e métodos específicos para trabalhar com números, como por exemplo:

-   `Number.MAX_VALUE`: retorna o maior valor que um número no JavaScript pode ter. <br>
-   `Number.MIN_VALUE`: retorna o menor valor que um número no JavaScript pode ter.<br>
-   `Number.POSITIVE_INFINITY`: representa o infinito positivo.<br>
-   `Number.NEGATIVE_INFINITY`: representa o infinito negativo.<br>
-   `Number.NaN`: representa um valor "Not a Number".<br>
-   `Number.isInteger(value)`: retorna true se o valor passado é um número inteiro, false caso contrário.<br>
-   `Number.isSafeInteger(value)`: retorna true se o valor passado é um número inteiro seguro, false caso contrário.<br>

Além das propriedades e métodos mencionados anteriormente, o JavaScript também possui algumas outras formas de trabalhar com números. Alguns exemplos incluem:

-   `parseInt(string, radix)`: converte uma string em um número inteiro. O parâmetro `radix` é opcional e representa a base numérica da string (padrão é 10).
-   `parseFloat(string)`: converte uma string em um número de ponto flutuante.
-   `Number(value)`: converte um valor em um número.
-   `.toFixed(n)`: retorna uma string com o número formatado com `n` casas decimais.
-   `.toExponential(n)`: retorna uma string com o número no formato exponencial com `n` casas decimais.
-   `.toPrecision(n)`: retorna uma string com o número formatado com `n` dígitos.

Além disso, o JavaScript também suporta operações matemáticas básicas como adição, subtração, multiplicação, divisão e módulo.

É importante observar que o JavaScript tem problemas de precisão para alguns cálculos com ponto flutuante, então é sempre uma boa prática verificar se os resultados estão dentro do esperado.

```javascript
let x = 0.1 + 0.2;
console.log(x); // 0.30000000000000004
```

E sempre que possível, evite trabalhar com números muito grandes ou muito pequenos, pois isso pode causar problemas de precisão.

---

### [Voltar ao ínicio](./index.md)
