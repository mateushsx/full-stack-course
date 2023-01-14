# Valores primitivos vs valores por referência em JavaScript

Em JavaScript, existem dois tipos de valores: valores primitivos e valores por referência.

Valores primitivos são tipos de dados simples que incluem números, strings, booleanos, `null` e `undefined`. Quando você trabalha com valores primitivos, você está trabalhando com uma cópia do valor. Por exemplo, se você atribuir um valor primitivo a uma variável e, em seguida, atribuir esse valor a outra variável, as duas variáveis terão cópias independentes do valor.

```javascript
let x = 5;
let y = x;
x = 7;
console.log(y); // 5
```

Valores por referência, por outro lado, são tipos de dados que incluem objetos, arrays e funções. Quando você trabalha com valores por referência, você está trabalhando com uma referência para o objeto, e não uma cópia. Isso significa que as alterações feitas em um objeto em uma variável serão refletidas em todas as outras variáveis que referenciam esse objeto.

```javascript
let obj1 = {a: 1};
let obj2 = obj1;
obj1.a = 2;
console.log(obj2.a); // 2
```

É importante lembrar a diferença entre valores primitivos e valores por referência quando se trabalha com código JavaScript, pois isso pode afetar como seu código é executado e como ele se comporta. Em alguns casos, você pode querer fazer uma cópia profunda (_deep copy_) de um objeto para evitar alterações indesejadas.

---

### [Voltar ao ínicio](./index.md)
