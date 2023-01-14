# Math em JavaScript

O objeto `Math` em JavaScript fornece uma série de propriedades e métodos para realizar operações matemáticas comuns. Alguns exemplos incluem:

-   `Math.PI`: retorna o valor de PI.
-   `Math.E`: retorna o valor de e (a base dos logaritmos naturais).
-   `Math.abs(x)`: retorna o valor absoluto de x.
-   `Math.round(x)`: arredonda x para o inteiro mais próximo.
-   `Math.ceil(x)`: arredonda x para cima.
-   `Math.floor(x)`: arredonda x para baixo.
-   `Math.sqrt(x)`: retorna a raiz quadrada de x.
-   `Math.pow(x, y)`: retorna x elevado a y.
-   `Math.sin(x)`, `Math.cos(x)`, `Math.tan(x)`: retorna o seno, cosseno e tangente de x (x é em radianos)

Além disso, o objeto Math também possui algumas funções que retornam valores aleatórios:

-   `Math.random()`: retorna um número aleatório entre 0 e 1.
-   `Math.floor(Math.random() * n)`: retorna um número inteiro aleatório entre 0 e n-1.

É importante lembrar que todos os métodos e propriedades do objeto Math são estáticos, portanto, você não precisa criar uma instância de Math para acessá-los.

```javascript
console.log(Math.sqrt(4)); // 2
console.log(Math.random()); // 0.56789
console.log(Math.floor(Math.random() * 10)); // 3
```

Outras propriedades e métodos incluem:

-   `Math.log(x)`: retorna o logaritmo natural de x.
-   `Math.log10(x)`: retorna o logaritmo base 10 de x.
-   `Math.exp(x)`: retorna ex, onde x é a base dos logaritmos naturais.
-   `Math.max(x, y, ...)`: retorna o maior número entre os argumentos passados.
-   `Math.min(x, y, ...)`: retorna o menor número entre os argumentos passados.
-   `Math.trunc(x)`: remove a parte fracionária de x.
-   `Math.sign(x)`: retorna o sinal de x (-1 para negativo, 0 para zero, 1 para positivo).
-   `Math.cbrt(x)`: retorna a raiz cúbica de x.
-   `Math.clz32(x)`: retorna o número de zeros à esquerda no número x representado como uma 32-bit integer.
-   `Math.fround(x)`: retorna o argumento x como uma representação de ponto flutuante de precisão simples.

Esses são apenas alguns exemplos das várias propriedades e métodos disponíveis no objeto Math. É sempre uma boa ideia consultar a documentação do JavaScript para obter uma lista completa e obter mais informações sobre como usá-los.
