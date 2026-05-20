# CapView Plus — PWA pronto para GitHub Pages

Arquivos principais:

- `index.html`
- `manifest.webmanifest`
- `sw.js`
- `icons/`

## Como testar localmente

Não abra por `file://`, porque Service Worker e instalação PWA não funcionam assim.

Use um servidor local na pasta do projeto:

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## Como publicar no GitHub Pages

Suba todos os arquivos na raiz do repositório ou na pasta publicada pelo Pages. Depois acesse a URL HTTPS gerada pelo GitHub Pages.

No Chrome/Edge, o botão de instalar deve aparecer na barra de endereço ou no menu do navegador após o carregamento correto do manifest e do service worker.
