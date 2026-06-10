# Site de Casamento

Site estático (HTML/CSS/JS) para um casamento, com galeria de fotos, informações de cerimônia, hospedagem e mais.

## Estrutura

- `index.html` — página principal do site
- `design-system.html` / `my-design-system.html` — referências de design
- `assets/` — imagens, ícones e bibliotecas (GSAP, ScrollTrigger)

## Como rodar localmente

Por ser um site estático, basta abrir o `index.html` no navegador, ou servir a pasta com um servidor local:

```bash
# Python 3
python -m http.server 8000
```

Depois acesse <http://localhost:8000>.

## Hospedagem

O site pode ser publicado gratuitamente via **GitHub Pages** (Settings → Pages → branch `main`).
