# Tipos Primitivos em JavaScript

JavaScript possui seis tipos primitivos: `string`, `number`, `boolean`, `null`, `undefined` e `symbol`.

## string

Uma `string` é uma sequência de caracteres. Elas podem ser declaradas usando aspas simples ou duplas.

Exemplo:

```javascript
let nome = 'João';
let sobrenome = 'Silva';
console.log(nome + ' ' + sobrenome); // imprime "João Silva"
```

## number

Um `number` é um valor numérico. JavaScript não possui tipos de dados diferentes para inteiros e números de ponto flutuante.

Exemplo:

```javascript
let idade = 25;
let altura = 1.75;
console.log(idade + altura); // imprime 26.75
```

## boolean

Um `boolean` representa um valor lógico verdadeiro ou falso.

Exemplo:

```javascript
let maiorDeIdade = true;
let temCarteiraDeMotorista = false;
console.log(maiorDeIdade && temCarteiraDeMotorista); // imprime false
```

## null

O valor `null` representa a ausência intencional de um valor.

Exemplo:

```javascript
let endereco;
console.log(endereco); // imprime undefined
endereco = null;
console.log(endereco); // imprime null
```

## undefined

O valor `undefined` é atribuído a uma variável que foi declarada, mas não foi inicializada com um valor.

Exemplo:

```javascript
let telefone;
console.log(telefone); // imprime undefined
```

## symbol

Um `symbol` é um tipo de dado único e imutável. Ele é usado como identificador único para propriedades de objetos.

Exemplo:

```javascript
let id = Symbol();
let pessoa = {
    [id]: 12345,
};
console.log(pessoa[id]); // imprime 12345
```

É importante notar que esses são os tipos primitivos básicos do JavaScript, e existem outros tipos de dados como Array e Object.

---

### [Voltar ao ínicio](./index.md)
