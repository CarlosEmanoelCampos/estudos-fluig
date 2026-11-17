# Formulários

## O que aprendi
- Os formulários permitem **coletar informações dos usuários** em uma página web.
- São utilizados para criar campos de preenchimento, como nome, e-mail e senha.
- O usuário pode inserir informações e enviá-las por meio de um formulário.
- As tags ajudam a organizar e identificar cada campo.

## Tags principais
- `<form>` representa um **formulário**, utilizado para agrupar campos e permitir o envio de informações.
- `<input>` representa um **campo de entrada**, utilizado para receber informações do usuário.
- `<label>` representa um **rótulo**, utilizado para identificar um campo do formulário.
- `<textarea>` representa uma **área de texto**, utilizada para escrever mensagens maiores.
- `<button>` representa um **botão**, utilizado para executar uma ação, como enviar um formulário.
- `placeholder` define um **texto de orientação** dentro de um campo, indicando o que o usuário deve preencher.

## Exemplo

```html
<form>
    <label for="nome">Nome:</label>
    <input type="text" id="nome" placeholder="Digite seu nome">

    <br><br>

    <label for="email">E-mail:</label>
    <input type="email" id="email" placeholder="Digite seu e-mail">

    <br><br>

    <label for="mensagem">Mensagem:</label>
    <textarea id="mensagem" placeholder="Escreva sua mensagem"></textarea>

    <br><br>

    <button type="submit">Enviar</button>
</form>
```
