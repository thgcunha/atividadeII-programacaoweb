# Diagnóstico do código legado

| # | Problema identificado | Tipo (HTML/CSS) | Gravidade | Solução proposta |
|---|---|---|---|---|
| 1 | Uso de `<font>` | Apresentação | Alta | Definir `font-family`, `font-size` e `color` no CSS. |
| 2 | `bgcolor` no HTML | Apresentação | Alta | Usar `background-color` no CSS externo. |
| 3 | Falta de `<!DOCTYPE html>` | Estrutura | Alta | Declarar HTML5 no início do arquivo. |
| 4 | Falta de `<meta charset="UTF-8">` | Estrutura | Alta | Informar a codificação no `<head>`. |
| 5 | Uso de `<center>` | Apresentação | Média | Centralizar com `text-align` e margens no CSS. |
| 6 | Uso de `<br>` para espaçamento | Apresentação | Média | Controlar espaços com `margin` e `padding` no CSS. |
| 7 | Ausência de tags semânticas | Estrutura | Alta | Usar `header`, `nav`, `main`, `section`, `article` e `footer`. |
| 8 | Ausência de metadados | Estrutura | Média | Adicionar autor, descrição e palavras-chave. |
| 9 | Nenhum CSS externo | Apresentação | Alta | Criar `estilo.css` e vinculá-lo com `<link>`. |
| 10 | Informações sem hierarquia de títulos | Estrutura | Média | Organizar o nome do site em `h1`, o código em `h2` e os detalhes em `h3`. |

Essas mudanças separam conteúdo de aparência, facilitam a manutenção e permitem que leitores de tela e mecanismos de busca entendam melhor o rastreio. Os dados exibidos no site são os exemplos fictícios do enunciado.
