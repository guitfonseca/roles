# rolê 🪩

Acervo pessoal de bares e lugares. Abre em "Qual é a sua vibe hoje?", sugere lugares em cards e mostra tudo no mapa.

## Subir no GitHub Pages
1. Crie um repositório (ex.: `role`) e suba `index.html` e `lugares.json`.
2. Settings → Pages → Deploy from branch → `main` / root.
3. Abra `https://SEU-USUARIO.github.io/role/` no celular e adicione à tela de início.

## Pra adicionar pelo celular (⚙️ no app)
- **Token do GitHub**: github.com/settings/personal-access-tokens → Fine-grained → só este repositório → Contents: Read and write.
- **Chave da Anthropic** (opcional, pra ler prints): console.anthropic.com → API Keys. Cada print custa centavos.

Os dois ficam só no navegador do seu celular, nunca no repositório.

Cada lugar salvo vira um commit em `lugares.json`; os prints vão pra pasta `prints/`. O site leva ~1 min pra refletir pra quem abre sem token.
