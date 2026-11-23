# Site — Dra. Maria Clara H. Entringer

Site institucional de página única (HTML + CSS + JS, sem build).

## Publicar no GitHub Pages
1. Crie um repositório no GitHub e envie todo o conteúdo desta pasta (o `index.html` deve ficar na raiz).
2. Em **Settings → Pages**, escolha *Deploy from a branch*, branch `main`, pasta `/ (root)`.
3. Para usar domínio próprio, adicione um arquivo `CNAME` com o domínio (ex.: `www.dramariaclara.com.br`) e configure o DNS. O HTTPS é ativado em Settings → Pages.

## Antes de publicar (editar em `index.html`)
- **WhatsApp:** procure `const WHATSAPP = ""` e informe o número com DDI+DDD, só dígitos (ex.: `5527999999999`).
- **Domínio:** troque `https://SEU-DOMINIO.com.br` pelo endereço real em `index.html` (tags `canonical`, `og:url`, `og:image`, `twitter:image`), `robots.txt` e `sitemap.xml`. Sem isso a pré-visualização de link não aparece. Em página de projeto do GitHub Pages (`usuario.github.io/repositorio`), use esse endereço completo.
- **Avaliações do Google:** edite a lista `REVIEWS` (e `NOTA`/`TOTAL`) no final do `index.html`.
- **CRO:** confirme o número no rodapé (`CRO-ES 9223`).
- **Fotos:** substitua os arquivos em `assets/img/` mantendo os nomes. Publique antes e depois apenas com autorização escrita dos pacientes.
- **Atualizar a pré-visualização:** após publicar, use o depurador de links do Facebook/Meta para limpar o cache da imagem.
