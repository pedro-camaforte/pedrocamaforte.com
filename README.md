# pedrocamaforte.com

Site pessoal. HTML + CSS estáticos, sem build e sem dependências.

## Estrutura

```
index.html        -> https://pedrocamaforte.com/      (inglês, padrão)
pt/index.html     -> https://pedrocamaforte.com/pt/   (português)
404.html
assets/style.css  -> estilo compartilhado pelas duas páginas
assets/favicon.svg
.htaccess         -> HTTPS, www -> sem www, 404
```

`/?lang=pt` redireciona para `/pt/`.

## Deploy na Hostinger

O conteúdo deste repositório é exatamente o conteúdo de `public_html`.

- **Git (recomendado):** hPanel → Avançado → Git → repositório
  `https://github.com/pedro-camaforte/pedrocamaforte.com.git`, branch `main`,
  diretório em branco (= `public_html`). Depois é só clicar em *Deploy* a cada push
  (ou ativar o webhook de auto-deploy).
- **Manual:** enviar todos os arquivos (incluindo `.htaccess`) para `public_html`
  pelo Gerenciador de Arquivos.

## Conteúdo pendente

Tudo que aparece em caixinha tracejada âmbar no site é placeholder (classe `.ph`).
Qualquer texto novo precisa entrar nos dois arquivos: `index.html` e `pt/index.html`.
