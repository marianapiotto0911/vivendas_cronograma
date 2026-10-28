# Vivendas de Barão — Cronograma da Obra

Site estático de um arquivo só (`index.html`), sem build e sem servidor. Compara o que foi executado em cada bloco
(lido do site de conferência) com o cronograma físico da planilha REV18.

## Publicar no GitHub Pages

1. Crie um repositório novo na mesma conta do site de conferência (ex.: `vivendas_cronograma`).
2. Envie o `index.html` para a raiz do repositório.
3. Em **Settings → Pages**, escolha a branch `main` e a pasta `/ (root)`.
4. O site abre em `https://<usuario>.github.io/<repositorio>/`.

**Importante:** fique na mesma conta (`<usuario>.github.io`) do site de conferência. É isso que permite ao novo site ler,
sozinho, a cópia que o de conferência guarda no navegador. Em outro endereço, use **Dados → Colar manualmente**.

## Como os dados funcionam

- Cronograma (metas por mês): editável na aba **Cronograma geral**; fica salvo no navegador (localStorage).
- Acompanhamento: lido de `vivendas_barao_state_v1` (cópia local do site de conferência) ou colado na aba **Dados**.
- Não há sincronização entre aparelhos — cada navegador guarda o seu.
