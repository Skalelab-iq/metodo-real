# Método R.E.A.L · Landing page

Página de venda da Turma 01 do Método R.E.A.L, mentoria para médicos.
Cada alteração salva neste repositório é publicada automaticamente pelo Netlify.

## Estrutura

| Arquivo | O que é |
| --- | --- |
| `index.html` | A página inteira (texto, estilo e comportamento) |
| `assets/` | Imagens, vídeo do topo e imagem de prévia do WhatsApp (`og-cover.jpg`) |
| `assets/fonts/` | Fontes Urbanist, Manrope e Instrument Serif |
| `favicon.png`, `apple-touch-icon.png` | Ícone da aba e do atalho no celular |
| `netlify.toml` | Configuração de publicação do Netlify |

## Ajustes comuns

- **Número do WhatsApp:** em `index.html`, procure `CONFIG` e altere `whatsapp` (só dígitos, com 55 + DDD).
- **Link por vendedor:** envie `https://SEU-DOMINIO/?v=5531999999999`. Os botões passam a chamar esse número.
- **Endereço do site:** quando o domínio próprio estiver ativo, trocar `metodo-real.netlify.app` pelo domínio em `index.html` (linhas `canonical`, `og:url`, `og:image`, `twitter:image`).
