# Alert, Confirm e Prompt em JavaScript

O JavaScript fornece três funções importantes para interagir com os usuários:

-   **alert()**: exibe uma caixa de alerta com uma mensagem especificada e um botão OK.

```javascript
alert('Esta é uma mensagem de alerta');
```

-   **confirm()**: exibe uma caixa de confirmação com uma mensagem especificada e botões OK e Cancelar. Retorna verdadeiro se o usuário clicar em OK e falso se o usuário clicar em Cancelar.

```javascript
const resultado = confirm('Tem certeza de que deseja excluir este item?');
if (resultado) {
    // usuário clicou OK
} else {
    // usuário clicou Cancelar
}
```

-   **prompt()**: exibe uma caixa de solicitação com uma mensagem especificada, um campo de texto e botões OK e Cancelar. Retorna o valor digitado pelo usuário se o usuário clicar em OK e nulo se o usuário clicar em Cancelar.

```javascript
const idade = prompt('Qual é a sua idade?');
if (idade != null) {
    console.log('Sua idade é ' + idade);
} else {
    console.log('Você clicou em Cancelar');
}
```

É importante notar que essas funções irão bloquear a execução do script até que o usuário interaja com elas.

---

### [Voltar ao ínicio](./index.md)
