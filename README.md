# Ao Redor dos EUA (Around The U.S.)

Projeto do curso de Desenvolvimento Front-end da TripleTen.

🔗 **Acesse:** https://naibalreira.github.io/web_project_around_pt/

Página interativa onde o usuário edita o próprio perfil e compartilha fotos de lugares, com curtidas, exclusão de cartões e visualização ampliada das imagens.

## Funcionalidades

- Edição do nome e da descrição do perfil.
- Adição de novos cartões (título e link da imagem).
- Curtir e excluir cartões; abrir a imagem em tamanho ampliado.
- Validação dos formulários "Editar perfil" e "Novo local" com as mensagens padrão do navegador, exibidas abaixo de cada campo.
- Botão "Salvar" inativo enquanto houver campo inválido.
- Pop-ups fecham pelo botão, clicando na sobreposição ou pressionando Esc.
- Layout responsivo (320 px a 1280 px).

## Tecnologias

- HTML5 semântico
- CSS3 com metodologia BEM (Flexbox e Grid)
- JavaScript (DOM, eventos, `<template>`, Constraint Validation API)

## Estrutura

```
index.html
pages/index.css
blocks/      estilos por bloco BEM
scripts/     validate.js (validação) e index.js (lógica da página)
images/      ícones e imagens
vendor/      normalize.css
```
