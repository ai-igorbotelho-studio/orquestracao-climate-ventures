# Infraestrutura de Orquestração — Proposta Viva × Climate Ventures

Site estático de uma página (PT/ENG), pronto para Cloudflare Pages.

## Pacote
- `index.html` — proposta completa e autocontida.
- `og-image.png` — preview social 1200×630.
- `_headers` — headers de segurança, cache e noindex.
- `robots.txt` — bloqueia indexação (proposta privada).

## Deploy (Cloudflare Pages)
1. Workers & Pages → Create → Pages → Upload assets.
2. Nome do projeto: `orquestracao-climateventures` (gera https://orquestracao-climateventures.pages.dev).
3. Arraste esta pasta e clique em Deploy.
Se usar outro nome/domínio, troque a URL em `canonical`, `og:url` e `og:image` do index.html.

## Idiomas
PT por padrão. Inglês: `?lang=en` ou botão POR | ENG.

## PDF
Rodapé → PDF POR / PDF ENG → "Salvar como PDF", A4, com "Gráficos de fundo" ativado.
