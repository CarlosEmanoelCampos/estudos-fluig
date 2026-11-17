# Semântica de Conteúdo

## O que aprendi
- Em vez de usar `<div>` para tudo, uso tags que dão significado ao conteúdo.
-  `<div>` é um elemento genérico utilizado para agrupar conteúdos. Problema que não informa especificamente qual é a função daquele conteúdo.
- Melhora a acessibilidade (leitores de tela) e o SEO (otimização para buscas).

## Tags semânticas
- `<header>` representa o **cabeçalho** de uma página ou seção como logo, nome de site, menu de navegação.
- `<main>` representa **conteúdo principal**, é onde fica as informações mais importante.
- `<section>` representa **seção** e serve para separar conteúdo relacionado dentro de uma página.
- `<footer>` representa **rodapé** e serve para mostrar informações finais da página, como direitos autorais, contatos e links importantes.


## Exemplo
```html
<header>
  <h1>Meu site</h1>
  <nav>Menu de navegação</nav>
</header>

<main>
  <section>
    <h2>Sobre mim</h2>
    <p>Conteúdo principal da página.</p>
  </section>
</main>

<footer>
  <p>Todos os direitos reservados.</p>
</footer>
```
