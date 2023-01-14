# Objetos em JavaScript

Objetos em JavaScript são estruturas de dados que armazenam valores em pares chave-valor. Eles são usados para representar entidades do mundo real, como por exemplo, um carro, um usuário, uma configuração, etc.

Existem várias maneiras de criar um objeto em JavaScript, mas uma das maneiras mais comuns é usando a notação de chaves {}. Dentro das chaves, você pode incluir pares de chave-valor, separados por vírgulas.

```javascript
let car = {
    make: 'Toyota',
    model: 'Camry',
    year: 2020,
};
```

Você também pode acessar os valores de um objeto usando a notação de ponto ou colchetes:

```javascript
console.log(car.make); // "Toyota"
console.log(car['model']); // "Camry"
```

Além disso, os objetos em javascript podem ter funções como valores de propriedades, essas são chamadas de métodos.

```javascript
let car = {
    make: 'Toyota',
    model: 'Camry',
    year: 2020,
    start: function () {
        console.log('Engine started!');
    },
};
car.start(); // imprime "Engine started!"
```

JavaScript também fornece alguns métodos para trabalhar com objetos, como:

-   `Object.keys(obj)`: retorna um array com as chaves de um objeto.
-   `Object.values(obj)`: retorna um array com os valores de um objeto.
-   `Object.entries(obj)`: retorna um array com arrays de chave-valor de um objeto.
-   `Object.assign(obj1, obj2, ...)`: copia as propriedades de um ou mais objetos para um objeto de destino.
-   `Object.freeze(obj)`: impede que as propriedades de um objeto sejam adicionadas, removidas ou modificadas.

Há muitas outras maneiras de trabalhar com objetos em javascript, como o uso de classes e herança, entretanto é importante consultar a documentação do javascript para entender melhor.
