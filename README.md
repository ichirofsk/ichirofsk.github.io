# Portfólio · Evandro Ichiro Fuse Sakai

Site estático: `index.html` + pasta `assets/`. Não precisa de build nem de servidor.

## Publicar

**Vercel (mais rápido)**
1. Entre em vercel.com › Add New › Project.
2. Arraste a pasta `portfolio-evandro` (ou importe o repositório do GitHub, se subir lá).
3. Framework preset: **Other**. Build command: vazio. Output directory: `.` (raiz).
4. Deploy. Depois, em Settings › Domains, dá para ligar um domínio próprio.

**Netlify**
- app.netlify.com/drop › arraste a pasta. Pronto.

**GitHub Pages**
1. Crie um repositório (ex.: `ichirofsk.github.io` para ficar em `https://ichirofsk.github.io`).
2. Suba `index.html`, `assets/` e este README na raiz.
3. Settings › Pages › Source: branch `main`, pasta `/ (root)`.

## Testar no computador
Abra o `index.html` direto no navegador, ou rode na pasta:
`python3 -m http.server 8000` e acesse http://localhost:8000

## Editar
- Textos (PT e EN), projetos, prêmios e formação ficam no bloco `const UI` e `const DATA`, dentro do `<script>` no fim do `index.html`.
- Para trocar imagens, substitua os arquivos em `assets/` mantendo os nomes.

## Antes de publicar
- As telas do hub do Instituto 12 são recriações com dados fictícios. Confirme a autorização para mostrar o nome e o símbolo do instituto.
- Os prints das avaliações da Convem e do agente de WhatsApp usam dados anonimizados.
