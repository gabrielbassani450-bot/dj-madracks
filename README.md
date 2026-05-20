# DJ MADRACKS ORIGINAL — Landing Page

Landing page profissional do DJ e produtor musical **DJ MADRACKS ORIGINAL**
(Leandro Delazeri) — São Paulo, BR.

Site estático de página única em HTML, CSS e JavaScript puro, sem frameworks.
Estética "Apple × Liquid Glass" com identidade streetwear: fundo em vídeo,
glassmorphism, tipografia Clash Display / Satoshi / Space Mono, animações a
60fps, partículas e parallax — tudo com `prefers-reduced-motion` e otimizações
para mobile.

## Estrutura

- `site/index.html` — site completo (HTML, CSS e JS embutidos)
- `site/assets/` — vídeo de fundo, foto recortada, logo e poster
- `.claude/launch.json` — configurações de servidor de desenvolvimento

## Rodar localmente

Servidor estático na pasta `site/`:

```bash
python -m http.server 5173 --directory site
```

Alternativa com Node:

```bash
npx serve site
```

Depois abra `http://localhost:5173`.

## Conteúdo

- Faixa mais tocada, mapa de audiência, playlist e formulário de booking
- Integração com Spotify, Instagram, TikTok e Linktree

---

© 2026 DJ Madracks Original · São Paulo, BR
