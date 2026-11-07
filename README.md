# Coisas de Negócio

Página inicial estática, responsiva e pronta para GitHub Pages.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie o arquivo `index.html` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`, depois salve.

O endereço ficará parecido com:
`https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

## Personalizar os quadrados

No `index.html`, procure o comentário `Para editar`.
Cada cartão é um link. Você pode alterar:

- `href`: endereço que abre ao clicar;
- o emoji dentro de `emoji`;
- o texto dentro de `tile-title`;
- a descrição dentro de `tile-desc`;
- a cor em `style="background:#..."`.

O projeto não usa servidor, banco de dados, dependências ou domínio próprio.
