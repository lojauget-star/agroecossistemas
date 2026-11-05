# Agroecossistemas | Resenha crítica interativa

Apresentação interativa de **11 slides** sobre Bowness et al. (2025), *Beyond redistribution: a framework for reparative just transitions*, usando Vite.

## Rodar localmente

```bash
npm install
npm run dev
```

## Publicação na Netlify

- Conectar o repositório `lojauget-star/agroecossistemas` à Netlify.
- Branch: `main`; build command: `npm run build`; publish directory: `dist`.
- O arquivo `netlify.toml` já contém os dois últimos parâmetros.

## Publicação no GitHub Pages

- GitHub > Settings > Pages > Build and deployment > Source: **GitHub Actions**.
- O workflow `.github/workflows/deploy-pages.yml` instala, compila e publica automaticamente ao dar push na `main`.
- URL esperada após o sucesso do deploy: `https://lojauget-star.github.io/agroecossistemas/`.

## Arquivos

- `index.html`: 11 slides, conteúdo e notas de fala.
- `src/style.css`: identidade verde-escura, imagem de fundo e transições.
- `src/main.js`: navegação por slides, atalhos, toque, tela cheia e notas.
- `public/mundau.png`: fotografia incluída localmente.

## Controles

- `←` / `→` ou `Page Up` / `Page Down`: avançar ou voltar.
- `N`: notas; `F`: tela cheia; `P`: imprimir.

## Referência

Bowness, E. et al. (2025). *Beyond redistribution: a framework for reparative just transitions*. **Environmental Research Letters**, 20, 094058. https://doi.org/10.1088/1748-9326/adf905

Fotografia da Barra do Mundaú: [Viagens e Caminhos](https://www.viagensecaminhos.com/wp-content/uploads/2025/10/mundau.jpg).
