# Short Circuit em JavaScript

O short circuit é uma técnica utilizada em JavaScript para evitar a avaliação desnecessária de expressões. Isso é feito utilizando os operadores lógicos `&&` e `||`.

Quando utilizamos o operador `&&`, o JavaScript avalia a primeira expressão. Se ela for falsa, o resultado será sempre falso, independentemente do valor da segunda expressão. Dessa forma, a segunda expressão não é avaliada, economizando tempo de processamento.

Exemplo:

```javascript
let x = 5;
let y = 10;

// Sem short circuit
if ((x > 0) && (y > 0)) {
    console.log('x e y são maiores que 0');
}

// Com short circuit
if (x > 0 && y > 0) {
    console.log('x e y são maiores que 0');
}
```

Da mesma forma, quando utilizamos o operador `||`, o JavaScript avalia a primeira expressão. Se ela for verdadeira, o resultado será sempre verdadeiro, independentemente do valor da segunda expressão. Dessa forma, a segunda expressão não é avaliada, economizando tempo de processamento.

```javascript
let x = 5;
let y = -10;

// Sem short circuit
if ((x > 0) || (y > 0)) {
    console.log('x ou y é maior que 0');
}

// Com short circuit
if (x > 0 || y > 0) {
    console.log('x ou y é maior que 0');
}
```

É importante lembrar que o short circuit só é aplicado quando a primeira expressão já é suficiente para determinar o resultado final, e não afeta o resultado final da expressão.

---

### [Voltar ao ínicio](./index.md)
