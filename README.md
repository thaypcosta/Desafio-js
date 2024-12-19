# Boas-vindas ao Alerta Interativo

Este projeto demonstra o uso de interações básicas em JavaScript, como exibição de alertas, coleta de dados do usuário com `prompt` e condições baseadas em valores fornecidos.

## Funcionalidades

- Exibe mensagens de boas-vindas ao usuário.
- Armazena e manipula variáveis como nome, idade, número de vendas e saldo disponível.
- Mostra alertas de erro simulados.
- Permite ao usuário fornecer seu nome e idade.
- Verifica se o usuário tem idade suficiente (18 ou mais) para tirar a habilitação.

## Código Principal

```javascript
// Exibe um alerta inicial de boas-vindas
alert('Boas vindas ao nosso site!');

// Declaração e inicialização de variáveis
let nome = 'Lua';
let idade = 25;
let numeroDeVendas = 50;
let saldoDisponivel = 1000;

// Exibe um alerta de erro
alert('Erro! Preencha todos os campos');

// Mensagem de erro armazenada em uma variável
let mensagemDeErro = 'Erro! Preencha todos os campos';
alert(mensagemDeErro);

// Solicita o nome e a idade do usuário
nome = prompt('Qual seu nome?');
idade = prompt('Qual sua idade?');

// Verifica se a idade permite tirar habilitação
if (idade >= 18) {
   alert('Pode tirar a habilitação');
}
