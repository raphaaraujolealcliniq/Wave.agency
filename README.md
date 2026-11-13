# Wave Agency — Landing page

Site estático (HTML, CSS e JavaScript num só ficheiro), pronto para GitHub e Vercel.

## Ficheiros

| Ficheiro | Para que serve |
|---|---|
| `index.html` | O site completo |
| `favicon.svg` | Ícone do separador do navegador |
| `og-image.png` | Imagem que aparece quando o link é partilhado (WhatsApp, Facebook, LinkedIn) |

## Antes de publicar: editar o bloco CONFIG

No fim do `index.html`, procure `const CONFIG` e altere:

- `whatsapp`: o seu número com indicativo, sem + nem espaços (ex.: `351912345678`)
- `email`: o email da agência (por defeito `ola@waveagency.pt`, que só funciona depois de criar essa caixa de email)
- `bfEnd`: data e hora de fim da campanha Black Friday
- `discount`: o desconto (ex.: `-20%`)
- `spotsTotal` / `spotsLeft`: vagas totais e vagas restantes

O domínio `waveagency.pt` já está definido no topo do `index.html` (linhas `og:image`, `og:url` e `canonical`). Se usar outro domínio, troque-o nessas três linhas.

## Publicar

1. No GitHub, crie um repositório (ex.: `wave-site`).
2. Carregue os 4 ficheiros para a raiz do repositório (Add file → Upload files).
3. Na Vercel: Add New → Project → importe o repositório → Framework: **Other** → Deploy.
4. A cada alteração enviada para o GitHub, a Vercel publica automaticamente a nova versão.
