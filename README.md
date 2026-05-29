# 💕 Convite de Encontro

Página de convite romântico com calendário, escolha de comida e envio pro webhook.

## Como hospedar no GitHub Pages

1. Cria um repositório novo no GitHub (ex: `convite-date`)
2. Arrasta **todos** os arquivos desta pasta pra dentro do repo (ou `git push`)
3. No repo: **Settings → Pages**
4. Em **Source**, escolhe a branch `main` e a pasta `/ (root)`
5. Salva. Em ~1 min o site fica no ar em:
   `https://SEU-USUARIO.github.io/convite-date/`

## Arquivos

- `index.html` — site inteiro (HTML + CSS + JS num arquivo só)
- `.nojekyll` — desliga processamento Jekyll do GitHub Pages
- `README.md` — este arquivo

## Notas

- Fotos/gifs ficam salvos no navegador de quem acessa (IndexedDB) — não vão pro repositório.
- O dia, hora e comida escolhidos são enviados pro webhook n8n ao clicar em "esse aqui!".
- Funciona em HTTPS (GitHub Pages já é HTTPS).
