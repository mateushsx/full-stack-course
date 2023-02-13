# Trabalhando com Datas em JavaScript

JavaScript possui um objeto chamado Date, que é utilizado para representar datas e horas.

## Criando um objeto Date

Para criar um objeto Date, podemos utilizar o construtor new Date(), que retorna a data e hora atual.

```js
const dataAtual = new Date();
```

Também é possível passar uma string contendo a data para o construtor, seguindo o formato `"yyyy-mm-dd"`.

```js
const dataDeAniversario = new Date('1990-06-30');
```

## Obtendo informações de uma data

Podemos obter informações específicas de uma data, utilizando os métodos do objeto `Date`. Por exemplo, para obter o ano de uma data, utilizamos o método `getFullYear()`.

```js
const anoDeAniversario = dataDeAniversario.getFullYear();
```

## Formatando datas

O objeto `Date` não possui um método para formatar datas em um formato específico. Para isso, podemos utilizar bibliotecas externas, como o `moment.js` ou o `date-fns`.

## Trabalhando com timestamps

Outra forma de representar datas em JavaScript é utilizando timestamps. Um timestamp é um número que representa a quantidade de milissegundos desde o Unix Epoch (1 de janeiro de 1970, 00:00:00 UTC). Para obter o timestamp de uma data, utilizamos o método `getTime()`.

```js
const timestamp = dataAtual.getTime();
```

Também é possível criar um objeto Date a partir de um timestamp, passando o timestamp como argumento para o construtor.

```js
const dataDoTimestamp = new Date(1644764400000);
```

Isso é apenas uma introdução às datas em JavaScript, mas já deve ajudar a entender como trabalhar com datas em suas aplicações.

---

### [Voltar ao ínicio](./index.md)
