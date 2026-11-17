# Tabelas e Agrupadores

## O que aprendi
- As tabelas são utilizadas para **organizar informações em linhas e colunas**.
- Os agrupadores permitem **organizar e agrupar elementos** dentro de uma página HTML.
- `<div>` é utilizado para agrupar elementos em bloco.
- `<span>` é utilizado para agrupar elementos em linha.

## Tags principais
- `<table>` representa uma **tabela**, utilizada para organizar dados.
- `<tr>` representa uma **linha** dentro da tabela.
- `<th>` representa uma **célula de cabeçalho**, utilizada para identificar os dados de cada coluna.
- `<td>` representa uma **célula de dados**, onde ficam as informações da tabela.
- `<thead>` representa o **cabeçalho da tabela**.
- `<tbody>` representa o **corpo da tabela**, onde ficam os dados principais.
- `<div>` representa um **agrupador em bloco**, utilizado para organizar elementos.
- `<span>` representa um **agrupador em linha**, utilizado para destacar ou agrupar pequenos trechos de conteúdo.

## Exemplo

```html
<table>
    <thead>
        <tr>
            <th>Nome</th>
            <th>Curso</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td>Carlos</td>
            <td>HTML</td>
        </tr>
        <tr>
            <td>João</td>
            <td>CSS</td>
        </tr>
    </tbody>
</table>

<div>
    <p>Estou estudando <span>HTML</span>.</p>
</div>
```
