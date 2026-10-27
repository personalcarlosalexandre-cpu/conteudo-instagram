# conteudo-instagram

Repositório de apoio para publicar os posts da consultoria on-line de Carlos Alexandre (@alexandrepersonalrj).

O Instagram só aceita imagem por URL pública, sem redirecionamento. Este repositório existe para servir as fotos dos posts em URL crua (`raw.githubusercontent.com`), que o Instagram consegue baixar.

## Como funciona

1. As legendas ficam em `legendas/`, uma por post, nomeada pela data do post.
2. A foto de cada post fica em `fotos/`, com o nome da data do post: `fotos/AAAA-MM-DD.jpg`.
3. Na hora do post, a imagem é lida de:
   `https://raw.githubusercontent.com/personalcarlosalexandre-cpu/conteudo-instagram/main/fotos/AAAA-MM-DD.jpg`

## Requisitos da foto

- Vertical 4:5 — 1080 x 1350 px
- JPEG, até 8 MB
- Nome do arquivo exatamente igual à data do post: `2026-11-02.jpg`

## Publicando uma foto

Pelo site do GitHub, no celular:

1. Abra a pasta `fotos`
2. Toque em **Add file → Upload files**
3. Escolha a foto já renomeada com a data
4. **Commit changes**

Pronto. Depois disso a imagem está disponível para publicação.
