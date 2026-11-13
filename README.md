# Página Pessoal - Sofia Deolim Fernandes

Trabalho de HTML e CSS: uma página pessoal com curiosidades sobre mim e os lugares que já visitei e os que quero conhecer. O HTML cuida da estrutura e o CSS (`estilo.css`) cuida de toda a aparência.

## Sobre a página

A página tem três partes:

- **Curiosidades:** lista com algumas informações sobre mim (livros, séries, vôlei e filmes da Disney).
- **Lugares que já fui:** Orlando, Riviera de São Lourenço (Bertioga) e Paraty.
- **Lugares que quero conhecer:** Londres, Paris e Cancún.

Cada lugar tem foto, um texto contando a experiência (ou o motivo de querer ir) e um link com a localização.

## Tecnologias usadas

- HTML5
- CSS3

## Estrutura do projeto

```
.
├── index.html
├── estilo.css
├── README.md
└── imagens/
    ├── soso.jpg
    ├── disney.jpeg
    ├── riviera.jpeg
    ├── paraty.jpg
    ├── londres.jpg
    ├── paris.webp
    └── cancún.jpg
```

> O nome do arquivo HTML pode ser outro, mas ele precisa estar na mesma pasta do `estilo.css`.

## Como conectar o CSS ao HTML

No `<head>` do HTML existe a linha:

```html
<link rel="stylesheet" href="estilo.css">
```

## Como visualizar

1. Baixe ou clone este repositório.
2. Mantenha o HTML, o `estilo.css` e a pasta `imagens` juntos.
3. Abra o arquivo HTML no navegador (duplo clique).

## Conceitos de CSS aplicados

| Conceito | Onde foi usado |
|---|---|
| **Especificidade e herança** | O `body` define fonte e cor, que são herdadas pelos outros elementos. O seletor `#Sofia` (id) tem mais força que o `h1` e vence o conflito de cor. |
| **Unidades de medida** | `px`, `%`, `rem`, `em` e `vw` nos tamanhos de fonte, largura e espaçamentos. |
| **Display e position** | `display: block` para centralizar a foto de perfil, `display: flex` na lista de lugares e `position: relative` nos cards. |
| **Pseudoclasse e pseudoelemento** | `:hover` nos cards e nos links, `:first-child` no primeiro item das listas, `::before` e `::after` para colocar os ✨ nos títulos `h2`. |
| **Flexbox** | Os lugares viram cards lado a lado com `flex`, `flex-wrap` e `gap`. |
| **Responsividade** | `@media (max-width: 600px)` deixa um card por linha no celular e ajusta fontes e foto. |

## Detalhes do CSS

- **Foto de perfil:** centralizada com `margin: 20px auto`, borda rosa e cantos arredondados.
- **Cards dos lugares:** fundo branco, borda rosa e imagens com `object-fit: cover`, para todas ficarem do mesmo tamanho sem esticar.
- **Efeito ao passar o mouse:** o card muda de cor e sobe 5px.
- **Textos dos lugares:** estão dentro de `<pre>`, então foi usado `white-space: pre-wrap` para quebrar a linha dentro do card.

## Paleta de cores

| Cor | Código | Uso |
|---|---|---|
| Rosa claro | `#fdf0f6` | Fundo da página |
| Rosa forte | `#d6336c` | Título, bordas e nomes dos lugares |
| Roxo | `#7b2cbf` | Subtítulos e links |
| Roxo claro | `#9d4edd` | Títulos `h3` |
| Roxo escuro | `#4a2c5a` | Texto geral |

## Autora

**Sofia Deolim Fernandes**
